# WilliamOtto_T1A1

# Q1
Web development markup languages are languages that are designed to change the structure of a document. This includes how parts of the document relate to one another. The expectation for modern markup languages is that they should be accompanied by stylesheets which can format and or process the information supplied by the markup document.

In the case of HTML, and many other modern markup languages, the main building blocks of the languages are called elements, or tags. Tags are used to describe the structure of a single part of the document. HTML has two types of elements, inline and block. Examples of inline elements include; italics, bold, URLs, image links and code spans. Examples of block elements include; paragraps, lists, tables, headings and footers.

# Q2
## Packets
Packets are segments of data that contribute to a larger message. Once packets reach their destination, they are recombined by the device that receives the data. The reason for their widespread use in networking is due to the efficiency that their use imparts to the network as a whole. In the case of the internet which is a packet switching network, breaking down data into smaller pieces, and allowing these packets to move to their destination through other network paths is essential. The reason for this is that no particular network path has to succumb to its capacity to transmit data as the load is spread in a more efficient way amongst many paths. This enables other devices to share the same network path without running into bandwidth issues.

## IP Addresses (IPv4 vs IPv6)
An IP address is a numerical label assigned to every device in a network that uses IP protocol to facilitate data transfer. It enables you to identify a specific device on a particular network. IPv4 is an IP protocol that was first used in 1983, and handles most of the internet traffic today. IPv6 is a newer protocol that is likely to supersede IPv4 at some point in the future. The main difference is the number of unique IP addresses that can exist on each protocol. IPv4 is a 32-bit numeric address which means there is only 2^32 combinations for unique IP addresses. IPv6 is a 128-bit alphanumeric address which means there are significantly more potential IP addresses available. As there is an IP address shortage, a transition to IPv6 would aid in solving this problem.

## Routers and Routing
Routers are devices which connect 2 or more networks together in a vast system of routers. Their primary function is to forward packets to the IP address that is indicated within the packet header. This is essential as they allow the internet to exist as a packet switching network which is vital for maintaining high speeds of data transfer. Packet switching networks in addition to making data transmission more efficient, also have a resilience toward hardware failure due to its decentralization. If a particular router was to fail, thanks to packet switching, the internet would still be able to function.

## Domain and DNS
A domain is the name given to any website. To connect to a website, a person can use the domain name to connect, which is where DNS comes into play. The DNS, or domain name system is a naming system that maps domain names such as google.com to a certain IP address and port number. When a user types a domain name into the web browser, the search query travels to a DNS server, and returns an IP address and port number relevant to the website that has been searched. This means the user doesn’t have to remember a string of numbers, and can instead just memorize the domain name.

In terms of domain name structure, different domain levels are controlled by different DNS servers. This is to make web searches more manageable as there are over 300 million domain names. The domain structure is as follows; top level domains (.org, .net, .gov, .com), second level domains (google.com, dftba.com), and sub-domain of parents (drive.google.com, images.google.com, store.dftba.com)

# Q3
## TCP
TCP or Transmission Control Protocol is a communication protocol that allows computer applications to communicate with computing devices over a network. The TCP's primary job is to etablish and maintain a connection between applications or devices until the data hasbeen transferred. It works in conjunction with IP which is solely responsible for obtaining and defining the address. This combination is called the TCP/IP model and is the most widely used method of data communication on the internet.

## HTTP & HTTPS
HTTP (Hypertext Transfer Protocol) is an application protocol that is used to enable file exchange on the Internet. HTTP appears at the start of every url and is designed to make the internet more efficient. HTTP lets web browsers make requests and communicate with the web servers. HTTPS serves the same purpose as HTTP, namely, to fascilitate data transfer over the internet, however, HTTPS has an additional security layer which is essential for websites that contain sensitive information such as peoples credit card information, or billing addresses.

## Web Browsers
A web browser is a software application that is designed to allow you to access the world wide web. The user of the application requests data from a specific website, and it is the web browser's responsibility to retrieve the data from that website, and display it graphically on the users computer screen.

# Q4
## Tuples
Tuples are used to simplify code. They allow you to store many different pieces of data within a single variable. These pieces of data are called elements. The primary use for tuples is to simplify and condense code so that it is more readable, and less repetitive. Elements of a tuple are ordered, and cannot be added replaced or removed. Tuples are used when you want to keep the elements fixed, and ordered.
## Lists
Lists have a similar purpose to tuples in that they allow you to store multiple elements in a single variable. The main difference lies in the fact that lists are mutable. Mutability refers to the ability for an element to be changed within the list. Elements can be added, changed and removed. Lists are used when order and ability to change elements is a priority.
## Sets
Sets are again similar to lists and tuples, whereby they are comprised of elements, however a set can not contain duplicates. Sets are also unordered, and as a consequence, elements can not be accessed through indexing, they can only be checked to see if they are in the set. Sets are used when ordering isn't a priority.

