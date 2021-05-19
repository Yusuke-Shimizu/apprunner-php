require 'rake'

desc "build"
task :build do
sh 'docker build -t hiramasa:0.1 .'
end

desc "ps"
task :ps do
sh 'docker ps'
end

desc "run"
task :run do
sh 'docker run -p 80:80 --name hiramasa -d hiramasa:0.1'
end

desc "rm"
task :rm do
sh 'docker rm -f hiramasa'
end
