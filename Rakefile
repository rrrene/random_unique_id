# encoding: UTF-8
# Copyright © 2013, 2014, Watu

require "bundler/gem_tasks"

require "rake/testtask"
Rake::TestTask.new do |t|
  t.libs << "lib"
  t.test_files = FileList["test/**/*_test.rb"]
end

task :default => :test
