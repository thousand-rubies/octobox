source 'https://rubygems.org'
ruby '3.1.2'

gem 'rails', '7.0.8.4'
gem 'bootstrap', '4.6.1'
gem 'attr_encrypted', git: 'https://github.com/octobox/attr_encrypted.git', branch: 'rails-7'
gem 'jquery-rails', '>= 4.5.1'
gem 'pagy'
gem 'local_time'
gem 'octicons_helper', '>= 17.7.0'
gem 'octokit'
gem 'omniauth-github', '2.0.1'
gem 'puma'
gem 'sassc-rails'
gem 'turbolinks'
gem 'typhoeus'
gem 'faraday_middleware'
gem 'faraday'
gem 'uglifier'
gem 'pg_search'
gem 'jbuilder'
gem 'rake', require: false
gem 'rgb'
gem 'sidekiq'
gem 'sidekiq-unique-jobs'
gem 'sidekiq-scheduler', require: false
gem 'rack-canonical-host'
gem 'sidekiq-status'
gem 'gemoji', require: false
gem 'bootsnap', require: false
gem 'bugsnag'
gem 'jwt'
gem 'oj'
gem 'yard', require: false
gem 'commonmarker'
gem 'pg', '1.4.4'
gem 'rexml'
gem 'omniauth-rails_csrf_protection', '>= 1.0.2'
gem 'psych', '~> 3.3'

group :development, :test do
  gem 'dotenv-rails', '>= 3.0.0'
  gem 'rails-controller-testing'
  gem 'sql_queries_count'
  gem 'active_record_query_trace'
end

group :test do
  gem 'factory_bot'
  gem 'webmock'
  gem 'mocha'
  gem 'minitest'
  gem 'timecop'
end

group :development do
  gem 'web-console', '>= 4.2.1'
  gem 'listen'
  gem 'spring'
  gem 'brakeman'
  gem 'binding_of_caller'
  gem 'better_errors'
end

group :production do
  gem 'skylight', '~> 5.3.4'
  gem 'lograge', '>= 0.13.0'
  gem 'puma_worker_killer'
end
