---
layout: cv
title: yanrong cheng
email:
  url: mailto:yanrongcheng0@gmail.com
  text: yanrongcheng0@gmail.com
phone: 15000563410
  
---
# yanrong cheng
<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->
{% include cv-contact.html %}


## Profile
- I have over five years C/C++ development experience. I am very familiar with STL/C++11/c++17 feature and other C++ stuff. Besides C++ I also experienced with some scripts languages( eg. linux shell,Python and nodejs).
- Personally,I am very interested in some low level computer stuff,like compiler and VM. I also have written a toy C complier with C++ in my spare time,(https://github.com/xyanrch/Yan) which wrote from-scratch. I have implemented most of C98's feature except C language's pre-proccess. I also have a very popular repo in github called overplus(https://github.com/xyanrch/overplus).
- I'm also very passional in open soruce project, I also contributed my patch to SerenityOS's javascripts engine, SerenityOS is a posix like OS and has a win95's GUI.

## Education

### **Donghua University** `2013.9 -2016.3`

```
Shang Hai
```

- Master. in Software Engineering
- Computer Graphics

### **China University Of Petroleum** `2007.9 - 2011.12`

```
QingDao
```

- Bachelor of Engineering. in Computer Science

## Employment History
### **Senior Software Engineer at DellEMC**  `2021.8 - `
- Work in Dell VSA(virtual storage appliancestorage team
- Main work is:
- Main develop language is **C++ python bash perl**

### **Senior Software Engineer at Baidu**  `2020.9 - 2021.5`
- Work in Baidu input method core team
- Main work is:Baidu Input method SDK development which is used for multi platform(eg. Andrion/IOS/Windows/MacOs)
- Main develop language is **C++**

### **Software developer at CleNet Technologies** `2016.5- 2020.8`
- work as a consultant for **Ericsson packet core team**
- I mainly focus on **OAM area** which include **EBM(Event based monitor), UE Trace, Configure and Command** 
- Main develop language is **C++** and also use some scripts language 

## Project Experience
### **Baidu Input Method**
   Baidu Input Method is a very famous APP both in Andrion and IOS, which has 900 million users 
- **Baidu Input Method APP side black list development**`2021.3- 2017.5`
   - Description: When in cloud input, it is requried to get user's input context to cloud server, but when user's input context exists sensitive words, we need    forbid this behaviour. So we need a blacklist dict that contains some sensitive words, when the sentance hit the blacklist, we won't send the sentance to the  cloud server. 
  - My work: Coordinate with server sides guy, design protobuf message's formate. Write design documents and review with tech leader, write code and unit tests.
- **Baidu Input Method Calcutor feature development** `2021.2 - 2021.3`
  - Description: Check if user input context has valid expression, if has valid express, then eval the result. Support both binary express and unary express.
  - My work: Write design documents and review with tech leader, write code and unit tests.
  
- **Baidu Input Method User Trace Module and Wubi Module refactor**`2020.10 - 2021.2`
   - Add many unit test cases for code. re-design modules's architecture. 
   - For user trace module, I reimplement decode and encode mechanism, redefine trace message. make code more neat and stable.

### **Ericsson EPG(Ericcson Packet core Gateway)** `2016.5 - 2020.8`
  EPG is short for Ericsson Packet Gateway, which is also called PGW and SGW in **telecom filed**. Its custom include Verizon, CMCC and some other telecom operators. Its has first class stability and performance.
- **EBM and Ue trace feature development for SX interface** 
  - Description: Sx interface is the standard interface between PGWC/SGWC/SMF and Userplane, this interface is introduced in 5G. Sx interface's protocal is PFCP Message(https://en.wikipedia.org/wiki/PFCP) which is the standard 3GPP protocal. This feature's goal is tracing pfcp message for a given user or dump pfcp message in a defined format,encode the content and then sent to EBM server.
  - I was the main developer and my work is: write design document and review with DA and SM, write code and unit tests, cooridnate with FT and ST, Fix the bugs.
  - This feature  successfully delivered to the custom on time.
- **EPG Configuration framwork adpter for 5G**
  - Description: In 5G network, The main change is CUPS(Control plane and User plane Split), because of CUPS, EPG configuration also changed a lot, so legacy configure framework need do some adpter for CUPS.
  - I was the core developer in this feature and my main work is: write a tool(using Python) that can auto gennerated some default configure and apply the config.
   Write a tool that split the legacy configure into user plane and control plane.

- **EBM Frameowrk performance improvement**
    - Description: Using profiler tool to analyse the whole EBM system, find the improvement point and improve perfamence.
    - Finally system get a 10% performance improvement with my effort, System session creation peak rates improve frome 35w/s to 40w/s.
    
- **UE Trace and feature developmet for S2A/S2B interface**
    - Description: S2a/S2b is the standard 3GPP interface whose protocal is GTPV2 message,  This feature's goal is tracing pfcp message for a given user or dump pfcp message in a defined format,encode the content and then sent to EBM server.
    - My work: Cooperate with Europe guys, write design proposal and review with DA,PO, write code and unit test cases.


### **C Compiler development**  `2020.1 - now`
  - In spare time I also Like do something programming just for fun.I wrote the compiler from-scratch.
   compiler include front end and back end,The front end include a lexer  and a parser. The lexcer scan all chracheters and then generate tokens, the parser parse 
   tokens and generator AST which is the data struct of "program laguage". The back end main role is visiting AST and generating X86 assemble.  
  - I have implement most feature of C98, and also include a bunch of tests.
  - Code in github: https://github.com/chengchenwish/Yan   
  

## Technical Skill
- Proficiency in software development in **C/C++, Python, Nodejs, Linux shell, Perl**
- Familiar with development on **Linux and Windows**.
- Familiar with configuring and using **Git,K8s, docker, googletest, protobuf**.
- Experirened in **Agile development**


## Language
- **English**: CET6, Both good in verbal and writing


<!-- ### Footer

Last updated: May 2013 -->
