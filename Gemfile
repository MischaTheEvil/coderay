source 'https://rubygems.org'

# Specify your gem's dependencies in coderay.gemspec
gemspec

# Add dependencies to develop your gem here.
# Include everything needed to run rake, tests, features, etc.
group :development do
  gem "bundler"
  gem "rake", "~> 10.5"
  gem "RedCloth", RUBY_PLATFORM == 'java' ? "= 4.2.9" : ">= 4.0.3"
  gem "term-ansicolor", "~> 1.3.2"
  gem 'tins', '~> 1.6.0'
  gem "shoulda-context", "= 1.2.1"
  gem "test-unit"
  gem "json", "~> 1.8" if RUBY_VERSION < '1.9'
  gem "rdoc", "~> 4.2.2"
end
