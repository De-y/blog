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
![2024-01-15 08-56-02](https://github.com/De-y/blog/assets/61808223/a419074f-7151-45b5-b0a6-2065e09f36ed)
GIF showing what happens when you hold CTRL + SPACE.

