# calculator
一个原生js写的简易计算器
主要思路是：
1、用事件代理，捕捉用户的点击操作
2、用一个数组来保存用户的操作
3、判断各种条件
4、用join("")的方法，将用户的操作连起来
5、用eval()的方法将结果得出。并将结果再次保存到数组中，以便可以在结果的基础上继续计算。
