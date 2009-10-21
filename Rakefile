begin
  require 'jeweler'
  Jeweler::Tasks.new do |s|
    s.name = "graster"
    s.description = s.summary = "G Raster!"
    s.email = "joshbuddy@gmail.com"
    s.homepage = "http://github.com/joshbuddy/graster"
    s.authors = ["Jedediah Smith", "Joshua Hull"]
    s.files = FileList["[A-Z]*", "{lib,bin}/**/*"]
    s.add_dependency 'RMagick'
    s.rubyforge_project = 'graster'
  end
  Jeweler::GemcutterTasks.new
  Jeweler::RubyforgeTasks.new do |rubyforge|
    rubyforge.doc_task = "rdoc"
    rubyforge.remote_doc_path = ''
  end
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end