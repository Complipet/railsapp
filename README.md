# railsapp
Ruby on Rails web application for CompliPet Social Pet Network
Guidelines for Developers Contribution

Switch to Branch development and do all your contribution there
Do not create any new branch for any new features. put all your code in developement branch only.
Once your pull request is accepted the code will be tested on test server and if everything is as expected will be merged to master for production. (You do not merge to master).
Commit Often.
Please write full commit message explaining what you changed / added. Do not use shortcuts in those messages.
Prerequisites

Ruby 2.0
Rails 4.1.8
ImageMagick
NodeJS
PG Gem and its corresponding dependencies as per your system.
For Production - Nginx and Passenger
How to Set Up

mkdir CompliPet
cd CompliPet
git clone git@bitbucket.org:complipetdevteam/railsapp.git
cd railsapp
Configure

Create a folder called "system" inside "public" folder if not present already.
Set Database Environment Variables: DB_PASS_DEV and DB_PASS_PRD
Set Devise Secret Key Environment Variable DEVISE_SECRET_KEY for production.
Dev DB as petster and Production DB as petster_production
more instructions coming soon....
