# kottans-backend

## Unix Shell
[kottans_frontend](https://github.com/webdevagent/kottans-frontend/blob/master/README.md)

## Git Collaboration
[kottans_frontend](https://github.com/webdevagent/kottans-frontend/blob/master/README.md)

## NodeJS Basics 1
![learnyounode](https://user-images.githubusercontent.com/44728742/64250385-a83c3f80-cf1e-11e9-9f1a-1df7ebd59074.png)

![functional](https://user-images.githubusercontent.com/44728742/64623040-f5be1e00-d3f0-11e9-80a3-c08afa6e812f.png)

![streams](https://user-images.githubusercontent.com/44728742/64699299-25caf700-d4ad-11e9-962c-62c131305aca.png)

Great resources that dive deep into nodejs, streams and functional programming. The coolest thing about this material that they help you to understand deeper more advanced topics.

## Memory Management

What's going to happen if program reaches maximum limit of stack ?
 If the maximum stack size has been reached, we have a stack overflow and the program receives a Segmentation Fault.
 
What's going to happen if program requests a big (more then 128KB) memory allocation on heap ?
 The heap is enlarged via the brk() system call (implementation) to make room for the requested block.
 
What's the difference between Text and Data memory segments ?
The data segment holds the contents for static variables initialized in source code and contaons all the the read/write data which is not 0-initialized.
The text segment is read-only and stores all of your code in addition to tidbits like string literals.
