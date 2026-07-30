class myClass:

    # Private Variable
    __privateVaar = 28
    def __privMeth(self):
        print("I'm inside my class, myClass")

    def hello(self):
        print("Variable Value: ", myClass.privateVaar)


foo = myClass()
foo.hello()
foo.__privMeth
