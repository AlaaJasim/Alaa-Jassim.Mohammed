# Alaa


  class Information:

    def __init__(self,name,age):
        
       self.name = name
       self.age =age
       
    def print_max(self):
       
       print("Name:",self.name)
       print("Age;",self.age)
       
    def print_Info(Salary,job):
       
       print("There Salry:{}".format(Salary))
       print("There Job:{}".format(job))
       
p1 =  Information("Alaa Jasim",19)
p2 = Information("Ahmed Raad",20)

p1.print_max()
p2.print_max()

Information.print_Info(1500 , 'programmer')
