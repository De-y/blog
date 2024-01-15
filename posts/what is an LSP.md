# What are LSP's
An LSP, or the language server protocol, is an open-source standard for communicating between a client and a server.

It became open-source and was initially developed in 2016 by Microsoft for Visual Studio.

# What are these clients and servers, and what do they do?

You have the client, which is the IDE, like Visual Studio Code.

Then, you have the server, which is the language server, like the C++ language server or the Python language server.

These two communicate together to be able to do features like

* Syntax highlighting
* Code completion
* Highlighting problems or code errors.

Which then allows you to go ahead and fix your lousy code (mine, at least)


![image](https://github.com/De-y/blog/assets/61808223/851f8ce1-8f79-43a2-9870-766931f45ddb)

This is a basic example of how LSP works with the client sending a request over to a server utilizing the language server protocol to check some lines of code, with the language server checking it and then returning some things to the client, pointing an error or something (happens continuously whenever you write something for mistakes, and is very fast at doing this), it can go further which we will check.

## A deep-dive into how it works

Basically, what is happening is the following diagram:

![image](https://github.com/De-y/blog/assets/61808223/d40a529b-0698-445e-b1ab-84a8b82122b6)

First, the client sends the request through LSP, and then after the language server receives it and processes it using parsing (basically a way for the server to "read" and understand the code) and further code and through linting (the primary way to identify errors, bugs, and stylistic issues) to iron out and to see if there are any errors; if there aren't, the server sends its decision back and then waits until a new request is made. However, if an error or issue is found, the server will return its decision and then instruct the client to highlight the line of code where there is an error.

That way, the client and the server know that
``console.log("Hello")`` is valid, while
``console.log(Hello)`` is invalid, as no variable named "Hello" is defined, which will then be highlighted as an error.

The below image shows it in a side-by-side comparison.

![image](https://github.com/De-y/blog/assets/61808223/d5270e22-9678-4a04-8815-9712be3df263)




# Useful Keybinds
CTRL + SPACE gives you a context menu for auto-filling in a necessary function.

![2024-01-15-09-03-46](https://github.com/De-y/blog/assets/61808223/6ff3e3d6-7dc8-48bd-9d51-c5300a7a1987)

A quick gif that shows you how to utilize this feature

I first used CTRL + SPACE to get to the context menu, then went down using my down arrow (you can use a mouse), found what I wanted, and then press enter. Then, what happens is that there will be suggestions for autofill done automatically by the language server.

Then, I used console.log to print out the length value of BarProp.

# What's next?

To start using the LSP, you will need an IDE and a Language Server for the language you will program in.

You can find the necessary language servers [here](https://langserver.org/). Then you will need to install that necessary language server and set it up inside your IDE (should do it automatically)

![image](https://github.com/De-y/blog/assets/61808223/d80c075b-d680-4de0-821a-4f10abd5e7c3)

Language Server table with all the different servers and whether or not they meet a category, can be found at langserver.org.


After that, you should be good!
