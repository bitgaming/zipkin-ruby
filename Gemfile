source 'https://rubygems.org'

# Specify your gem's dependencies in zipkin-tracer.gemspec
gemspec

platform :ruby do
  gem 'benchmark-ips'
  gem 'rbtrace'
  gem 'byebug'
  gem 'simplecov', require: false
end

platform :jruby do
  gem 'hermann', github: 'reiseburo/hermann', ref: '436ec9b'
end
