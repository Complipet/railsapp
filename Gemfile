source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.8'
#gem 'rails', '4.2.0'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
#gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

gem 'rails_12factor', group: :production
ruby "2.2.1"
gem 'devise'
gem "omnicontacts"
gem 'has_friendship'
gem 'mailboxer'
gem 'rails_admin'
#gem 'forem', :github => "radar/forem", :branch => "rails4"
gem 'kaminari'
#gem 'kaminari', :git => 'git@github.com:amatsuda/kaminari.git'
gem "paperclip", git: "git://github.com/thoughtbot/paperclip.git"

#  NOTE FOR UPGRADING FROM 4.3.0 OR EARLIER       #
##################################################

#Paperclip is now compatible with aws-sdk >= 2.0.0.

#If you are using S3 storage, aws-sdk >= 2.0.0 requires you to make a few small
#changes:

#* You must set the `s3_region`
#* If you are explicitly setting permissions anywhere, such as in an initializer,
#  note that the format of the permissions changed from using an underscore to
#  using a hyphen. For example, `:public_read` needs to be changed to
#  `public-read`.

#If you want to continue using an earlier version of aws-sdk, replace
# aws-sdk with aws-sdk-v1 in your Gemfile.
gem 'acts_as_votable', '~> 0.10.0'
#gem 'mreinsch-acts_as_rateable'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'sass-rails', '>= 3.2'
gem 'simple_form'
gem 'country_select'
gem 'state_select'
gem 'carmen-rails', '~> 1.0.0', github: 'jim/carmen-rails'
gem 'public_activity'
gem 'cancancan', '~> 1.10'
gem 'jquery-ui-rails'
#gem 'jquery-infinite-pages'
gem 'bootstrap-filestyle-rails'
gem 'icheck-rails'
gem 'friendly_id'
#, '~> 5.1.0'