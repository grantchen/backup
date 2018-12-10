source "https://rubygems.org"

gemspec

# Omitted from CI Environment
group :no_ci do
  gem "pry"
  gem "rb-fsevent" # Mac OS X
  gem "rb-inotify" # Linux

  gem "redcarpet"
  gem "yard"
end

gem 'qiniu', github: 'grantchen/qiniu-ruby-sdk', branch: 'develop'