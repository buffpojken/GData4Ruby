begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|

    gemspec.name = "buffpojken-gdata4ruby"
    gemspec.summary = %Q{A full featured wrapper for interacting with the base Google Data API}
    gemspec.email = ["daniel@sykewarrior.com"]
    gemspec.homepage = "https://github.com/buffpojken/GData4Ruby"
    gemspec.authors = ["buffpojken"]
    gemspec.add_dependency 'oauth', '>= 0.4.4'
    gemspec.files = FileList["README", "CHANGELOG", "lib/gdata4ruby.rb", "lib/gdata4ruby/base.rb", "lib/gdata4ruby/gdata_object.rb", "lib/gdata4ruby/request.rb", "lib/gdata4ruby/service.rb", "lib/gdata4ruby/oauth_service.rb", "lib/gdata4ruby/acl/access_rule.rb", "lib/gdata4ruby/utils/utils.rb"]
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: gem install jeweler"
end