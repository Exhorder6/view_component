# frozen_string_literal: true

source "https://rubygems.org"
gemspec

rails_version = "#{ENV['RAILS_VERSION'] || 'main'}"

gem "capybara", "~> 3", ">= 3.35.0"
gem "rails", rails_version == "main" ? { git: "https://github.com/rails/rails", ref: "main" } : rails_version
