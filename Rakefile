
begin
  require 'bones'
rescue LoadError
  abort '### Please install the "bones" gem ###'
end

task :default => 'test:run'
task 'gem:release' => 'test:run'

Bones {
  name     'gusevfe_utils'
  authors  'Fedor Gusev'
  email    'gusevfe@gmail.com'
  url      'http://github.com/gusevfe/gusevfe_utils'
}

