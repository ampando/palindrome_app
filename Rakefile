require 'rake/testtask'

Rake::TestTask.new do |t|
  t.pattern = 'test/*_test.rb'
  t.warning = false
end

task :default => [:test]

def test_index
  get '/'
  assert last_response.ok?
end