# Load DSL and Setup Up Stages
require 'capistrano/setup'
require 'capistrano/deploy'
require 'capistrano/rvm'
require 'capistrano/bundler'
require 'capistrano/rails'
require 'capistrano/rails/assets'
require 'capistrano/rails/migrations'
require 'capistrano/sidekiq'
require 'capistrano/puma'
require 'capistrano/puma/nginx'
#require "capistrano/scm/git"
#install_plugin Capistrano::SCM::Git
# install_plugin Capistrano::Puma

# Loads custom tasks from `lib/capistrano/tasks' if you have any defined.
Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }
