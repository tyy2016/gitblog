##print
- print'100+200=',100+200----100+200= 300
- print'hello,python.'----hello,python
- print'hello,''python'----hello,pyhton
- print 'hello','python'----hello python

##description
'#This line is used for description....'
'print 'hello,python'.... #'

##variance
- 在Python程序中，变量是用一个变量名表示，变量名必须是大小写英文、数字和下划线（_）的组合，且不能用数字开头
- eg:1,4,7,10,13,16,19....,前 100 项的和.
	x1=1
	d=3
	n=100
	x100=x1+(n-1)*d
	s100=(x1+x100)*n/2
	print s100

##char
- 字符串可以用''或者""括起来表示.
- 符串本身包含':"I'm OK."
- 符串本身包含":'Learning "Python".'
- 如果字符串既包含'又包含":'Bob said \"I\'m OK\".'
- \n表示换行; \t 表示一个制表符; \\ 表示 \ 字符本身
- eg:请将下面两行内容用Python的字符串表示并打印出来:Python was started in 1989 by "Guido".Python is free and easy to learn.
- s='Python was started in 1989 by \"Guido\".\nPython is free and easy to learn.'
- print s

##raw
- 在字符串前面加前缀r，表示这是一个raw字符串，里面的字符就不需要转义了.
- eg:r'Python was started in 1989 by "Guido".'

##多行字符串
- '''line1
- line2
- line3''' =
- 'line1 \n line2 \n line3'
- eg:请把下面的字符串用r'''...'''的形式改写，并用print打印出来：
- '\"To be, or not to be\": that is the question.\nWhether it\'s nobler in the mind to suffer.'
- print r'''"To be, or not to be":that is the question.
- Whether it's nobler in the mind to suffer.'''

##Unicode
- print u '中文'----中文
- u'中文\n日文\n韩文'
- u'''第一行
- 第二行'''
- # -*- coding: utf-8 -*-:第一行添加注释
- eg:多行Unicode字符串表示下面的唐诗并打印：
- 静夜思
- 床前明月光，
- 疑是地上霜。
- 举头望明月，
- 低头思故乡.
- print u'''静夜思
- 床前明月光，
- 疑是地上霜。
- 举头望明月，
- 低头思故乡。'''

##整数和浮点数
- 11/4=2
- 11%4=3
- 11.0/4=2.75
- Python的整数运算结果仍然是整数，浮点数运算结果仍然是浮点数,整数和浮点数混合运算的结果就变成浮点数.

##布尔类型
- 布尔类型只有True和False两种值,有以下几种运算true,or,not.
