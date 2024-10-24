# Programming: The Basics 

  Disclaimer: Parts of this text is written in a snarky, conversational tone. The snark isn't directed at anyone in particular, but if that isn't something you find humerous, this text isn't for you. I wrote it in this fashion because I want people to actually read it. Reading whitepapers, and text in that style, make me want to boil my eyes because of how dry it is. 

Even though this text is intended to give a more holistic, general overview of programming, it's written under the assumption the reader has some level of familiarty with programming. If you feel confident in your abilities to where I can describe a small problem and then you can implement some form of a solution, then that background should be enough to be able to take something away from this book.

## Language Families

Like spoken languages, programming languages have [language families](https://ccrma.stanford.edu/courses/250a-fall-2005/docs/ComputerLanguagesChart.png) -- as new languages pop up, they take influence from older ones and so will share large amounts of similarities between them. I'm categorizing the [more-mainstream](https://redmonk.com/sogrady/files/2024/09/lang.rank_.0624.wm_.png) languages into three primary families. Mainly based on syntax but that's not the only determinant. There are other more-obscure lists 

### C-descendants 

If you've programmed, you've probably done so in C or one if its descendants. It's important to note that most of the syntax of C is not unique to it -- C itself takes heavy inspiriation from B, BCPL, and ALGOL. However, none of it's predecessors are well-known and are rarely (if ever) used. C is the lingua franca of the programming world -- specifically the C ABI -- so I'm just going to call this family C-descendants. The largest contributing factor to C's dominance is probably UNIX. C was developed help develop the UNIX operating system which is the primary inspiration of the Linux operating system. All mainstream operating systems -- Linux, Windows, and Mac -- have massive portions of their codebase in C/C++.

C-descendants are highly discernable by their use of statments, curly braces, 

### LISP-descendants 

LISP, standing for LISt Processing, being just a few years younger than ALOGOL, is one of the oldest, high-level languages. LISP introduced ideas of garbage collection, dynamic typing, and higher-order functions. It's descendants (particularly Scheme) introduced things like proper* recursion.

  Here "proper" refers to tail-call optimized recursion. In more-sophisticated compiliers/interpreters, recursion is translated to the same instructions that loops are 

### ML-descendants

## Program Structure Paradigms

### Imperative vs Declarative

#### Imperative 

##### Procedural

##### Object Oriented

#### Declarative 

##### Functional

##### Relational

##### Logical

## Control Flow

### Iteration and Recursion

### Conditionals

### Error Handling

### Concurrency and Parallelism
