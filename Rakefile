ENV["PLAYLISTER_ENV"] ||= "development"

require_relative './config/environment'
require 'sinatra/activerecord/rake'

# Type `rake -T` on your command line to see the available rake tasks.
desc "Allows for a live IRB session that reloads"
task :console do
  Pry.start
end