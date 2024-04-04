# RackEmApp Release Notes
*Platform - 5th April 2024*
 - Fixed issue with team handicaps not being saved/applied properly to competitions
 - Fixed break indicator in Evolve's custom stream overlay
 - Fixed issue with BD and RD not displaying on group tables, which in turn caused the competition pages to throw an error
 - Added platform dashboard for a quick view of matahces in play
   
*Platform - 2nd April 2024*
 - Removed support for Facebook and Google logins
 - Revamp of the Competition Entry management screen
 - Added "League Table Profiles" to standardise the use of league tables across leagues and competitions, and allow individual divisions to run different league table setups
 - Added Hangfire for background job processing
 - Added Hangfire job to clean up ShotClockSubscribers table

*Platform - 27th March 2024*
 - Fixed an issue when registering a new team from an existing logged in account was not loading the tabkes for the default venue correctly
 - Added support for Receipts to be generated when registering a new team and paying by Stripe
