# Setting up Rust in vs-code

## Linux & MacOS

### Installing the language

First, open up the terminal
Run the cURL command ```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```
![image](https://github.com/De-y/blog/assets/61808223/8422ceea-877d-4baf-8ba3-f7815e22f004)

And then let the installer run and answer all the prompts for your install. (It may take some time to download the installer)
![image](https://github.com/De-y/blog/assets/61808223/9523164b-4fcf-4b11-8484-1623c9c3734e)


After that, you are done!

### Initializing vs-code with the necessary extensions

Search for Rust in the extensions marketplace and choose the "Rust" extension by rust-lang.
![image](https://github.com/De-y/blog/assets/61808223/fd0373b1-2d52-4a83-b416-299e836a7040)

Once that is installed, you will need a couple more extensions (depending on your expertise and what you need)
You will need to search for Crates in the extension marketplace and choose the "crates" extension, as so.
![image](https://github.com/De-y/blog/assets/61808223/2829fc85-70cb-4f73-a047-7ddb5faf6403)

Finally, you will need to search up for the rust-analyzer package on the extensions marketplace, and install it.
![image](https://github.com/De-y/blog/assets/61808223/3c159c01-ec43-4f0c-ac61-80b8a5d78654)

After that, you should be good!

#### However, if you are not

If you get an error like this
![image](https://github.com/De-y/blog/assets/61808223/bbe56560-9e91-443d-95c9-8932f30dd603)
Then you will need to rerun the shell script or you will need to uninstall rust and then reinstall it from the shell script and then intialize vs-code with the necessary extensions.

But that is basically it for Linux & MacOS!
