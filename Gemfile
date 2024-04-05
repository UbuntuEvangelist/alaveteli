source 'https://rubygems.org'

gem 'rails', '7.0.8.1'

gem 'pg'

# New gem releases aren't being done. master is newer and supports Rails > 3.0
gem 'acts_as_versioned', :git => 'git://github.com/technoweenie/acts_as_versioned.git'
gem 'charlock_holmes'
gem 'dynamic_form'
gem 'exception_notification', '>= 4.0.0'
gem 'fancybox-rails', '>= 0.3.0'
gem 'foundation-rails', '>= 5.2.2.0'
gem 'jquery-rails', '~> 4.0.1'
gem 'jquery-ui-rails', '>= 4.1.1'
gem 'json'
gem 'mahoro'
gem 'memcache-client'
gem 'net-http-local', :platforms => [:ruby_18, :ruby_19]
gem 'net-purge'
gem 'rack', '>= 2.2.8.1'
gem 'rack-utf8_sanitizer', '>= 1.3.2', :platforms => [:ruby_19, :ruby_20, :ruby_21]
gem 'rake', '0.9.2.2'
gem 'rails-i18n'
gem 'recaptcha', '~> 0.3.1', :require => 'recaptcha/rails'
# :require avoids "already initialized constant" warnings
gem 'rmagick', :require => 'RMagick'
gem 'ruby-msg', '~> 1.5.0',  :git => 'git://github.com/mysociety/ruby-msg.git'
gem 'secure_headers'
gem "statistics2", "~> 0.54"
gem 'syslog_protocol'
gem 'thin', '>= 1.6.0'
gem 'vpim'
gem 'will_paginate'
# when 1.2.9 is released by the maintainer, we can stop using this fork:
gem 'xapian-full-alaveteli', '~> 1.2.9.5'
gem 'xml-simple', :require => 'xmlsimple'
gem 'zip'

# Gems related to internationalisation
gem 'fast_gettext'
gem 'gettext_i18n_rails'
gem 'gettext'
gem 'globalize3', :git => 'git://github.com/globalize/globalize.git', :ref => '5fd95f2389dff1'
gem 'locale'
gem 'routing-filter', '>= 0.6.3'
gem 'unicode'
gem 'unidecoder'

group :assets do
  gem 'bootstrap-sass'
  gem 'sass-rails', '~> 5.0.8'
  gem 'compass-rails', '2.0.0'
  gem 'coffee-rails', '~> 4.2.2'
  gem 'uglifier', '>= 1.0.3'
  gem 'therubyracer'
end

group :production do
  gem 'newrelic_rpm'
end

group :test do
  gem 'fakeweb'
  gem 'coveralls', :require => false
  gem 'webrat'
  gem 'nokogiri', '>= 1.15.6'
end

group :test, :development do
  gem 'factory_girl_rails', '~> 2.0', '>= 2.0.0'
  gem 'rspec-rails', '>= 2.14.0'
  gem 'spork-rails', '>= 4.0.0'
end

group :development do
  gem 'capistrano'
  gem 'mailcatcher', '>= 0.9.0'
  gem 'quiet_assets', '>= 1.0.3'
  gem 'rdoc', '>= 6.3.4.1'
end

group :debug do
  gem 'ruby-debug', :platforms => :ruby_18
  gem 'debugger', :platforms => :ruby_19
  gem 'annotate'
end

