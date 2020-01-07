source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.7', '>= 5.0.7.2'
# Use mysql as the database for Active Record
gem 'mysql2', '>= 0.3.18', '< 0.6.0'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
# gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
group :development, :test do
  gem 'capistrano'
  gem 'capistrano-rbenv'
  gem 'capistrano-bundler'
  gem 'capistrano-rails'
  gem 'capistrano3-unicorn'
end
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'font-awesome-sass'
gem "haml-rails", ">= 1.0", '<= 2.0.1'
gem 'carrierwave'
gem 'mini_magick'
gem 'devise'
gem 'fog-aws'

  group :production do
  gem 'unicorn', '5.4.1'
end

# GEM
#   remote: https://rubygems.org/
#   specs:
#     actioncable (5.0.7.2)
#       actionpack (= 5.0.7.2)
#       nio4r (>= 1.2, < 3.0)
#       websocket-driver (~> 0.6.1)
#     actionmailer (5.0.7.2)
#       actionpack (= 5.0.7.2)
#       actionview (= 5.0.7.2)
#       activejob (= 5.0.7.2)
#       mail (~> 2.5, >= 2.5.4)
#       rails-dom-testing (~> 2.0)
#     actionpack (5.0.7.2)
#       actionview (= 5.0.7.2)
#       activesupport (= 5.0.7.2)
#       rack (~> 2.0)
#       rack-test (~> 0.6.3)
#       rails-dom-testing (~> 2.0)
#       rails-html-sanitizer (~> 1.0, >= 1.0.2)
#     actionview (5.0.7.2)
#       activesupport (= 5.0.7.2)
#       builder (~> 3.1)
#       erubis (~> 2.7.0)
#       rails-dom-testing (~> 2.0)
#       rails-html-sanitizer (~> 1.0, >= 1.0.3)
#     activejob (5.0.7.2)
#       activesupport (= 5.0.7.2)
#       globalid (>= 0.3.6)
#     activemodel (5.0.7.2)
#       activesupport (= 5.0.7.2)
#     activerecord (5.0.7.2)
#       activemodel (= 5.0.7.2)
#       activesupport (= 5.0.7.2)
#       arel (~> 7.0)
#     activesupport (5.0.7.2)
#       concurrent-ruby (~> 1.0, >= 1.0.2)
#       i18n (>= 0.7, < 2)
#       minitest (~> 5.1)
#       tzinfo (~> 1.1)
#     addressable (2.7.0)
#       public_suffix (>= 2.0.2, < 5.0)
#     airbrussh (1.4.0)
#       sshkit (>= 1.6.1, != 1.7.0)
#     arel (7.1.4)
#     bcrypt (3.1.13)
#     bindex (0.8.1)
#     builder (3.2.4)
#     byebug (11.0.1)
#     capistrano (3.11.2)
#       airbrussh (>= 1.0.0)
#       i18n
#       rake (>= 10.0.0)
#       sshkit (>= 1.9.0)
#     capistrano-bundler (1.6.0)
#       capistrano (~> 3.1)
#     capistrano-rails (1.4.0)
#       capistrano (~> 3.1)
#       capistrano-bundler (~> 1.1)
#     capistrano-rbenv (2.1.4)
#       capistrano (~> 3.1)
#       sshkit (~> 1.3)
#     capistrano3-unicorn (0.2.1)
#       capistrano (~> 3.1, >= 3.1.0)
#     carrierwave (2.0.2)
#       activemodel (>= 5.0.0)
#       activesupport (>= 5.0.0)
#       addressable (~> 2.6)
#       image_processing (~> 1.1)
#       mimemagic (>= 0.3.0)
#       mini_mime (>= 0.1.3)
#     coffee-rails (4.2.2)
#       coffee-script (>= 2.2.0)
#       railties (>= 4.0.0)
#     coffee-script (2.4.1)
#       coffee-script-source
#       execjs
#     coffee-script-source (1.12.2)
#     concurrent-ruby (1.1.5)
#     crass (1.0.5)
#     devise (4.7.1)
#       bcrypt (~> 3.0)
#       orm_adapter (~> 0.1)
#       railties (>= 4.1.0)
#       responders
#       warden (~> 1.2.3)
#     erubis (2.7.0)
#     excon (0.69.1)
#     execjs (2.7.0)
#     ffi (1.11.3)
#     fog-aws (3.5.2)
#       fog-core (~> 2.1)
#       fog-json (~> 1.1)
#       fog-xml (~> 0.1)
#       ipaddress (~> 0.8)
#     fog-core (2.1.2)
#       builder
#       excon (~> 0.58)
#       formatador (~> 0.2)
#       mime-types
#     fog-json (1.2.0)
#       fog-core
#       multi_json (~> 1.10)
#     fog-xml (0.1.3)
#       fog-core
#       nokogiri (>= 1.5.11, < 2.0.0)
#     font-awesome-sass (5.11.2)
#       sassc (>= 1.11)
#     formatador (0.2.5)
#     globalid (0.4.2)
#       activesupport (>= 4.2.0)
#     haml (5.1.2)
#       temple (>= 0.8.0)
#       tilt
#     haml-rails (1.0.0)
#       actionpack (>= 4.0.1)
#       activesupport (>= 4.0.1)
#       haml (>= 4.0.6, < 6.0)
#       html2haml (>= 1.0.1)
#       railties (>= 4.0.1)
#     html2haml (2.2.0)
#       erubis (~> 2.7.0)
#       haml (>= 4.0, < 6)
#       nokogiri (>= 1.6.0)
#       ruby_parser (~> 3.5)
#     i18n (1.7.0)
#       concurrent-ruby (~> 1.0)
#     image_processing (1.9.3)
#       mini_magick (>= 4.9.5, < 5)
#       ruby-vips (>= 2.0.13, < 3)
#     ipaddress (0.8.3)
#     jbuilder (2.9.1)
#       activesupport (>= 4.2.0)
#     jquery-rails (4.3.5)
#       rails-dom-testing (>= 1, < 3)
#       railties (>= 4.2.0)
#       thor (>= 0.14, < 2.0)
#     kgio (2.11.2)
#     listen (3.0.8)
#       rb-fsevent (~> 0.9, >= 0.9.4)
#       rb-inotify (~> 0.9, >= 0.9.7)
#     loofah (2.4.0)
#       crass (~> 1.0.2)
#       nokogiri (>= 1.5.9)
#     mail (2.7.1)
#       mini_mime (>= 0.1.1)
#     method_source (0.9.2)
#     mime-types (3.3)
#       mime-types-data (~> 3.2015)
#     mime-types-data (3.2019.1009)
#     mimemagic (0.3.3)
#     mini_magick (4.9.5)
#     mini_mime (1.0.2)
#     mini_portile2 (2.4.0)
#     minitest (5.13.0)
#     multi_json (1.14.1)
#     mysql2 (0.5.3)
#     net-scp (2.0.0)
#       net-ssh (>= 2.6.5, < 6.0.0)
#     net-ssh (5.2.0)
#     nio4r (2.5.2)
#     nokogiri (1.10.7)
#       mini_portile2 (~> 2.4.0)
#     orm_adapter (0.5.0)
#     public_suffix (4.0.1)
#     puma (3.12.2)
#     rack (2.0.8)
#     rack-test (0.6.3)
#       rack (>= 1.0)
#     rails (5.0.7.2)
#       actioncable (= 5.0.7.2)
#       actionmailer (= 5.0.7.2)
#       actionpack (= 5.0.7.2)
#       actionview (= 5.0.7.2)
#       activejob (= 5.0.7.2)
#       activemodel (= 5.0.7.2)
#       activerecord (= 5.0.7.2)
#       activesupport (= 5.0.7.2)
#       bundler (>= 1.3.0)
#       railties (= 5.0.7.2)
#       sprockets-rails (>= 2.0.0)
#     rails-dom-testing (2.0.3)
#       activesupport (>= 4.2.0)
#       nokogiri (>= 1.6)
#     rails-html-sanitizer (1.3.0)
#       loofah (~> 2.3)
#     railties (5.0.7.2)
#       actionpack (= 5.0.7.2)
#       activesupport (= 5.0.7.2)
#       method_source
#       rake (>= 0.8.7)
#       thor (>= 0.18.1, < 2.0)
#     raindrops (0.19.0)
#     rake (13.0.1)
#     rb-fsevent (0.10.3)
#     rb-inotify (0.10.1)
#       ffi (~> 1.0)
#     responders (3.0.0)
#       actionpack (>= 5.0)
#       railties (>= 5.0)
#     ruby-vips (2.0.16)
#       ffi (~> 1.9)
#     ruby_parser (3.14.1)
#       sexp_processor (~> 4.9)
#     sass (3.7.4)
#       sass-listen (~> 4.0.0)
#     sass-listen (4.0.0)
#       rb-fsevent (~> 0.9, >= 0.9.4)
#       rb-inotify (~> 0.9, >= 0.9.7)
#     sass-rails (5.0.7)
#       railties (>= 4.0.0, < 6)
#       sass (~> 3.1)
#       sprockets (>= 2.8, < 4.0)
#       sprockets-rails (>= 2.0, < 4.0)
#       tilt (>= 1.1, < 3)
#     sassc (2.2.1)
#       ffi (~> 1.9)
#     sexp_processor (4.13.0)
#     spring (2.1.0)
#     spring-watcher-listen (2.0.1)
#       listen (>= 2.7, < 4.0)
#       spring (>= 1.2, < 3.0)
#     sprockets (3.7.2)
#       concurrent-ruby (~> 1.0)
#       rack (> 1, < 3)
#     sprockets-rails (3.2.1)
#       actionpack (>= 4.0)
#       activesupport (>= 4.0)
#       sprockets (>= 3.0.0)
#     sshkit (1.20.0)
#       net-scp (>= 1.1.2)
#       net-ssh (>= 2.8.0)
#     temple (0.8.2)
#     thor (1.0.1)
#     thread_safe (0.3.6)
#     tilt (2.0.10)
#     tzinfo (1.2.6)
#       thread_safe (~> 0.1)
#     uglifier (4.2.0)
#       execjs (>= 0.3.0, < 3)
#     unicorn (5.4.1)
#       kgio (~> 2.6)
#       raindrops (~> 0.7)
#     warden (1.2.8)
#       rack (>= 2.0.6)
#     web-console (3.7.0)
#       actionview (>= 5.0)
#       activemodel (>= 5.0)
#       bindex (>= 0.4.0)
#       railties (>= 5.0)
#     websocket-driver (0.6.5)
#       websocket-extensions (>= 0.1.0)
#     websocket-extensions (0.1.4)

# PLATFORMS
#   ruby

# DEPENDENCIES
#   byebug
#   capistrano
#   capistrano-bundler
#   capistrano-rails
#   capistrano-rbenv
#   capistrano3-unicorn
#   carrierwave
#   coffee-rails (~> 4.2)
#   devise
#   fog-aws
#   font-awesome-sass
#   haml-rails (>= 1.0, <= 2.0.1)
#   jbuilder (~> 2.5)
#   jquery-rails
#   listen (~> 3.0.5)
#   mini_magick
#   mysql2 (>= 0.3.18, < 0.6.0)
#   puma (~> 3.0)
#   rails (~> 5.0.7, >= 5.0.7.2)
#   sass-rails (~> 5.0)
#   spring
#   spring-watcher-listen (~> 2.0.0)
#   tzinfo-data
#   uglifier (>= 1.3.0)
#   unicorn (= 5.4.1)
#   web-console (>= 3.3.0)

# BUNDLED WITH
#    2.0.2
