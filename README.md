# railsapp
Ruby on Rails web application for CompliPet Social Pet Network
<h1>Guidelines for Developers Contribution</h1>

Switch to Branch development and do all your contribution there
Do not create any new branch for any new features. put all your code in developement branch only.
Once your pull request is accepted the code will be tested on test server and if everything is as expected will be merged to master for production. (You do not merge to master).
Commit Often.
Please write full commit message explaining what you changed / added. Do not use shortcuts in those messages.
<h1>Prerequisites</h1>
<ul>
<li>Ruby 2.0
<li>Rails 4.1.8
<li>ImageMagick
<li>NodeJS
<li>PG Gem and its corresponding dependencies as per your system.
<li>For Production - Nginx and Passenger
</ul>
<h1>How to Set Up</h1>
<ul>
<li>mkdir CompliPet
<li>cd CompliPet
<li>git clone git@bitbucket.org:complipetdevteam/railsapp.git
<li>cd railsapp
</ul>
<h1>Configure</h1>
<ul>
<li>Create a folder called "system" inside "public" folder if not present already.
<li>Set Database Environment Variables: DB_PASS_DEV and DB_PASS_PRD
<li>Set Devise Secret Key Environment Variable DEVISE_SECRET_KEY for production.
<li>Dev DB as petster and Production DB as petster_production
</ul>
more instructions coming soon....
