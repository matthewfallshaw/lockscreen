task :default => :build

desc "Build lockscreen"
task :build do
  sh "clang -framework Foundation lockscreen.m -o lockscreen"
  log "lockscreen built."
end
