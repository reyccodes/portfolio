# Class Projects!

Throughout my classes, I've gotten the awesome opportunity to learn a ton of pretty interesting skills. Here's a collection of some projects I've worked on for my classes. (Note, by course policies, I cannot publically post most of the source code. Instead, I provided some write-ups on things I've learned for some of the projects!)

## 6.1810: Operating Systems Engineering

I learned a ton in this class about, well, operating systems! Specifically, I've grown more familiar with practical skills, like more familiarity with how to work with memory in C and debugging with gdb, and learned more about the inner workings of Linux. The class primarily consisted of adding specific features to xv6, a bare-bones operating system. Throughout the class, I think I've managed to touch every file in xv6 and really get familiar with how an OS works which is what I primarily wanted to get out of the class. My aspiration is to build my own operation system someday, though now I think I have a much better idea of how many components would go into that!

### Copy-on-Write

An oddly finnicky aspect to add. The key idea of copy-on-write is that when creating a fork, often we don't need all of the memory, especially since we often have a fork() followed by an exec() which will override all the files anyways. Instead, we can lazily allocate physical memory as needed. Some key components that went into the lab was (1) moving around the allocation logic, (2) keeping track of how many things were pointing to a VA to decide when to free it, and (3) making sure all other errors still returned. 

## 6.1010: Fundamentals of Programming

Overall, this class was pretty chill with labs usually taking me the afternoon to complete. Here are some of my favorite labs.

### LISP Interpreter

This was the capstone lab and quite fun. We were able to 

### N-D Mines

A fun recursive lab which required implementing the mines game in n-d. 

