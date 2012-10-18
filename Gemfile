source 'https://rubygems.org'           #comments updated 10/18

gem 'rails', '3.2.8'                    #RAILS, duh
gem 'bootstrap-sass', '2.0.4'           #Bootstrap sass for css design and layout
gem 'bcrypt-ruby', '3.0.1'              #runs background for authorization method and helper, FOR has_secure_password method
gem 'faker', '1.0.1'                    #I_DON'T_KNOW_YET
gem 'will_paginate', '3.0.3'            #likely for page numbers at the bottom? 
gem 'bootstrap-will_paginate', '0.0.6'  #somehow a bridge for page numbers at the bottom and bootstrap? 
gem 'jquery-rails', '2.0.2'             #to use jquery?  although have not seen when this comes into play
                                        #is it always running in the background?  Can check on github

group :development, :test do
  gem 'sqlite3', '1.3.5'                #to create development test database 
  gem 'rspec-rails', '2.11.0'           #to include rspec in rails
  gem 'guard-rspec', '1.2.1'            #WHAT WAS GUARD?  I FORGET - THINKN LESSON 3, OR 4? 
  gem 'guard-spork', '1.2.0'            #I_DON'T_KNOW_YET CHECK GITHUB
  gem 'spork', '0.9.2'                  #To run spork server on which to run rspec tests in development
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.5'           #maybe required to runn sass in rails (but for development only?) co Github
  gem 'coffee-rails', '3.2.2'           #Should do coffee script tutorial in codeschool
  gem 'uglifier', '1.2.3'               #I_DON'T_KNOW_YET seem to remember was mentioned, check rails tutorial
end

group :test do
  gem 'capybara', '1.1.2'               #I_DON'T_KNOW_YET dsl for something, can't recall... having to do w/tests
  gem 'factory_girl_rails', '4.1.0'     #I_DON'T_KNOW_WELL_YET, shown in lesson 6, co github
  gem 'cucumber-rails', '1.2.1', :require => false  #I_DON'T_KNOW_YET
  gem 'database_cleaner', '0.7.0'       #I_DON'T_KNOW_YET
  # gem 'launchy', '2.1.0'              #I_DON'T_KNOW_YET, LESSON 7 I THINK
  # gem 'rb-fsevent', '0.9.1', :require => false  #I_DON'T_KNOW_YET
  gem 'growl', '1.0.3'                  #I_DON'T_REMEMBER ; check railstutorial, similar to notification on my blog? 
end

group :production do
  gem 'pg', '0.12.2'                    #I_DON'T_KNOW_YET; thinking is for postgreSQL for heroku production server? 
end