# -
大作业
class my_robot(object):
    
    def __init__(self, name):
        self.name = name
        self.chat_history = []
    
    def __str__(self):
        return 'Ha, your chat robot %s comes ' %self.name #这个自我介绍一样的话或许可以搞怪一点，我暂时想到这个
Jarvis = my_robot('Jarvis')
print(Jarvis)
