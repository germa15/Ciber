source "https://rubygems.org"

# Este Gemfile es mínimo para usar con GitHub Actions y remote_theme.
# GitHub Actions gestiona Jekyll, el tema (Chirpy) y sus dependencias.
# No necesitas listar 'jekyll', 'minima', 'jekyll-theme-chirpy' o 'github-pages' aquí.

group :jekyll_plugins do
  # Si usas plugins adicionales que NO son parte del tema o de Jekyll por defecto, ponlos aquí.
  gem "jekyll-feed" # Ejemplo de un plugin adicional
  gem "jekyll-seo-tag" # Ejemplo de otro plugin adicional
end

# Se mantienen las dependencias específicas de plataforma (aunque GitHub Actions usa Linux)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
