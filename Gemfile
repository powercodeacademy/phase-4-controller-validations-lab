source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Ruby 3.3+ and 3.5+ compatibility: Add future-compatibility gems for stdlib removals
gem 'bigdecimal'
gem 'fiddle'
gem 'logger'
gem 'mutex_m'
gem 'ostruct'

# Rails 7.1 and Ruby 3.3.5 compatibility
gem 'nio4r', '~> 2.7'
gem 'puma', '~> 6.4'
gem 'rails', '~> 7.1.3'
gem 'sqlite3', '~> 1.6.0'
# gem 'bcrypt', '~> 3.1.7'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'rspec-rails', '~> 6.0'
  gem 'webrick'
end

group :development do
  gem 'listen', '~> 3.3'
  # Add rubocop for code quality
  gem 'rubocop', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :test do
  gem 'rspec-json_expectations'
  gem 'shoulda-matchers', '~> 4.0'
end
