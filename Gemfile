source :rubygems

# add in all the runtime dependencies

gem 'rails', '>= 3.0.0'

gem 'warden'
gem 'devise', '= 1.1.3'

gem 'mongoid', '2.0.0.beta.19'
gem 'bson_ext', '1.1.5'
gem 'locomotive_mongoid_acts_as_tree', '0.1.5.1', :require => 'mongoid_acts_as_tree'
gem 'will_paginate'

gem 'haml', '= 3.0.18'
gem 'locomotive_liquid', '2.2.2', :require => 'liquid'
gem 'formtastic', '>= 1.1.0'
gem 'inherited_resources', '>= 1.1.2'

gem 'rmagick', '= 2.12.2'
gem 'locomotive_carrierwave', '0.5.0.1.beta2', :require => 'carrierwave'

gem 'custom_fields', '1.0.0.beta2'
gem 'fog', '0.3.7'
gem 'mimetype-fu'
gem 'actionmailer-with-request'
gem 'heroku'
gem 'httparty', '>= 0.6.1'
gem 'RedCloth'
gem 'delayed_job', '2.1.2'
gem 'delayed_job_mongoid', '1.0.1'
gem 'rubyzip'
gem 'locomotive_jammit-s3', :require => 'jammit-s3'

# The rest of the dependencies are for use when in the locomotive dev environment

group :development do
  # Using unicorn_rails instead of webrick (default server)
  gem 'unicorn'
end

group :test, :development do
  gem "ruby-debug", :platforms => :mri_18
  gem "ruby-debug19", :platforms => :mri_19
end

group :test do
  gem 'autotest'
  gem 'ZenTest'
  gem 'growl-glue'
  gem 'rspec-rails', '2.3.1'
  gem 'factory_girl_rails'
  gem 'pickle'
  gem 'capybara'

  gem 'database_cleaner'
  gem 'cucumber', '0.8.5'
  gem 'cucumber-rails'
  gem 'spork'
  gem 'launchy'
  gem 'mocha', :git => 'git://github.com/floehopper/mocha.git'
end