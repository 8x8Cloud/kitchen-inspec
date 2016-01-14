# -*- encoding: utf-8 -*-
source 'https://rubygems.org'
gemspec

group :guard do
  gem 'guard-rspec',    :require => nil
  gem 'guard-rubocop',  :require => nil
end

group :test do
  gem 'codeclimate-test-reporter', :require => nil
end

group :tools do
  gem 'github_changelog_generator', '~> 1'
end

group :integration do
  gem 'berkshelf', '~> 4.0'
  gem 'test-kitchen', '~> 1.4', :require => nil
  gem 'kitchen-dokken'
  gem 'kitchen-inspec', path: '.'
end
