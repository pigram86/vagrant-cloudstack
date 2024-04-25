source 'https://rubygems.org'

gemspec

group :development do
  # We depend on Vagrant for development, but we don't add it as a
  # gem dependency because we expect to be installed within the
  # Vagrant environment itself using `vagrant plugin`.
  gem 'vagrant', git: 'https://github.com/mitchellh/vagrant.git', tag: 'v2.0.3'
  gem 'coveralls', '>= 0.7.3', require: false
  gem 'simplecov', require: false
  gem 'rspec-core'
  gem 'rspec-expectations'
  gem 'rspec-its'
  gem 'rspec-mocks'
end

group :plugins do
  gemspec
end
