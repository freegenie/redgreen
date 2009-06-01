require 'rake'

$LOAD_PATH.unshift('lib')
 
begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "redgreen"
    gem.summary = "freegenie-redgreen colourises windows console output for tests."
    gem.email = "freegenie@gmail.com"
    gem.homepage = "http://github.com/freegenie/redgreen"
    gem.description = "freegenie-redgreen colourises windows console output for tests.  This version works with ZenTest 4.0.0, autotest, snarl, XP and Vista.  Please see the README file for setup or issues with Snarl."
    gem.authors = ["Pat Eyler", "Chris Wanstrath", "Luke Pearce"]
  end
rescue LoadError
  puts "Jeweler, or one of its dependencies, is not available. Install it with: gem install jeweler"
end
 
require 'rake/rdoctask'
Rake::RDocTask.new do |rdoc|
  rdoc.rdoc_dir = 'rdoc'
  rdoc.title = 'freegenie-redgreen'
  rdoc.rdoc_files.include('README.markdown')
  rdoc.rdoc_files.include('lib/**/*.rb')
end
