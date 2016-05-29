#笨办法学python学习笔记
##习题6
1. 示例代码学习
**示例代码**：

```
x = "There are %d types of people." % 10
binary = "binary"
do_not = "don't"
y =  "Those who know %s and those who %s." %(binary , do_not)

print x
print y

print "I said: %r." % x
print "I also said: '%s'." %y

hilarious = False
joke_evaluation = "Isn't that joke so funny?!%r"

print joke_evaluation % hilarious

w = "This is the left sige of ..."
e = "a stirng with a right side."

print w+e

```
**运行结果**：
>There are 10 types of people.

>Those who know binary and those who don't.

>I said: 'There are 10 types of people.'.

>I also said: 'Those who know binary and those who dont't.'.

>Isn't that joke so funny?!False

>This is the left sige of ...a stirng with a right side.

__问题总结__：

- print出错

错误提示：

>SyntaxError: Missing parentheses in call to 'print'

原因：在python3中，print是一个函数，需要加上()。




