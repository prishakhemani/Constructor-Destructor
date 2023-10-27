# Constructor-Destructor
# CONSTRUCTOR

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

# DESTRUCTOR

Destructor is a member function which deletes an object. A destructor is called automatically by the compiler when the object goes out of scope. A destructor is a special member function that works just opposite to constructor, unlike constructors that are used for initializing an object, destructors destroy (or delete) the object.

# Syntax:

className{


    // Some code
    
};

# Properties

1)Destructor function is automatically invoked when the objects are destroyed.

2)It cannot be declared static or const.

3)The destructor does not have arguments.

4)It has no return type not even void.

5)An object of a class with a Destructor cannot become a member of the union.

6)A destructor should be declared in the public section of the class.

7)The programmer cannot access the address of destructor.

# Difference betwn constructor & destructor

![64fadc0c6f803_constructor__destructor_in_c](https://github.com/prishakhemani/Constructor-Destructor/assets/142494518/cf417ae9-5d15-433b-88d9-3259948a3383)







