# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "rails", "~> 5.2"
gem "omniauth", "~> 1.3"
gem "oauth2"
gem "omniauth-oauth2"
gem "rdoc"

gem "activemodel-serializers-xml", git: "git@github.com:rails/activemodel-serializers-xml.git"

gem "rails-controller-testing"

gem "responders", "~> 2.4"

gem 'bcrypt', git: 'git@github.com:pooza/bcrypt-ruby.git'

group :test do
  gem "omniauth-facebook"
  gem "omniauth-openid"
  gem "timecop"
  gem "webrat", "0.7.3", require: false
  gem "mocha", "~> 1.1", require: false
end

platforms :jruby do
  gem "activerecord-jdbc-adapter"
  gem "activerecord-jdbcsqlite3-adapter"
  gem "jruby-openssl"
end

platforms :ruby do
  gem "sqlite3", "~> 1.3.6"
end

# TODO:
# group :mongoid do
#   gem "mongoid", "~> 4.0.0"
# end
