---
title: "! How to decode a bacon cipher"
draft: false
---

### Example Cipher:
**T**o en**co**de **a** mes**s**age e**ac**h letter **of** the **pl**a**i**nt**ex**t **i**s replaced b**y a g**rou**p of f**i**ve** o**f t**he l**et**te**rs 'A' or 'B'.**

.  

When *decoding*, replace each letter with an 'a' or '**b**'.  
'a' if the letter is standard, '**b**' if the letter is **bold**.  

### The example would look like this:
**b**a aa**bb**aa **b** aaa**b**aaa a**bb**a aaaaaa **bb** aaa **bb**a**b**aa**bb**a **b**a aaaaaaaa a**b** **b** **b**aaa**b** **bb** **b**a**bb** a**b** **b**aa a**bb**aa**bb** ‘**b**’ **bb** ‘**b**’.

### These letters are then grouped together in fives like this:
**b**aaa**b**(S) **b**aa**b**a(T) aa**b**aa(E) aa**bb**a(G) aaaaa(A) a**bb**aa(N) a**bb**a**b**(O) aa**bb**a(G) **b**aaaa(R) aaaaa(A) a**bbb**a(P) aa**bbb**(H) **b**a**bb**a(Y) **bb**aaa **bb**aa**b** **bbbbb**

Each group of five letters corresponds to a letter in the table below.  
So the example decoded message is *'steganography'*.  

(where the last three groups | **bb**aaa **bb**aa**b** **bbbbb** |, being unintelligible, are assumed not to form part of the message.)

| Letter | Code  |  | Letter | Code |
|:-------|:-----:|:--:|:------:|------:|
| A      | aaaaa |  | N      | a**bb**a**b** |
| B      | aaaa**b** |  | O      | a**bbb**a |
| C      | aaa**b**a |  | P      | a**bbbb** |
| D      | aaa**bb** |  | Q      | **b**aaaa |
| E      | aa**b**aa |  | R      | **b**aaa**b** |
| F      | aa**b**a**b** |  | S      | **b**aa**b**a |
| G      | aa**bb**a |  | T      | **b**aa**bb** |
| H      | aa**bbb** |  | U      | **b**a**b**aa |
| I      | a**b**aaa |  | V      | **b**a**b**a**b** |
| J      | a**b**aa**b** |  | W      | **b**a**bb**a |
| K      | a**b**a**b**a |  | X      | **b**a**bbb** |
| L      | a**b**a**bb** |  | Y      | **bb**aaa |
| M      | a**bb**aa |  | Z      | **bb**aa**b** |
