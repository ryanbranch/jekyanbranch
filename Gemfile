# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# gem "rails"

# END AUTO GENERATED PORTION OF GEMFILE
# BEGIN MANUALLY WRITTEN PORTION OF GEMFILE
# Created by Ryan Branch on 2020/07/08

# ADDITIONS BASED ON NOTES FROM JEKYLL WINDOWS INSTALLATION DOCUMENTATION
#   (https://jekyllrb.com/docs/installation/windows/)
# 1. Time-Zone Management
#   A. Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
#   B. TZInfo 2.0 incompatibility
#     i. Version 2.0 of the TZInfo library has introduced a change in how timezone offsets are calculated. 
#     ii. This will result in incorrect date and time for your posts when the site is built with Jekyll 3.x on Windows. 
#     iii. We therefore recommend that you lock the Timezone library to version 1.2 and above
gem 'tzinfo', '~> 1.2'
# 2. Auto Regeneration
#   A. Jekyll uses the listen gem to watch for changes when the --watch switch is specified during a build or serve.
#   B. While listen has built-in support for UNIX systems, it may require an extra gem for compatibility with Windows.
gem 'wdm', '~> 0.1.1', :install_if => Gem.win_platform?
#   C. This additional line (below) was added verbatim as recommended by CMD output upon running "jekyll serve",
#      although it still outputs the same request for this line to be added
gem 'wdm', '>= 0.1.0' if Gem.win_platform?

# ADDITIONS BASED ON JEKYLL "Step by Step Tutorial"
#   (https://jekyllrb.com/docs/step-by-step/01-setup/)
gem "jekyll"

# ADDITIONS BASED ON JEKYLL "GitHub Pages" DOCUMENTATION
#   (https://jekyllrb.com/docs/github-pages/)
gem "github-pages", group: :jekyll_plugins