desc "Deploy to server"
task :deploy do
exclude = ""
  system "stasis"
  # exclude = "--exclude-from '#{File.expand_path('./rsync-exclude')}'"
  system "jekyll && rsync -azv --delete public titans:~/timuruski.com/www"
end
