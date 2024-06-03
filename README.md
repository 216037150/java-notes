# java-notes

  Java is a widely-used, general-purpose, class-based, and object-oriented programming language that is designed to have as few implementation dependencies as possible
  Java Course Content

    Introduction to Java
    Java syntax and data types
    Java classes and objects
    Java inheritance and polymorphism
    Java for web development
    Java for Android mobile app development
    Best practices for Java programming


    Outcomes

     Introduce candidates to the basics of Java programming
    Teach candidates how to use Java for object-oriented programming
    Provide candidates with a solid understanding of Java concepts such as classes, objects, and inheritance
    Teach candidates how to use Java for web development and Android mobile app development
    Provide candidates with hands-on experience creating Java programs

 Java serves as a common programming language for newcomers. Think of it as our way of chatting with computers. Software engineers wield Java to craft an array of apps—web, mobile, and desktop ones. These apps  fall under the Java applications or programs category because they are constructed with Java. 

 You have most likely bumped into programs demanding the Java Runtime Environment (JRE) for operation. This component enables your computer to run Java programs. For crafting and compiling Java programs, you    will need the Java Development Kit (JDK), bundled with the JRE and handy compilers and tools. With JDK installation, the JRE comes along automatically.


# JDK
The 'SE' stands for the standard edition, which suits our needs perfectly. We are currently working with Java 17.0.2, the latest version in development. But no need to stress, if there are newer versions when you are in the course, feel free to use those. Just remember, as you delve deeper into Java, the differences between versions matter more. Also, ensure you grab the right JDK for your operating system.

# Installing IntelliJ IDEA
 In this course, We will be using IntelliJ, a free and open-source code editor. You can grab it from jetbrains.com/idea, just hit that download button. They will try to detect your operating system for you,     so just make sure they have got it right. Look for the Community Edition download and start the download. Once it is finished, simply double-click to open it.

 If you are using a Mac, drag the application into your Applications folder. On Windows, follow the installation prompts. Once that is all sorted out, double-click on the app. This is where We will be doing      all our coding—it is our IDE, short for integrated development environment. So, moving forward, all our code will be written here. Easy as pie!

 There are a couple of ways to write and run Java programs. One option involves using a text editor and the command line. Essentially, you type out the code in a text editor like Sublime or Atom, and then you   rely on the command line to both compile and execute it. For instance, you could write some code in the text editor to display "Hello" in the console, and then you would execute it through the command line

 To get started, you will want to click on "New Project" and configure some settings. One of the key things to configure is the specific version of Java We will use for coding and running our programs. Do you   happen to know which Java version we should opt for?

After we download Java 20, let's go ahead and choose that option. If Java 20 is not showing up, just make sure you have downloaded the JDK for Java 20. 

Moving on, we will give our project the name "Learning Java" and make a new folder for it on our desktop. Once those steps are done, we are all set to start our project by hitting the "Create" button.


Moving on, we will give our project the name "Learning Java" and make a new folder for it on our desktop. Once those steps are done, we are all set to start our project by hitting the "Create" button.

