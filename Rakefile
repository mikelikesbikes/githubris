require 'bundler/gem_tasks'
require 'rspec/core/rake_task'
require 'cucumber/rake/task'

RSpec::Core::RakeTask.new :spec do |t|
  t.rspec_opts = '--color --format=documentation'
end

Cucumber::Rake::Task.new :features

task :default => :spec
