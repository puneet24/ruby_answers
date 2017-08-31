
1)	Ruby Method for finding factorial
def factorial(no)
    f = 1; for i in 1..no; f *= i; end; f
end

2)	SublimeText
3)	Ruby method to check that 1 string contains another or not.
def exists(str1, str2)
    str1,include? Str2
end

4)	
5)	
class Admin                           # Declaring class admin
    cattr_accessor :tabs              # getter and setter methods for class instance variable named tabs
    class << self                     # This is the advanced way to do this, is to define a method inside the Class instance itself. This is referred to as the eigenclass or the singleton class and it uses the self keyword to open a new context where the Class instance is held in self
        def add_tab(tab)              # Definition of class instance method named add_tab
            @@tabs = @@tabs | [tab]   # setting union of (@@tabs, and tab) array and taking unique values out of that
        end
        def tabs                      # Definition of class instance method named tabs
            @@tabs.sort               # returning sorted tabs in ascending order
        end
	end
end	

## In ruby last line is by default returning in any method.																					

