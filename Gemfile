source 'https://rubygems.org'

# 核心：交給 GitHub Pages 大禮包全權打理（它會自動安裝相容的 jekyll, jekyll-feed 等）
gem 'github-pages', group: :jekyll_plugins

# Minimal Mistakes 主題套件（必須獨立宣告，否則抓不到樣式）
gem 'minimal-mistakes-jekyll'

# 本地端測試（Windows/Mac）需要的微調，放在這裡不會影響 GitHub 線上編譯
group :jekyll_plugins do
  gem 'webrick', '~> 1.8'
end
