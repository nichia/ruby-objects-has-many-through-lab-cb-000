require_relative './lib/artist'
require_relative './lib/genre'
require_relative './lib/song'
require_relative './lib/appointment'
require_relative './lib/doctor'
require_relative './lib/patient'

require 'pry'
require 'rake'

puts "Welcome to Objects has many through....."

def reload!
  load './lib/artist.rb'
  load './lib/genre.rb'
  load './lib/song.rb'
  load './lib/appointment.rb'
  load './lib/doctor.rb'
  load './lib/patient.rb'
end

desc "A Console"
task :console do
  Pry.start
end
