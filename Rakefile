desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end
desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end
  
  namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do
    Student.create_table
  end
  
  desc 'drop into the Pry console'
task :console => :environment do
  Pry.start


end

[1] pry(main)> Student.all
=> [[1, "Melissa", "10th"],
 [2, "April", "10th"],
 [3, "Luke", "9th"],
 [4, "Devon", "11th"],
 [5, "Sarah", "10th"]]
 end 
end

