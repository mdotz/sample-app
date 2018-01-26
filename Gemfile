source 'https://rubygems.org'

gem 'rails',          '5.1.4'
=begin
for windows problems with bcrypt
  1. Change to the gem directory 
  \Ruby22-x64\lib\ruby\gems\2.x.x\gems\bcrypt-3.1.10-x64-mingw32\ext\mri
  2. Run ruby extconf.rb
  3. Run make
  4. Run make install
=end
gem 'bcrypt',                   '3.1.11'
gem 'faker',                    '1.7.3'
gem 'will_paginate',            '3.1.6'
gem 'bootstrap-will_paginate',  '1.0.0'
gem 'bootstrap-sass',           '3.3.7'
gem 'puma',                     '3.9.1'
gem 'sass-rails',               '5.0.6'
gem 'uglifier',                 '3.2.0'
gem 'coffee-rails',             '4.2.2'
gem 'jquery-rails',             '4.3.1'
gem 'turbolinks',               '5.0.1'
gem 'jbuilder',                 '2.7.0'

group :development, :test do
  gem 'sqlite3', '1.3.13'
  gem 'byebug',  '9.0.6', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rails-controller-testing'
end

group :development do
  gem 'web-console',        '3.5.1'
  gem 'minitest-reporters', '1.1.14'
  gem 'guard',              '2.13.0'
  gem 'guard-minitest',     '2.4.4'
end

group :production do
  gem 'pg', '0.18.4'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
