require 'rake'

task default: [:build]

desc "Build"
task :build do
  puts "Building... "
  system "bundle exec middleman build"
end

desc "Deploy"
task :deploy do
  puts "Deploy to master"
  system "bundle exec middleman deploy > /dev/null 2>&1"
end
