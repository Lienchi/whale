source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.5'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem "devise"
gem 'jquery-rails'
gem 'ffaker'
gem 'bootstrap-sass', '~> 3.3.7'
gem 'annotate'
gem 'carrierwave'
gem 'roo', '~> 2.7.0'
gem "font-awesome-rails"
gem 'bootstrap-modal-rails'


group :production do
  #gem 'pg', '~> 0.11'
  gem 'mysql2', '~> 0.3.18'
end

group :development, :test do
  gem 'capistrano-rails'
  gem 'capistrano-passenger'

  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'shoulda-matchers', '~> 3.1'
  gem 'rails-controller-testing'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
