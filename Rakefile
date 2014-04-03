# -*- ruby -*-

require 'rubygems'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "karthik-ruby-gmail"
    gem.summary = %Q{A Rubyesque interface to Gmail, with all the tools you'll need.}
    gem.description = %Q{A Rubyesque interface to Gmail, with all the tools you'll need. Search, read and send multipart emails; archive, mark as read/unread, delete emails; and manage labels. Fork of 
    the original ruby-gmail gem (https://github.com/dcparker/ruby-gmail). Added search by subject, limit number of email search results.}
    gem.email = "karthik.mallavarapu@gmail.com"
    gem.homepage = "https://github.com/karthik-mallavarapu/ruby-gmail"
    gem.authors = ["Karthik Mallavarapu"]
    gem.authors = ["Karthik Mallavarapu"]
    gem.add_dependency('shared-mime-info', '>= 0')
    gem.add_dependency('mail', '>= 2.2.1')
    gem.add_dependency('mime', '>= 0.1')
    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end

task :default do
  sh "find test -type f -name '*rb' -exec testrb -I lib:test {} +"
end