Figure 9: Setting up a project in Intellij
![image](https://github.com/216037150/java-notes/assets/52372746/20827fc0-ef00-439c-9765-f8764fc60c50)

Now that IntelliJ is all set up, let's get into how to use it effectively. The navigation pane on the left is super useful. It helps us switch between different project files. For example, there is an .idea folder with important project metadata.

But the SRC folder is where the real action happens; it is the source code hub. This is where we will find our main Java code and where we will do most of our coding. Think of it as our project's beating heart. 

And do not forget about the external library section. Here, we link up the JDK (Java Development Kit), which is a must for our Java projects.

Up in the top-right corner, we have got some cool buttons for running and debugging our program. We will dig deeper into debugging later in the course, but for now, just hit the play button to compile and run the program. 

![image](https://github.com/216037150/java-notes/assets/52372746/a258fdf4-9eb8-40f4-a35d-6cd6f36dbd7d)

Java is known for its verbosity, which means we have to use more words than some other programming languages for a simple program. However, this can be a good thing for beginners because it helps you grasp the concepts better and keeps things clear. Every Java program needs a class; it is the foundation of all Java code. That is why our file already includes the "public class Hello World" code snippet.

But before we take our code for a spin, there is one golden rule: the file name and the class name in the Java code should match, both rocking that "Hello World" vibe. Otherwise, we are in for a wild ride of errors. 

# Classs
  To create a new class, you right-click on the package, choose "New," and then select "Java Class." Java class names typically start with an uppercase letter. In this case, we are making a class for a gross      pay algorithm, so we name it "GrossPayCalculator." It is a three-word name without spaces, as Java does not allow spaces in class names. Each word starts with an uppercase letter, following Java         conventions. Once you have named the class, press ‘Enter’, and you will see the new class created in the package.

  ![image](https://github.com/216037150/java-notes/assets/52372746/a5348a86-e40c-4d2c-a372-3b493c18cba4)
Now, let's make the tab larger by double-clicking it in our editor. As you can see, the very first line of the Java file is a package declaration. If your Java file belongs to a package (like ours does), the first line should declare the package name followed by a semicolon (;). The declaration is quite straightforward; it consists of the word "package" and then the exact name of the package we have chosen.


Following the package declaration, you will find the class declaration. In a Java file, you always have a Java class. This class is declared as a public class called "GrossPayCalculator," enclosed in two curly braces. In Java, these curly braces serve to group a section of code together. So, voila! We have got our very first Java class. 🎉

# Main Method

you know, when you see those curly braces in Java, just remember that whatever code you place between them is part of the Java class. Those curly braces are like little code houses, and inside one of them, we are gonna whip up a method, which is like another mini house of code. Here is the deal: if you want your code to actually run in a Java class, it has to be cozy inside one of these methods. 

![image](https://github.com/216037150/java-notes/assets/52372746/b43ac600-652e-4734-8ffa-b87c30448cb7)

To make the method, you would write "public static void main" and then put in some curly braces. This method is known as the "main method," and in Java, it is where a program starts running. When you run this class, Java searches for this main method, and that is where the program kicks off. It has to be exactly like this, with the curly braces and all. Methods always come with these curly braces, and everything inside them belongs to that specific method. 

We should insert a print statement into the main method to see it in action. In Java, when we want to display something, we use 'system.out.println' followed by what we want to display within parentheses. it is a common beginner task to print 'Hello World,' so let's do that. We will write 'Hello World' inside quotes and end the line with a semicolon. 

![image](https://github.com/216037150/java-notes/assets/52372746/75f86527-8961-433c-8f68-8a9f1c93281a)

This line is like an instruction that tells Java to display text on the console, and the semicolon signifies the end of an instruction in Java. Now, our class has a main method with one instruction. Let's execute this class. To run it for the first time, right-click anywhere in the program and select the 'run' option. You will see a console window open and print 'Hello World' just as we instructed. Congrats, you have created your first Java program!

# Reserved Words
  When you examine this code, take a look at the different-colored words. The color may vary depending on your editor and theme, but in this context, we are referring to words like "package," "public,"      "class," "static," and "void." 

![image](https://github.com/216037150/java-notes/assets/52372746/5667b537-004f-490d-be7b-85a94b921406)

These are all examples of reserved words in programming. Reserved words are special terms within a programming language, and they have specific meanings defined by the language itself. Consequently, we cannot use them to name variables or elements in our program. So, it is a no-go to label something as "class," "public," or "package" because these words are off-limits; Java has reserved them for specific purposes. 

There is actually quite a long list of reserved words. As we continue to work together, keep an eye on the colors in your code. Whenever you type something and it changes color to orange or whatever hue your editor uses for reserved words, remember that you have just encountered another one of these special terms.

# Java Variable
 A comment is basically something programmers use to leave notes for themselves, not for the computer. When you put two slashes at the start of a line, it becomes a comment, and the computer ignores it. These comments are not necessary for the program to run, but they are like little reminders for us as we work on the algorithm.

First, we need to figure out how many hours someone worked—let's say it is 40 hours. We want to keep track of this number, so we create a variable called "hours" and use the equals sign to store 40 in it. Think of a variable as a place in the computer's memory that holds information, but here is the catch: when you see "hours" turn red on the screen, that means there is a problem. If you hover over it, you will see an error message saying Java does not know what "hours" is because we have not told it yet.

Programming languages come in two formats: dynamic typed and static typed. In dynamic languages like JavaScript, the data type of a variable is figured out as the program runs. No need for upfront type declarations here. But in the world of statically typed languages, like Java, you must declare the variables before using them, because they want to check the data type at compile time.
![image](https://github.com/216037150/java-notes/assets/52372746/3b54add0-0103-48fd-9174-c87833b6bd53)

Now, let's dive into an example. Say we have got this variable called "hours". We are about to use it for the first time, so we need to declare what type of data it is going to hold. Different data types take up different amounts of memory, so you must choose the right one. In this case, we have the number 40, which is an integer. In Java lingo, we would use the keyword "int" to declare it. So, "hours" gets an "int" label, and we give it the value 40.

Next, let's talk about the hourly pay rate, which we will say is $25.50. Since this involves decimal numbers, we need a data type that can handle those. That is where "double" comes in handy. So, we declare a variable named "pay rate" as a "double" and set it to 25.50.

Now comes the math part. We want to multiply the hours by the pay rate and store it in another variable. What should the data type be for this result? Well, since we are multiplying an integer by a decimal, we might end up with a decimal result. So, we label this variable "gross pay" as a "double," and it equals "hours" times "pay rate."

Now, to see the result, we print it out using "system.out.println." We will create a string that says "gross pay" and add our "gross pay" variable to it using a plus sign.

Finally, we run our program, either by right-clicking and choosing "run" or hitting the play button if we have done it before. And voila, the gross pay calculator does its thing! 

# Primitive Data Types
 There are eight primitive data types in Java. First, we have the integral gang, the whole number crew. There is byte, short, int, and long. What sets them apart? Well, it is all about memory size. Take byte, for instance, it is 8-bit, so it maxes out at 256. But long, that is a beast, 64-bit, capable of handling numbers up to 9.2 quintillion and then some!

![image](https://github.com/216037150/java-notes/assets/52372746/08b2541f-e231-4521-974e-7b3a6676696d)

Now, for the decimals. It is float and double. Float gives you seven decimal digits, but if you want precision, double is your friend. It can handle 16 decimal digits. Then there is the boolean gang—always keeping it simple: true or false. No other options! You can also think of it as one for true and zero for false, easy peasy.

Last but not least, char, the single character holder. Just remember, put char values in single quotes, not doubles. Those are for strings.

# Local Variable
 Java, despite being statically typed, allows for type inference with local variables. This means you can simply declare a variable as VAR, and Java figures out the data type based on what you assign to it. Look at this example.
 ![image](https://github.com/216037150/java-notes/assets/52372746/32971c38-4a9a-4b24-b7aa-3f079303d35a)

 Instead of going with boolean for the variable called isWaterWet, you can opt for VAR. Just remember, with VAR, You must give that variable a kickstart right when you declare it. Otherwise, Java will not be able to figure out what data type it should be. This type of guessing game only works for local variables, the ones you declare within a method. You cannot pull this VAR trick for global variables, those at the class level outside of your class methods.

 # Naming Variables
 ![image](https://github.com/216037150/java-notes/assets/52372746/5b43d0a8-3bec-477f-b343-2d0b51b30f93)
 In the GrossPayCalculator program, we use names like 'hours' and 'payRate' for our variables, making it crystal clear what they represent. Some programmers, in a rush, opt for shortcuts like 'h' for hours or 'r' for rate, but that is not recommended since it confuses both others and your future self. 

So, always go for descriptive names in your code—whether it is variables, methods, classes, or packages. The idea is simple: make it easy to understand. When you are collaborating, this becomes even more crucial because your peers might need to make updates. 


**
Course Module 1: Java 101 - Introduction to Java Java Variables Naming Variables

Naming Variables

Figure 26: Creating variables

Figure 26: Creating variables

In the GrossPayCalculator program, we use names like 'hours' and 'payRate' for our variables, making it crystal clear what they represent. Some programmers, in a rush, opt for shortcuts like 'h' for hours or 'r' for rate, but that is not recommended since it confuses both others and your future self. 

So, always go for descriptive names in your code—whether it is variables, methods, classes, or packages. The idea is simple: make it easy to understand. When you are collaborating, this becomes even more crucial because your peers might need to make updates. 

Here is some friendly advice: Java variable naming follows some conventions. Start with a lowercase letter, and if it is more than one word, use camel case (first word starts with a lowercase letter, subsequent words with uppercase). 

Numbers are okay within the name, just not as the first character. Special characters like $ or _ are fine, but avoid dashes. Also, steer clear of Java's reserved words; they have specific meanings. If you goof up, do not worry; the compiler will let you know if your variable name is notvalid.

Figure 27: Variable naming rules in Java

Figure 27: Variable naming rules in Java


# Decision Structures in Java
  The if statement works like a side road in the program. If a certain situation happens, the program takes that side road and executes a certain block of code, then it goes back to the main path of execution. 

  ![image](https://github.com/216037150/java-notes/assets/52372746/0f724ec8-44ba-4d9b-8048-e53cdf59fa5d)

  This code uses an If statement to decide if an employee gets a bonus based on how many sales they made. The If statement checks if the number of sales is more than the quota. If 
  it is, then the employee gets a bonus of US$250. Otherwise, they do not get a bonus.

# If-else Statements
  The if-else statement is a decision structure that allows a program to take one of two paths, depending on whether a certain condition is met. For example, a program could use an if-else statement to determine whether a salesperson has met their quota. If the salesperson has met their quota, the program could print a congratulatory message. Otherwise, the program could print a message reminding the salesperson to try harder next time.

  ![image](https://github.com/216037150/java-notes/assets/52372746/61eb26d0-fb84-40fd-a8ed-91c7bad39001)

This code checks if the user met their quota. If they did, they were informed. Otherwise, they are told how many sales they were short.

The code first initializes the quota to 10. Then, it asks the user how many sales they made this week. Next, it checks if the sales are greater than or equal to the quota. If they are, the code prints a message saying that the user met their quota. Otherwise, the code prints a message saying that the user did not meet their quota and how many sales they were short.

The code uses an if statement to check the condition. The else statement is used to handle the alternative path. The salesShort variable is used to store the number of sales the user was short.
  
# Grading pass rate
  We start with an if statement and say that: 

if the score is less than 60, we will update the grade variable to equal F.
If the score is not less than 60, we move on to the next condition. We say that if the score is less than 70, then the grade is D.
If the score is not less than 70, we move on to the next condition. We say that if the score is less than 80, then the grade is C.
If the score is not less than 80, we move on to the next condition. We say that if the score is less than 90, then the grade is B.
If the score is not less than 90, then the grade is equal to A.
This ensures that all possible grades are covered.


# Switch Statements
A switch statement tests a variable for equality against a list of values. Each value is called a case, and the variable being switched on is checked for each case.

![Screenshot from 2024-06-03 10-47-23](https://github.com/216037150/java-notes/assets/52372746/716102c6-9da7-431f-81c1-bdec542fd4ae)


The switch statement works like the if-else-if decision structure, perfect for situations with more than two options. The key distinction is that if-else-if checks conditions, while the switch statement checks for equality. In a scenario where a user inputs their grade, we can use a switch statement to display a message matching the student's letter grade.

![image](https://github.com/216037150/java-notes/assets/52372746/2372007a-bd3c-4546-b121-738148adb879)

Switch expressions are like switch statements, but they are more convenient. Instead of separately declaring a message and then assigning it with a switch statement, you can simplify things with switch expressions. 

Just place an equal sign after the message and shift the switch structure to the right side. Also, you can make the cases cleaner by using an arrow (a dash followed by a greater than sign) instead of ":message=". This means the same thing; for instance, if the grade is A, it assigns "Excellent job" to the message variable. You can apply this to other cases too.

![image](https://github.com/216037150/java-notes/assets/52372746/cff8fd54-e769-45b9-a833-9e95375110c9)






