require ::File.expand_path('../config/environment', __FILE__)

desc 'Start Development Server Locally'
task "s" do
  exec "rackup config.ru --port 9393"
end
task "i" do
  exec "ruby csv/csv_import.rb"
end
