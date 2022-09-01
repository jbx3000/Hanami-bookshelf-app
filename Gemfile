source 'https://rubygems.org'

gem 'rake'
gem 'hanami',       '~> 1.3'
gem 'hanami-model', '~> 1.3'

gem 'sqlite3'

group :development do
  # Code reloading
  # See: https://guides.hanamirb.org/projects/code-reloading
  # gem 'shotgun', platforms: :ruby # shotgun doesn't work on Windows, comment it out to fix, see hanami notes
  gem 'hanami-webconsole'
end

group :test, :development do
  gem 'dotenv', '~> 2.4'
end

group :test do
  gem 'rspec'
  gem 'capybara'
end

group :production do
  # gem 'puma'
end
