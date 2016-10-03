require 'pry'
def 確認運算方式
 puts"請輸入你的運算"
 puts"1.加 2.減 2.乘 4.除
 iuput = gets.chomp.to_i
 end while ![1,2,3,4].include?(input)
 return input
 end

 def 計算(input, num1, num2)
 case input
 when 1
 puts "你的答案為：#{num1 + num2}"
 when 2
 puts "你的答案為：#{num1 - num2}"
 when 3
 puts "你的答案為：#{num1 * num2}"
 else
 puts "你的答案為：#{num1 / num2}"
 end