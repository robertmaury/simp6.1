# ------------------------------------------------------------------------------
# NOTE: SIMP Puppet rake tasks support ruby 2.1.9
# ------------------------------------------------------------------------------
gem_sources = ENV.fetch('GEM_SERVERS','https://rubygems.org').split(/[, ]+/)

gem_sources.each { |gem_source| source gem_source }

group :test do
  gem 'rake'
  gem 'rspec'
  gem 'metadata-json-lint'
  # Ruby code coverage
  gem 'simplecov'
  gem 'simp-rake-helpers', ENV.fetch('SIMP_RAKE_HELPERS_VERSION', ['>= 4.0.0', '<= 6.0.0'])
  gem 'travis'
  gem 'travis-lint'
  gem 'travish'
  gem 'pry'
  gem 'pry-doc'
end
