require 'open3'
require 'erb'

# Minimal build script to avoid eventmachine dependency
task :serve do
  puts "Building Jekyll site..."
  # Just output a message for now - Jekyll build will use available gems
  system("cd #{Dir.pwd} && jekyll serve --no-watch --force_polling")
end

task :build do
  puts "Building static site..."
  system("cd #{Dir.pwd} && jekyll build")
end
