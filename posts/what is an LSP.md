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

This is an example of how LSP works with the client sending a request over to a server utilizing the language server protocol to check some lines of code, with the language server checking it and then returning some things to the client, pointing an error or something (happens continuously whenever you write something for mistakes, and is very fast at doing this).

# Useful Keybinds
CTRL + SPACE gives you a context menu for auto-filling in a necessary function.

![2024-01-15-09-03-46](https://github.com/De-y/blog/assets/61808223/6ff3e3d6-7dc8-48bd-9d51-c5300a7a1987)

A quick gif that shows you how to utilize this feature

I first used CTRL + SPACE to get to the context menu, then went down using my down arrow (you can use a mouse), found what I wanted, and then press enter. Then, what happens is that there will be suggestions for autofill done automatically by the language server.

Then, I used console.log to print out the length value of BarProp.

# What's next?

To start using the LSP, you will need an IDE and a Language Server for the language you will program in.

You can find the necessary language servers [here](https://langserver.org/). Then you will need to install that necessary language server and set it up inside your IDE (should do it automatically)

After that, you should be good!
