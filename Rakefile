
begin
  require 'bones'
rescue LoadError
  abort '### Please install the "bones" gem ###'
end

task :default => 'test:run'
task 'gem:release' => 'test:run'

Bones {
  name     'pivotcli'
  authors  'Julius F'
  email    'baldrailers@gmail.com'
  url      'http://julius.weekendhack.in'
}

