# RackEmApp Release Notes
This page displays the release note information for the RackEmApp Platform and the RackEmApp Mobile Application. To subscribe to changes in our release notes, you can watch [this GitHub Repository](https://github.com/RackEmApp/releasenotes).

---
***Platform** - 9th August 2024*
 - Fixed issue accessing fixtures and results admin when no active seasons
 - Fixed issue accessing fixtures page following a fix yesterday, nullable object on assigned table
   
***Platform** - 8th August 2024*
 - Fixed issue transferring players when in pre-season
 - Added new "Dish Table" page
 - Fixed issue with outstanding byes showing on fixture page
 - Fixed issue with fixture pages not showing assigned venues

***Platform** - 7th August 2024*
 - Performance improvement adding team to division in season wizard
 - Fixed wrong message title when adding a bye in Season Wizard
 - Adding ranking number to doubles ranking pages
 - Fixed issues with captain detials not loading on team registration page
 - Fixed issues with All Divisions fixture page not showing comp matches

***Platform** - 5th August 2024*
 - Added disclaimer for Stripe entry fees that may violate their gambling restrictions
 - Fixed bug where number of entries in the competitions list was including draft entries
   
***Platform** - 4th August 2024*
 - Fixed issue displaying cup matches on home page when hoe  team is a Bye
 - Fixed issue with Fixtures pages not showing Cup matches due to the inccorrect filter on the query
 - Fixed issue with referee mode erroring if you set a frame winner before a lag winner
 - Fixed issue that remove players from competition entries when marking them as paid
 - Fixed issue not displaying the individual competition placeholder when that is the next fixture date
 - Removed auto refresh on error page

***Platform** - 2nd August 2024*
 - Added support for app to auto-login to venue booking page
 - Added ability for players to optionally include their name and display it against the booking
 - Added quick checkout for when there is no money to be paid

***Platform** - 31st July 2024*
 - Fixed issue saving a booking using multiple resources
 - Fixed issue where booking note not being constructed properly
 - Fixed issue rescheduling competition matches

***App** - 25th July 2024 (1.1.10)*
 - Fixed numerous issues with the new Live Scores screen
 - Fixed an issue with deselecting players as the away team when you are using the "once per section" setting
 - Fixed an issue preventing the selection of a player so captain;s unable to enter people into a comp


***Platform** - 25th July 2024*
 - Fixed issue with dashboard healthcheck displaying overdue firxtures for deleted teams
 - Fixed issue with Perpetuals not allowing you to switch to Individuals when they are set as Team
 - Minor update to License Service
 - Added ability to alter the date played for any given match
 - Prep work for displaying results by date played rather than scheduled date - including a data script to fix old erroneous data
 - Improved performance of loading Venue page
 - Bug fixes relating to accessing venue pages for shared venues
 - Added ability to deactivate a venue to hide from your venues list page
 - Results pages will now show matches in order of date played, not necessarily the scheduled date for the match. This was a particular problem when cup matches had "played by" deadlines. 

***Platform** - 24th July 2024*
 - Added recording of the person and date/time of team registration approvals
 - Fixed validation bug on ReRegistration price for a season allowing it to be saved as
 - Performance improvements on Doubles averages pages

***Platform** - 23rd July 2024*
 - Fix to creation of singles leagues and competitions
   
***Platform** - 18th July 2024*
 - Updates to bookings to access existing basket
 - Fix to competition team scorecard editor not resetting forfeit status of a frame
   
***Platform** - 17th July 2024*
 - Fixed adding a perpetual roll of honour record
 - Added Login indicator to bookign screen
 - Added league admin ability to use match codes as bookign discounts for approved comps
 - Changes to support secondary clock time and timed pause for challenge matches for BTF

***Platform** - 15th July 2024*
 - Fixes to yesterdays update
 - Amendments to support positive points "penalties"
   
***Platform** - 14th July 2024*
 - Added new "All Divisions" option for league tables
 - Optimized Fixtures pages for better performance
 - Optimized Results pages for better performance
 - Optimized league landing/home page
 - Optimized the querying that takes place on every page render in "MakeLeaguePageViewModel"

***Platform** - 12th July 2024*
 - Dedicated Singles Leagues functionality
 - Fixes to the Healthcheck in the dashboard

***Platform** - 10th July 2024*
 - Finalized the licensing additions
 - Added Healthcheck to the dashboard

***App** - 8th July 2024 (1.1.6)*
 - Fixed an issue where if away captain's selected a forfeit player, it would not allow the section to be locked in.
 - Added support for all android versions from 5 and above
 - Fixed an issue loading competition matches when the table had been booked through the table booking system on a shared venue
 - Added support for league games to be settle by a draw decider

***Platform** - 8th July 2024*
 - Added support for league matches to be decided by a draw decider
 - Fixed issue where booking emails were not including the date
   
***Platform** - 7th July 2024*
 - Fixed issue completing competition matches
 - Fixed issue which meant when updating yoru details in the app it wasn't updating the user email address
 - Fixed an issue which there an error deleting a user relating to the delete method not loading the userleagues
 - Altered the emailing of the draw method to default to the User email, if the player is linked to a user

***Platform** - 5th July 2024*
 - Fix to rankings algorithm that was miscalculating the number of appearances
 - Fixed bug that impacts new live scores screen for new app
 - Rewritten ELO Algorithm
 - Migrated all league post result processing to a queued background job
 - 
***App** - 4th July 2024 (1.1.2)*
 - Captains can now create Friendly Matches so they can live score their non-league/competition matches
 - Scoreboard functionality has been built as Native, including Table mode for venues, and will keep the screen on as standard without needing to fiddle with device settings
 - League tables migrated to run in the mobile app instead of a browser link
 - Player rankings migrated to run in the mobile app instead of a browser link
 - App now available in the Amazon App store for easy download to Fire tablets
 
***Platform** - 3rd July 2024*
 - Singles averages fully refactored into its own services to make it more performant (<10% of original time taken)
 - Added endpoints for League Tables and Rankings to be supported natively in the mobile app
 - Fixed issed editing competion match entries if there are two matches with the same player/entry
 - Fixed access to rankings from roll of honour erroring when there is no current season in play

***Platform** - 2nd July 2024*
 - Using "Big screen mode" on a tablet allows tournament directors to quickly schedule matches by tapping the time, or editing the score by tapping that all from a single kanban style view
 - Added sponsors rotation to Big Screen mode for competitions
 - Added better feedback for failed discount codes in table bookings to help uses know why they may not work
 - Further scoreboard enhancements ready for the app update (work in progress)

***Platform** - 25th June 2024*
 - Invoices can now be paid by card by anyone not just the captain
 - Payment report not including stripe payments
 - Payment report not showing right current price when registration type is "Per player"
 - Changes to further support the Scoreboard migration to the mobile app (work in progress)
 - Added endpoints to create friendlies ready for the feature to go live in the mobile app(work in progress)

***Platform** - 19th June 2024*
 - Added ability for leagues to set their own Privacy Policy and Terms and Conditions.
 - Added ability for a season to have some terms set to provide information to captain's registering online
 - Added shortcut buttons to the admin scorecard editor to make it easier to forfei matches, saving a few hundred clicks
 - Fixed the API results endpoint to display the right player information
 - Amendments to the Mobile App API to support the upcoming scoreboard feature (work in progress)

***Platform** - 13th June 2024*
 - Additional endpoint changes to support upcoming functionality (Scoreboard) in mobile app
 - Added the custom field results for team registrations into the dashboard approval list

***Platform** - 10th June 2024*
 - Upgrade to .NET 8
 - Implemented additionals ecurity headers to achieve an A rating from securityheaders.com
 - Brought all javascript sources local to prevent agains man in the middle attacks
 - Implement content security policy
 - Fixed bug creating deciding frame

***Platform** - 6th June 2024*
 - Added new handicap method "Stoodlarke Handicap Algorithm", detaisl in documentation
 - Added handicaps to competition live scores page
 - Fixed issue with team competition matches pre-season not committing frame data and throwing an error
 - Fixed venue pages not opening due to null opening times list
 - Fixed update of seasonteam throwing error when no captain or vice captain is defined

***Platform** - 5th June 2024*
 - Bug fix for the app throwing an error when your next match is away to an either/or match
   
***Platform** - 3rd June 2024*
 - Big update for Double Elimination competitions introducing templates to make managing a DE tournament easy
 - Moved the TinyMCE WYSIWYG editor to locally hosted instead of cloud hosted to solve maximum page views error
   
***Platform** - 29th May 2024*
 - Fixed issue with team registration page not showing the right wordingwhen paying per player.
 - Fixed issue removing lines from basket
 - Fixed issue pressing New Player in the admin team creation in season wizard

***Platform** - 27th May 2024*
 - Fixed issue with player auto population for competition matches which manifests itself in the app when frame captions are null
 - Set team names to be clickable links when viewing a group stage team competition

***App** - 27th May 2024 (1.0.22)*
 - Fixed issue where non-captain's could not see the away player in scorecards
 - Set the Dispute details box to be required so you can no longer submit a dispute without explaining why

***Platform** - 24th May 2024*
 - Fixed bank details showing incorrectly on season basics page
 - Fixed bug accessing old season in certain scenarios

***Platform** - 22nd May 2024*
 - Fixed issue with roll of honour not being populated for pre-determined knockouts
 - Fixed issue with walkover finals not awarding roll of honour
 - Fixed issue with news areticle email templates getting the link wrong
 - Fixed issue creating losers comp from groups

***Platform** - 20th May 2024*
 - Fixed issue with payment report not including additional player fee in payment calculations
 - Fixed issue generating competition groups not displaying matches

***Platform** - 14th May 2024*
 - Fixed several email templating issues
 - Added ability to Archive competitions
 - Added ability for articles to be hidden from home page
 - Fixed conert bye to team not creating a league table record
 - Fixed the lag not alernating between sets in sets matches
 - Added new feature to email your competition entrants
 - Minor UI improvements to live scores and scorecards

***Platform** - 13th May 2024*
 - Made changes to stop progressing competitions and divisions without a leage table profile beig assigned
 - Added the ability to convert a League bye into a real team part way through the season

***Platform** - 10th May 2024*
 - Altered new Email service to not catch exceptions to allow Hangfire to do them and provide better logging and exception management capabilities.
 - Fixed issue where transferring players pre-season would not detect the right "old" team and keep them present in that list
 - Improvements to internal platform admin tools (player and user searching)
   
***Platform** - 9th May 2024*
 - Fixed bug with Player Stats not calculating right when the player has been transferred
 - Fixed issue updating players details from the mobile app

***App** - 9th May 2024 (1.0.21)*
 - Made the Save Player toast message more descriptive when erroring
 - Prevented captains changing player details when players have a user account
 - Fixed issue in Matches list where clicking the away team name would take you to the home team profile

***Platform** - 8th May 2024*
 - Complete replacement of ElasticEmail to own templating system and emailing using Gmail SMTP.
 - Bug fixes for Sets matches
 - Fixed bug where creating losers comp doesn't pull through results that were settled by decider

***Platform** - 5th May 2024*
 - Fixed bug which stops competition page (groups) showing when no league table profile is defined
 - Fixed scoreboard showing complete match too early for Sets based matches
 - Fixed error in processing comp matches where league table profiles have match section bonus points, but no match format is assigned
 - Added sets matches back in
 - Began switch of emailing engine away from Elastic Email
 - Fixed bug saving players in the app when registering for a team on a different league day
 - Fix to league table sort when by Wins, Frames, Head to Head

***Platform** - 1st May 2024*
 - Fixed issue which caused new players not be registered when using the app

***Platform** - 29th April 2024*
 - Fixed issue saving player due to incorrect input type in code
 - Fixed issue setting player names blank when they have a user account and saving them in the admin player list

***Platform** - 28th April 2024*
 - Prevented app player registrations from saving if the player is already registered to a team for that season
 - Prevent the saving of a competition entry with a blank description

***Platform** - 26th April 2024*
 - Fixed issue with competition date picker not hiding the date in competition management
 - Fixed issue with competition page not displaying round date
 - Added 1 decimal place to any average method using a combination of calculations

***Platform** - 24th April 2024*
 - When creating a competition for losers in a Series, it will associate that competition to the series. This will allow you to run a plate which also scores points towards th rankings.
 - Complete Competition will now be able to be performed more than once. This means if a mistake is made it will clean up the erroneous roll of honour and trophies
 - Bug fix series competition tables not identifying entries when obtaining frame results
 - Added QR code to competition draw sheet to allow direct access to the scoreboard
 - Fixed issue showing RD and BD instead of the actual values in league tables
 - Fixed issue preventing download of fixtures CSV when there is a Bye/no venue or table assigned
 - Added the ability for you to re-compelte competitions, which will overwrite existing Roll of Honour, Series Points and Trophies to help correct mistakes.
   
***Platform** - 23rd April 2024*
 - Added collapsible round settings in competition management for a better UX
 - Added On/By for dates in non single day event group stages (singles leagues)
 - Tidied up competition page where it was not a single day event with scheduled matches making the rounds look funny

***Platform** - 22nd April 2024*
 - Extended Game Based averages to include complex calculation requirement for Cowes District Pool League

***App** - 22nd April 2024 (1.0.20)*
 - Fixed image upload picker issues across Android and iOS
 - Fixed issue where "points based on sections" not allowing you submit the result

***Platform** - 21st April 2024*
 - Added new player statistics method for "Game Based" which will consider a match section as a game within a match and award wins/losses accordingly.

***Platform** - 18th April 2024*
 - Added ability to create a new "Parent" team for season teams to be registered/moved into
 - Fixed issue where registering an existing player through the app which should be paid for online not directing to the checkout
 - Fixed issue where multi-league setups not showing the right assigned team to a player
 - Fixed issue accessing referee mode/not setting match format to null when saving competition details
 - Fixed issue with live league tables not working
 - Fixed issue preventing completion of a group stage competition when Byes exist
 - Added ability for competition table selection in predetermined kncomouts to auto-assign to downstream rounds

***App** - 16th April 2024 (1.0.16)*
 - Fixed issue where you could not enter team competitions from the dashboard

***App** - 15th April 2024 (1.0.15)*
 - Added button in my teams to go straight to Averages/Player Stats
 - Fixed scorecard loop not disposing properly
 - Fixed issue when registering a new player that requires payment not routing to the checkout properly
 - Hidden New Player button when the user has no captain rights

***Platform** - 15th April 2024*
 - Fixed Arbitrary Points System not saving values correctly
 - Fixed Arbitrary Points System not awarding points correctly
 - Fixed issue with competition entries not loading the partial view correctly
 - Set toasters to appear on top of modals
 - Updated player list to show read only email address when a player is linked to a user

***Platform**- 14th April 2024*
 - Added advance button to group matches to allow singles leagues with unfulfilled matxhes to be progressed or completed
 - Made a change to record the match played date even if the lag or start match button is not pressed
 - Fixed scoreboard not showing the complete button when in a best of match with handicaps
 - Fixed issue which would error on season checkout when creating league tables

***Platform** - 13th April 2024*
 - Fixed issue with Stripe checkout not completing correctly when returned back to RackEmApp
 - Added Averages Name property to allow for a button to be added in the app
 - Fixed issue where Predetermined Knockout rounds were not editable
 -  Fixed live scores issue when there is a comp match in play but is not a group match throwing an error due to missing league table profile
 - Fixed issue preventing the generation of receipts when no competition entries are selected

***Platform** - 12th April 2024*
 - Fixed issue saving "result based on match sections" property in league table profile
 - Fixed issue with competition groups league table profiles nlot saving/overwriting with blank values
 - Added Lola's Pool party branding to 147 sports custom screens
 - Removed table clash flag in new season wizard fixtures list for byes as its not relevant
 - Fixed a bug with Bye removal in new season wizard not working
 - Fixed an issue starting a round in a group round which is not a single day event not working

***App** - 12th April 2024 (1.0.14)*
 - Fixed issue with Start Match button not appearing
 - Added message at the top of teams screen to make it more obvious that they need to swipe between teams when they are registered to more than one

***Platform** - 5th April 2024*
 - Fixed issue with team handicaps not being saved/applied properly to competitions
 - Fixed break indicator in Evolve's custom stream overlay
 - Fixed issue with BD and RD not displaying on group tables, which in turn caused the competition pages to throw an error
 - Added platform dashboard for a quick view of matahces in play
   
***Platform** - 2nd April 2024*
 - Removed support for Facebook and Google logins
 - Revamp of the Competition Entry management screen
 - Added "League Table Profiles" to standardise the use of league tables across leagues and competitions, and allow individual divisions to run different league table setups
 - Added Hangfire for background job processing
 - Added Hangfire job to clean up ShotClockSubscribers table

***Platform** - 27th March 2024*
 - Fixed an issue when registering a new team from an existing logged in account was not loading the tabkes for the default venue correctly
 - Added support for Receipts to be generated when registering a new team and paying by Stripe