# Q5
An interpreter, or more generally, a REPL is a program that has the ability to execute commands and display them. The interpreter executes code line by line, converting each line into machine code. A consequence of this fact is that interpretation is not very time efficient. An advantage of the line by line conversion is that the program can be debugged more easily as the whole program doesn't need to be compiled every time a change is made. Common interpreted languages include; Python, JavaScript, Java, C#, PHP.

Conversely, a compiler is a program that turns all of the source code into machine code before executing the program. This makes compiled code faster to execute, however this does come with a disadvantage being that the entire program needs to be converted into an executable file before any changes can be made, slowing the debugging process down. Another advantage of compiled code is that there is an added layer of security because the consumer only receives the binary code, with no way to see how the program works. A compiled program is not cross platform compatible as the executable file is designed for a specific operating system. Separate binaries need to be created for different operating systems. Common compiled languages include; C, C++, Objective C.

# Q6
## Python vs C
Python is a high-level object oriented programming language. High-level means that the language is closer to human language rather than machine code. High-level languages are more focused on complex aritmetical operations and program efficiency. Contrastingly, C is a mid-level procedural language. Mid-level means that the language bridges the gap between machine level and high level languages; C can be used to do system programming for writing operating systems as well as application programming. Procedural languages are more difficult to understand for beginners because it requires the implementation of step-by-step instructions that break tasks down into smaller parts (variables and routines).

Python being higher level means that it is easier to understand for beginners than C. Contributing to this readability is how variables are declared in Python versus C. In Python, when declaring a variable, there is no need to define a data types as this is handled automatically. In C, data types need to be explicitly declared when creating a variable. This makes the code more difficult to understand. A drawback of this feature is that the language is less efficient with processor and memory. Additionally, it requires an interpreter to be translated into machine code. C, however, has a shorter run time as the code only needs to be compiled and not interpreted. Compiled code has the advantage of being more secure but is harder to debug and is not cross-platform compatible.

# Q7
For software developers the question of ethical programming is an important topic to take into consideration.

# Q8
Control flow refers to the order in which a program will execute the code. The standard way for a program to execute code is seqentially, however many programming languages respond to input which can change the control flow.

An example of a basic control flow in Python are boolean data types. Rather than letting the code execute sequentially, the boolean data type can be used which has two potential values 'True' and 'False'. Booleans are used when any decision needs to be made.

Comparison operators are another simple form of control flow in Python. Examples of comparison operators include; <, >, ==, !=. These operators change the flow of the code by resolving either a true of false value.

Another type of control flow statement are the if, elif and else statements. An if statement will check if a condition in the if statement is true or false. If the condition is true, the code indented below the if statement will be executed. Any subsequent if statements will be checked even if only one statement can be true.

The elif statement is used when only one condition is meant to be true. If there is a list of elif statements below the initial if statement, the first elif statement that is true will be executed. Any subsequent elif statements will be ignored which saves on valuable CPU time.

The Else statement is used when we want to execute some code only if all of the prior statements are false.

# Q9
Type coercion allows for the conversion one data type to another. With type coercion, the process happens automatically or implicitly. Type conversion is similar in that it also converts one data type to another but with one distinction - type conversion is implicit or explicit, or in other words, it can happen manually, or automatically.

Python has support for type conversion, but not for type coercion. Examples
include the conversion from an integer into a float which can happen implicitly or explicitly. An example of implicit conversion would be if we were to try and sum two values, one being a float, and the other being an integer. In this case the output would be a float value. This is implicit because the conversion is done automatically by the interpreter. To avoid data loss, converting from a lower data type (integer) to a higher data type (float) is recommended.

An example of explicit conversion would be the sum of a string and an integer. For this example, the string would need to be converted into an integer using the int() function, then the resulting values can be added together. This is explicit conversion because additional input is required to force the conversion from string to integer.

# Q10
Data type is an important concept in all programming languages. Having the ability to store different types of data in a variable gives that variable different behavioural characteristics.

Whenever we want to store a sequence of letters in a variable, we need to use the string data type. The string is denoted by either single or double quotes. One of the features of the string data type is that it enables you to be able to access individual elements in the string using square brackets. Another feature comes of the fact that the string are treated as an array. This means you can loop through the string which has many useful applications. You can also access the length of the string using the len() function. The keyword 'in' can be used to check if a certain sequence of characters is in the string. Some of these features are unique to strings.

