require 'rubygems'
require 'rake'
require 'rake/clean'
require 'rake/testtask'
require 'rake/packagetask'
require 'rake/gempackagetask'
require 'rake/rdoctask'
require 'fileutils'
include FileUtils
require File.join(File.dirname(__FILE__), 'lib', 'right_http_connection')

begin
    require 'jeweler2'
    Jeweler::Tasks.new do |gemspec|
        gemspec.name = "http_connection"
        gemspec.summary = "HTTP helper library"
        gemspec.email = "travis@appoxy.com"
        gemspec.homepage = "http://github.com/appoxy/http_connection/"
        gemspec.description = "HTTP helper library"
        gemspec.authors = ["Travis Reeder", "RightScale"]
        gemspec.files = FileList['lib/**/*.rb']
    end
    Jeweler::GemcutterTasks.new
rescue LoadError
    puts "Jeweler not available. Install it with: sudo gem install jeweler2"
end

