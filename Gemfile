# frozen_string_literal: true

source "https://rubygems.org"

# Blog engine
gem "jekyll", "~> 4.3.2"
gem "jekyll-theme-chirpy", "~> 7.0", ">= 7.0.1"

# Webrick es necesario desde Ruby 3.0+
gem "webrick", "~> 1.7"

# Para silenciar la advertencia sobre base64 en Ruby >= 3.4
gem "base64", "~> 0.1.1"

# Validación de HTML (opcional, solo en tests o CI)
group :test do
  gem "html-proofer", "~> 5.0"
end

# Compatibilidad con Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", platforms: [:mingw, :x64_mingw, :mswin]
