require 'bundler/setup'
require 'bundler/gem_tasks'
require 'cucumber/rake/task'

Cucumber::Rake::Task.new do |t|
  t.fork = true
  t.cucumber_opts = ['--format', (ENV['CUCUMBER_FORMAT'] || 'progress')]
end

desc 'Default: run cucumber features'
task :default => [:cucumber]