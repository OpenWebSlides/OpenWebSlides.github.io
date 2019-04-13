# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'middleman', '~> 4.2'
gem 'middleman-autoprefixer', '~> 2.7'
gem 'middleman-deploy', github: 'middleman-contrib/middleman-deploy'
gem 'middleman-livereload'
gem 'rubocop'
gem 'tzinfo-data', platforms: %i[mswin mingw jruby]
gem 'wdm', '~> 0.1', platforms: %i[mswin mingw]
