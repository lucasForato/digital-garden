---
title: A simple API in C++
publish: "true"
---
## The Objective

I have learned through some years working as a developer that the best way to improve my development skills is by building my own projects. Since C++ is a very extensive language, my goal is crafting simple yet purposeful projects that are going to teach me specific topics of interest. 

Building an API required me to learn countless subjects, including:
- How to build projects in C++ using **CMake**
- How to configure my **Neovim** environment to work with C++
- Object Oriented Programming in C++
- How to write header files.
- How to structure a simple project.

These are some of the concepts that building an API enabled me to learn. I always find it incredible how the simple act of practicing is one of the most powerful ways to acquire new skills in the field of programming.

## The Project

The project was meant to be as simple as possible and yet offer me a lot to take in. I went with a simple **authentication system** using **C++**, **CMake** and **SQLite**. The goal was being able to **sign up**, **sign in**, and **list users**. I would have to hash the password and deal with HTTP, which was a lot for someone who knows 0 C++.

## Neovim

Many people on the internet recommended using **CLion** as the IDE to write C++, for its simplicity when it comes to CMake support and many other features that come out of the box. I went with a rather different approach, which was **[Neovim](https://neovim.io/)**. Neovim is an extension of Vim that allows anyone to build their own IDE using the best navigation provided by Vim and the simplicity of Lua for configuration.

All I had to do was support C++ in my LSP configuration, which was pretty straight forward. I will write an article in the future explaining my Neovim configuration, so stay tuned.

## CMake, the nightmare

CMake was a big pain for me. Coming from a **Node background**, everything was as simple as running a simple `npm install` command and everything would be dealt with for me. C++ also offers some package managers, but I decided to go with the more difficult solution, which was building my own **CMake** file and install all my packages.

At first, things seemed pretty OK, since I found a great resource on the internet explaining the [most important CMake concepts](https://learnxinyminutes.com/docs/cmake/). All of a sudden, I had to download a package for dealing with HTTP for me and things started to fall apart. Installing a package in C++ can be painful, I had to download the code, build the code, add the dependency to CMake, among some other things. Each package was a different nightmare. But after some time, I started to understand the concepts of adding new packages to the project and things started to be faster. The first package was mostly a day to add, the last one took me 2 hours, big improvement, huh?

And after dealing with CMake for some days, I can say that I understand the basics of it. I am no pro, far from that, but I can understand it and sometimes write my own stuff.

## Learning C++

As I said previously, learning a language for me comes down to writing projects and let the projects tell me what I have to learn. That was exactly the approach I took for my first C++ project.

In the beginning, I read more and wrote less, the idea was getting familiar with the syntax and how things work in a more macro environment. Then, I started writing the project. Each time I faced a problem that was new and needed some learning, I would go to [learncpp.com](https://www.learncpp.com/) and I looked for the topic that I needed to learn, understanding it in more detail. Sometimes that source was not enough and I had to search for other solutions using **AI** or the **good old Google**. After some weeks I was able to find my way through all problems in the project and finally delivered what was expected in the first place.

## The code

If you are curious like me, you are probably wondering how the code turned out to be, for people like us, I wrote a second part to this article which is focused on the more technical part, explaining how I solved some simple project, you can check it below:
[[A simple API in C++ pt. 2]]

## Conclusion

Through this journey, I have learned a lot about **CMake** and how to work with libraries in C++, which was a big win for me. My next goal is implementing a simple checkers game in C++, which will teach me more about the syntax, structure, and patterns of writing a good C++ program. See you then :)