The int data type is used to convert a specified value into an integer. The syntax is as follows: int(value, base) where the value is the number or string that needs to be converted. The base value is the number system that the value is in.

The list data type is used to store more than one item in a variable. The list data type's characteristics include the fact that it is ordered and items can be added, removed or changed.

Data types are essential as they allow the coder to specify the behaviour of a variable and what kind of data it takes in.

# Q11
Define a generic class for food items, another child class for drinks and any other category of food such as pizza, burgers, pasta, etc. The generic class will have basic information that all items on the menu have such as price and name of the dish. All other items on the menu will inherit from this, but will have additional information with regards to toppings or drink size etc.

# Q12
celcius = float(input())
fahrenheit = (celcius * 9 / 5) + 32
print(f"The result is: {fahrenheit}.")

The issue for this code snippet is that to explicitly convert the data type to, in this case, a float value, the float() function needs to be specified in the first line. There is no such data type called convert(). Additionally, the input function is necessary to allow the program to receive an input from the user to convert into farenheit.

# Q13
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
i = 0
    while (i < len(arr)) and (arr[i] < arr[i + 1]):
        i += 1
    arr[i], arr[i + 1] = arr[i + 1], arr[i]
    print(arr)

# Q14
set n and i = 1
for n in range between 1 and 101
    n + 1 and i = 2
    if
    for i in range between 2 and n - 1:
        if remainder of n / i is equal to 0:
            break
    else:
        add 1 to i
    else:
        print number n and return

![alt text](Flowchart.png)

# Q15
print("What is the temperature?")
temperature = float(input())
print("Is it raining?")
raining = bool(input())

if raining == ("yes") and temperature < 15:
    print("It's wet and cold")
elif raining == ("no") and temperature < 15:
    print("It's not raining but cold")
elif raining == ("no") and temperature > 15:
    print("It's warm but not raining")
else:
    print("It's warm and raining")

# Q16
Skill_info = {'PYTHON': 1, 'RUBY': 2, 'BASH': 4, 'GIT': 8, 'HTML': 16, 'TDD': 32, 'CSS': 64, 'JAVASCRIPT': 128}

user_input = []
skill = ''
while skill != ' ':
    skill = input("Enter a skill or [space] to quit: ").upper()
    if skill != ' ':
        if skill in Skill_info:
            user_input.append(skill)
        else:
            print("Not a valid input!")

score = 0

for skill in Skill_info:
    if skill in user_input:
        score += Skill_info[skill]

print("Your skill score is: {}".format(score))

print("You can improve your score by learning other languages!")

# References
https://en.wikipedia.org/wiki/Markup_language
https://www.ssc.wisc.edu/~hemken/Stataworkshops/stmd/Markdown/markdownelements1.html
https://www.cloudflare.com/learning/network-layer/what-is-a-packet/
https://www.guru99.com/difference-ipv4-vs-ipv6.html
https://www.thousandeyes.com/learning/techtorials/ipv4-vs-ipv6
https://www.fortinet.com/resources/cyberglossary/tcp-ip#:~:text=TCP%20stands%20for%20Transmission%20Control,data%20and%20messages%20over%20networks.
https://www.cloudflare.com/learning/network-layer/what-is-a-router/
https://www.fortinet.com/resources/cyberglossary/what-is-https
https://www.fortinet.com/resources/cyberglossary/http-proxy
https://www.mozilla.org/en-US/firefox/browsers/what-is-a-browser/#:~:text=How%20does%20a%20web%20browser,are%20transmitted%20on%20the%20web.
https://www.guru99.com/difference-compiler-vs-interpreter.html
https://www.programiz.com/article/difference-compiler-interpreter
https://www.interviewbit.com/blog/difference-between-c-and-python/#:~:text=Python%20is%20an%20object%20oriented%20programming%20language.&text=C%20is%20a%20middle%20level,machine%20language%2C%20using%20an%20interpreter.&text=C%20is%20a%20compiled%20programming%20language.
https://www.dotnettricks.com/learn/c/why-c-is-called-middle-level-language
https://www.educative.io/answers/what-are-control-flow-statements-in-python
https://medium.com/analytics-vidhya/python-fundamentals-for-everybody-type-conversion-vs-type-coercion-34234e99c9c4
https://developer.mozilla.org/en-US/docs/Glossary/Type_coercion
https://www.w3schools.com/python/python_datatypes.asp
https://www.programiz.com/python-programming/variables-datatypes
