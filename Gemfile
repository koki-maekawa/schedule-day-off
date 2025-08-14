source "https://rubygems.org"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 8.0.2"
# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"
# Bundle and transpile JavaScript [https://github.com/rails/jsbundling-rails]
gem "jsbundling-rails"
# CSS Bundler
gem "cssbundling-rails"
# Use Sass to process CSS
gem "sassc-rails"
# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"
# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 6.0"
# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"
# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# 日本語化
gem "rails-i18n"
gem "enum_help"

# ログイン機能
gem "sorcery"

# 検索機能
gem "ransack"

# ページネーション
gem "kaminari"

# 画像アップロード
gem "carrierwave"
gem "mini_magick"

# メタタグの設定
gem "meta-tags"

# 管理画面
gem "rails_admin", "~> 3.0"

# 権限管理
gem "cancancan"

# 環境別定数管理
gem "config"

# 環境変数
gem "dotenv-rails"

# Googleログイン
gem "googleauth"

group :production do
  # Amazon S3を使用するためのパッケージ
  gem "fog-aws"
end

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  # Static analysis for security vulnerabilities [https://brakemanscanner.org/]
  gem "brakeman", require: false

  # Omakase Ruby styling [https://github.com/rails/rubocop-rails-omakase/]
  gem "rubocop-rails-omakase", require: false
  gem "rubocop-rspec", require: false

  # erb styling
  gem "erb_lint", require: false
  gem "htmlbeautifier", require: false

  # test
  gem "rspec-rails"
  gem "factory_bot_rails"

  # N+1
  gem "bullet"
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # mail check
  gem "letter_opener_web"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "capybara-playwright-driver"
  gem "faker"
end
