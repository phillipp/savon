source 'https://rubygems.org'
gemspec

gem "httpclient", "~> 2.3.4"

gem "simplecov", :require => false
gem "coveralls", :require => false
gem "uuid"

gem "wasabi", github: 'phillipp/wasabi', branch: 'dependency-fix'

platform :rbx do
  gem 'json'
  gem 'racc'
  gem 'rubysl'
  gem 'rubinius-coverage'
end

platform :jruby do
  gem 'json'
end
