# Getting Started with TypeScript

## Terms

- **Dynamically-typed Languages**
- **IntelliSense**
- **Refactoring**
- **Source maps**
- **Statically-typed Languages**
- **Transpiling**
- **Type safety**

## What is Typescript

- **TypeScript is a super set of JavaScript.**
- **TypeScript builds on top of JavaScript.**
- **TypeScript code into plain JavaScript code using a TypeScript compiler.**

## Benefits of Typescript

![alt text](./src/assets/images/benefits.png?raw=true)

## Static Typing

- Programming languages divide into two categories: statically-typed and dynamicallytyped.

  ![alt text](./src/assets/images/statictyping.png?raw=true)

- In statically-typed languages (eg C++, C#, Java, etc), the type of variables is set atcompile-time and cannot change later.
- In dynamically-typed languages (eg Python, JavaScript, Ruby), the type of variables is determined at run-time and can change later.
- TypeScript is essentially JavaScript with static typing and some additional features that help us write more concise and robust code.
- Most IDEs and code editors supporting TypeScript provide incredible IntelliSense and auto-completion. So we get active hints as we code. A great productivity booster!
- By providing type information in our code, we get better refactoring support in most IDEs and code editors.
- Refactoring means changing the structure of the code without changing its behavior.
- With TypeScript we can catch more bugs at compile time.

## Drawback of Typescript

![alt text](./src/assets/images/drawbacks.png?raw=true)

## Typescript Compiler

- Browsers don’t understand TypeScript code. So we need to use the TypeScript compiler to compile and translate (or transpile) our TypeScript code into regular JavaScript for execution by browsers.

  ![alt text](./src/assets/images/compiler.png?raw=true)

## Preference for choosing language typescript or javascript

![alt text](./src/assets/images/ts-js.png?raw=true)

## Setting up the Development Enviroment

- Node software is required for running the typescript application in your machine
  - _URL_ : https://nodejs.org/en/
- After you need to install the typescript in your machine using following by the cli command
  - _npm i -g typescript_ : Installing typescript
  - _tsc -v_ : Checking typescript version
- Code Editor (IDE) Visual studio code
  - _URL_ : https://code.visualstudio.com/
