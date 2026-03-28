source "https://mirrors.ustc.edu.cn/rubygems/" # 国内镜像，加速下载

# 注释掉老旧的 github-pages（所有报错的根源）
# gem "github-pages", group: :jekyll_plugins

# 使用原生 Jekyll 4（完美适配你的 Ruby 3.2）
gem "jekyll", "~> 4.3"
gem "tzinfo-data" # 必需时区依赖

# Windows 适配（保留你原有的配置）
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# 插件组（保留你原有的插件，补齐所有缺失依赖）
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  # 注释掉 hawkins（不兼容 Jekyll 4，用官方 --livereload 替代）
  # gem "hawkins"

  # 补齐项目必需的所有插件（彻底解决缺失依赖报错）
  gem "jekyll-paginate"
  gem "jekyll-gist"
  gem "jekyll-seo-tag"
  gem "jekyll-redirect-from"
  gem "jekyll-relative-links"
end