require_relative './lib/exam_loader'
require_relative './lib/test_runner'

namespace "exam" do
  desc "Start an exam"
  task :start do 
    if ExamLoader.load then
      puts "loaded"
    end
  end

  task :question, [:question_number] do |t, args|
    TestRunner.run(0)
  end
end