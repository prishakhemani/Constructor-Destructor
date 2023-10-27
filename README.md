# Constructor-Destructor
# Constructor

A constructor in C++ is a special ‘MEMBER FUNCTION’ having the same name as that of its class which is used to initialize some valid values to the data members of an object. It is executed automatically whenever an object of a class is created. The only restriction that applies to the constructor is that it must not have a return type or void. It is because the constructor is automatically called by the compiler and it is normally used to INITIALIZE VALUES. The compiler distinguishes the constructor from other member functions of a class by its name which is the same as that of its class.

# Syntax

The syntax for defining constructor inside the class body is as follows:

class CLASSNAME

{

   ………
   
  public :
  
               CLASSNAME([parameter_list]) 
               
             {
             
                . . . . . . 
                
             }
             
              . . . . . . . .
              
};

You can also define a constructor with its declaration inside the class body and see what follows.

class CLASSNAME

 {
 
 . . . . . . . . 
 
public:

          CLASSNAME ([parameter_list]);
          
         . . . . . . . . .
         
}; 

CLASSNAME: :CLASSNAME([parameter_list])

{

. . . . . . . . . . .

}



# Types

There are 3 types of constructors in C++, They are :

1)Default Constructor

2)Parameterized Constructor

3)Copy Constructor
