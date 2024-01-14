source "https://rubygems.org"

ruby "3.3.0"

# Use main development branch of Rails
gem "rails", github: "rails/rails", branch: "main"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.5"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", ">= 6.4.2"

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Use Tailwind CSS [https://github.com/rails/tailwindcss-rails]
gem "tailwindcss-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# REDIS AND ASSOCIATED SERVICES
# gem "sidekiq"
# gem "sidekiq-scheduler"

# gem "redis", ">= 5.0.8"
# gem "redis-namespace"
# gem "redis-rails"
# gem "redis-rack-cache"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# IMAGE MANAGEMENT
# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"
# gem "mini_magick"
# gem 'rmagick', '~> 5.3.0'

# AUTHENTICATION
# gem "devise", "~>4.9"

# ADMINISTRATION
# gem "avo", "~> 3.1"

# HTTP REQUESTS
# gem "httparty"

# PDF
# gem "prawn", require: false

# FRONT END
# gem "chartkick"
# gem "groupdate"
# gem "view_component"
# gem "pagy"
# gem "font-awesome-rails", "~> 4.7"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ]
  gem "database_cleaner", "~> 2.0"
  gem "dotenv-rails"
  gem "byebug"
  gem "pry-byebug"
  # Static analysis for security vulnerabilities [https://brakemanscanner.org/]
  gem "brakeman", require: false

  # Omakase Ruby styling [https://github.com/rails/rubocop-rails-omakase/]
  gem "rubocop-rails-omakase", require: false
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"
  gem "pry", "~> 0.14.2"
  gem "pry-remote"
  gem "pry-nav"
  gem "annotate"
  gem "bullet"
  gem "stackprof"
  gem "benchmark"
  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem 'rspec', '~> 3.12'
end
