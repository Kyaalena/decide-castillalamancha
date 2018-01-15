# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gem "decidim", "0.8.2"

gem "decidim-admin", path: "decidim-admin"
gem "decidim-core", path: "decidim-core"
gem "decidim-debates", path: "decidim-debates"

# Uncomment the following line if you want to use decidim-assemblies plugin
# gem "decidim-assemblies", "0.9.0.pre"

gem "puma", "~> 3.0"
gem "uglifier", ">= 1.3.0"

gem "faker", "~> 1.8.4"

group :development, :test do
  gem "byebug", platform: :mri

  gem "decidim-dev", "0.8.2"
end

group :development do
  gem "letter_opener_web", "~> 1.3.0"
  gem "listen", "~> 3.1.0"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console"

  # deploy
  gem "capistrano", "3.8.0", require: false
  gem "capistrano-bundler", "~> 1.2", require: false
  gem "capistrano-passenger"
  gem "capistrano-rails", "1.1.8", require: false
  gem "capistrano-rbenv"
  gem "capistrano3-delayed-job", "~> 1.0"
end
