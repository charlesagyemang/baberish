task :c do
  ARGV.each { |a| task a.to_sym do ; end }
  puts `git add . && git commit -am "#{ARGV[1].to_s}"`
end


task :push do
  ARGV.each { |a| task a.to_sym do ; end }
  puts `git add . && git commit -am "#{ARGV[1].to_s}" && git push origin #{ARGV[2]}`
end

task :h do

  ARGV.each { |a| task a.to_sym do ; end }
  puts `git add . && git commit -am "#{ARGV[1].to_s}" && git push origin master && git push heroku master`

end

task :mod do

  ARGV.each { |a| task a.to_sym do ; end }
  puts `yo rocket-api:module #{ARGV[1]}`

end

task :set do
  puts `heroku run yarn sequelize-stage db:migrate`
end


task :serve do

  ARGV.each { |a| task a.to_sym do ; end }
  param = ARGV[1]

  if param
    cmd_line = "http://localhost:#{ARGV[1]}/"
    system("/Applications/Google\\ Chrome.app/Contents/MacOS/Google\\ Chrome --url #{cmd_line}")
    puts `ruby -run -e httpd . -p #{ARGV[1]}`
  else
    puts "Please parse a port number"
  end

end

task :close do
  ARGV.each { |a| task a.to_sym do ; end }
  param = ARGV[1]

  if param
    puts `lsof -i:8080`
  else
    puts "Please parse a port number"
  end

end
