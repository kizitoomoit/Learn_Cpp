## This is a description of the Hello_World.cpp program

 In C++ the statements that come after "//" are refered as comments
 These comments are love letters to your future self.

 They help you in future to understand your own code or it can help other programmers who might go through your code to understand what is going // on.

 Function header is where we give our function a heading and a type for our instance int main() is our function header.
 The part which is enclosed with the curly braces {} are refered to as function body,

 function body is the representation of your instructions to the computer on what the function should do(This is where you function logic goes)
 In C++ ieach complete instruction is called a stetement and should be terminated with a semicolon so to notify the computer that the statement
 is over and expect the next statement.

 Finally to terminate our function we use the return 0 statement which tells the complier we have come to the end of our function.
 In C++ the first function must always be main that tells the compiler that your program has begun and if it is missing you program will throw erros because it expects always to find the main() function first.

 the int that comes before the main () function name is the return type of the function which tells other functions that call this function which return type to expect.
 What comes inside the brackets() is argument(s) and for our case main usually doesn't take any arguments from any function, you can also decide to explicity define void inside the brackets int main(void) to tell other functions which call the main function that the main function doesn't take any arguments.

 Also you can use key word void like this void main() instead of int main(void)
 #include <iostream> - This is refered to as preprocessor- Which referes to the program that processes a source file before the main compilation takes place.
 The #include directie causes the preprocessor to add the contents of iostream file to your program

 The iostream are called the include files or header files because theya re included at the beginning of a file.
 Each header files has its own use case, ie the iostream header files handles the interaction of your program with the outside world.
 The io in the iostream header stands for input and output which handles your interactions with the program.

 The using namespace std; helps use the cout and cin which helps us to take print the output to the screen of the user or take the input from the user using the keyboard.
 The \n is a newline operator which makes the cursor move to the beginning of the next line
