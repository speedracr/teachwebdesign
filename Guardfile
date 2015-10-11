# You can use some options to change guard-haml configuration
# output: 'public'                   set output directory for compiled files
# input: 'src'                       set input directory with haml files
# run_at_start: true                 compile files when guard starts
# notifications: true                send notifictions to Growl/libnotify/Notifu
# haml_options: { ugly: true }    pass options to the Haml engine

guard 'haml', input: 'haml', output: './', run_at_start: true


guard 'livereload' do
  watch(%r{.+\.(html|css|js)$})
end

guard 'sass', :input => 'sass', :output => 'css', :run_at_start => 'true'
