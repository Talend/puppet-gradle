source 'https://rubygems.org'
puppetversion = ENV.key?('PUPPET_VERSION') ? "#{ENV['PUPPET_VERSION']}" : ['~> 3.8.0']

gem 'puppet', puppetversion

group :test do
  gem 'rake'
  gem 'rspec'
  gem 'rspec-puppet'
  gem 'puppetlabs_spec_helper'
  gem 'puppet-lint'
end
