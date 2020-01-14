#praktika_class_kolesnikov_maxim_SPTVR19
class Student():
    name= ''
    color= ''
    nationality= ''
    age= ''
    citizenship= ''
    
    def __init__ (self, n,c,b,a,d):
        self.name= n
        self.color= c
        self.nationality= b
        self.age= a
        self.perks=[]
        self.citizenship= d
        
    def addPerks(self,perk_type):
        self.perks.append(perk_type)
         
    def showPerks(self):
        return self.perks

 
class Maxim(Student):
        print('\n'
            'Информация о ученике:')

max1=Maxim('Максим', 'Белый', 'Русский европеец', '18 лет', 'Эстонское')
max1.addPerks('Программирование')

print('\n'
      f'Имя: {max1.name} \n'
      f'Цвет кожи: {max1.color} \n'
      f'Национальность: {max1.nationality} \n'
      f'Возраст: {max1.age} \n'
      f'Умения: {max1.showPerks()} \n'
      f'Гражданство: {max1.citizenship}')
