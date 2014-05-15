desc "help msg"
task :help do
  system('rake -T')
end

desc "deploy"
task :deploy do
  system("rsync -avz _output/* tufu:/var/www/kidslib.fltrp.com/asset/game/")
  puts "\n\n同步到服务器了"
end
task :default => [:help]
