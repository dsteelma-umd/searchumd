# frozen_string_literal: true

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.0'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
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
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# dotenv - For storing production configuration parameters
gem 'dotenv-rails', '~> 2.2.1'

gem 'quick_search-core', git: 'https://github.com/NCSU-Libraries/quick_search.git', tag: '0.2.0'

# -Inserted by QuickSearch-

# QuickSearch searchers
#
# If you want to use different searchers, remove/replace these and be sure to remove them from
# your config/quick_search_config.yml file as well as references to them in your theme's search
# results page template

gem 'quick_search-wikipedia_searcher'
gem 'quick_search-open_library_searcher'
gem 'quick_search-arxiv_searcher'
gem 'quick_search-placeholder_searcher'

gem 'quick_search-world_cat_searcher',
    git: 'https://github.com/umd-lib/quick_search-world_cat_searcher.git', branch: 'develop'
gem 'quick_search-world_cat_knowledge_base_searcher',
    git: 'https://github.com/umd-lib/quick_search-world_cat_knowledge_base_searcher.git', branch: 'develop'
gem 'quick_search-lib_answers_searcher',
    git: 'https://github.com/umd-lib/quick_search-lib_answers_searcher.git', branch: 'develop'
gem 'quick_search-lib_guides_searcher',
    git: 'https://github.com/umd-lib/quick_search-lib_guides_searcher.git', branch: 'develop'
gem 'quick_search-database_finder_searcher',
    git: 'https://github.com/umd-lib/quick_search-database_finder_searcher.git', branch: 'develop'
gem 'quick_search-library_website_searcher',
    git: 'https://github.com/umd-lib/quick_search-library_website_searcher.git', branch: 'develop'
gem 'quick_search-swiftype_searcher',
    git: 'https://github.com/umd-lib/quick_search-swiftype_searcher.git', branch: 'develop'
gem 'quick_search-world_cat_discovery_api_searcher',
    git: 'https://github.com/umd-lib/quick_search-world_cat_discovery_api_searcher.git', branch: 'develop'

# Dependencies for the quick_search-world_cat_discovery_api_searcher initialization script
gem 'oclc-auth', '>=1.0.0'
gem 'worldcat-discovery', '>=1.2.0.1'

# -END Inserted by QuickSearch-

# -Inserted by QuickSearch-

# QuickSearch theme
#
# Remove the following if you want to use a different theme

gem 'quick_search-umd_theme',
    git: 'https://github.com/umd-lib/quick_search-umd_theme.git', branch: 'develop'

# END -Inserted by QuickSearch-

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :test do
  gem 'simplecov', '~> 0.15.1', require: false
  gem 'simplecov-rcov', '~> 0.2.3', require: false
  gem 'minitest-reporters', '~> 1.1.19'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  # Code analysis tools
  gem 'rubocop', '= 0.52.1', require: false
  gem 'rubocop-checkstyle_formatter', '~> 0.4.0', require: false
end

group :production do
  gem 'pg', '~> 0.18.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
