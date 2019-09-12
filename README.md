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

```
55b2c0584000-55b2c058c000 r-xp 00000000 08:01 9437209                    /bin/cat
55b2c078b000-55b2c078c000 r--p 00007000 08:01 9437209                    /bin/cat
55b2c078c000-55b2c078d000 rw-p 00008000 08:01 9437209                    /bin/cat
55b2c1708000-55b2c1729000 rw-p 00000000 00:00 0                          [heap]
7f545f7f0000-7f54601bf000 r--p 00000000 08:01 13245079                   /usr/lib/locale/locale-archive
7f54601bf000-7f54603a6000 r-xp 00000000 08:01 11408068                   /lib/x86_64-linux-gnu/libc-2.27.so
7f54603a6000-7f54605a6000 ---p 001e7000 08:01 11408068                   /lib/x86_64-linux-gnu/libc-2.27.so
7f54605a6000-7f54605aa000 r--p 001e7000 08:01 11408068                   /lib/x86_64-linux-gnu/libc-2.27.so
7f54605aa000-7f54605ac000 rw-p 001eb000 08:01 11408068                   /lib/x86_64-linux-gnu/libc-2.27.so
7f54605ac000-7f54605b0000 rw-p 00000000 00:00 0 
7f54605b0000-7f54605d7000 r-xp 00000000 08:01 11408040                   /lib/x86_64-linux-gnu/ld-2.27.so
7f546079e000-7f54607c2000 rw-p 00000000 00:00 0 
7f54607d7000-7f54607d8000 r--p 00027000 08:01 11408040                   /lib/x86_64-linux-gnu/ld-2.27.so
7f54607d8000-7f54607d9000 rw-p 00028000 08:01 11408040                   /lib/x86_64-linux-gnu/ld-2.27.so
7f54607d9000-7f54607da000 rw-p 00000000 00:00 0 
7ffc92dee000-7ffc92e0f000 rw-p 00000000 00:00 0                          [stack]
7ffc92f10000-7ffc92f13000 r--p 00000000 00:00 0                          [vvar]
7ffc92f13000-7ffc92f14000 r-xp 00000000 00:00 0                          [vdso]
ffffffffff600000-ffffffffff601000 r-xp 00000000 00:00 0                  [vsyscall]
```
Heap - 55b2c1708000-55b2c1729000,  
Stack - 7ffc92dee000-7ffc92e0f000,  
MMS - 7f54601bf000-7f54603a6000  

Awesome learning resources and subtasks.  A lot of useful info about stack, heap, data and text segments. Also, those subtasks upgrade your OS knowledge.  
