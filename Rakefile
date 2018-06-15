require "bundler/gem_tasks"
require "rspec/core/rake_task"

RSpec::Core::RakeTask.new(:spec)

task :console do
  exec "pry -r gem_checker -I ./lib"
end

task :default => :spec
