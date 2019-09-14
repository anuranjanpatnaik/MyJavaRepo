#If you know how to compile programs on the command line, and if you have
#downloaded the examples, you can easily compile and run all the examples.
#For non-GUI programs, just change into one of the chapter directories inside 
#the "sources" directory, and use a command of the form

#                  javac ExampleClassName.java
                  
#For example:
#                  javac HelloWorld.java
                  
#As long as your compiler supports Java 8 or higher, there should be no errors.  
#(You might see some warnings, especially if you use a newer version of Java, 
#but warnings do not stop a program from being compiled or executed.)  You can 
#then run the compiled programs using the java command.  For example:

#                  java HelloWorld
For GUI programs, which use JavaFX, you will have to add command-line options to
the javac and java commands, as discussed in Section 2.6 of the textbook,
but the basic idea is the same.
