begin
  require 'bundler/setup'
rescue LoadError
  puts 'You must `gem install bundler` and `bundle install` to run rake tasks'
end
Dir.glob('lib/tasks/*.rake').each { |r| load r}
