# Typescript
## Table of Contents

- [What Is TypeScript?](#what-is-typescript)
- [Components of TypeScript](#components-of-typescript)
- [The Gaps in JavaScript](#the-gaps-in-javascript)
- [How TypeScript Fills in JavaScript’s Gaps](#how-typescript-fills-in-javascripts-gaps)
- [How to Get Started with TypeScript](#how-to-get-started-with-typescript)

## What Is TypeScript?
**TypeScript** is a strongly typed, object-oriented, compiled programming language** that builds on JavaScript. It is a superset of the JavaScript language, designed to give you better tooling at any scale.
TypeScript calls itself **“JavaScript with syntax for types.”** In short, it is JavaScript with some additional features.
<hr>

## Components of TypeScript

**TypeScript comprises three main components:**

1. **Language:** the syntax, keywords, and type annotations.
2. **The TypeScript Compiler (TSC):** converts the instructions written in TypeScript to its JavaScript equivalent.
3. **The TypeScript Language Service:** an additional layer of editor-like applications, such as statement completion, signature help, code formatting, and colorization, among other things.
<hr>

## The Gaps in JavaScript

JavaScript remains a loosely typed language, which can be inhibiting in and of itself. With function parameters and variables offering little to no information, developers are often left fumbling in the dark trying to determine what types of data are being passed where in JavaScript. They either have to waste time looking at the documentation or — in worst cases — simply do their best to guess based on the implementation.
<hr>

## How TypeScript Fills in JavaScript’s Gaps

As a strongly typed programming language that builds on JavaScript, TypeScript’s mission is to step in and fill these gaps to enable application-scale development better.
- **Enhanced IDE Support**

this is largely due to the improved IDE (integrated development environment) support brought by TypeScript, where the TypeScript compiler informs the IDE on rich type information in real-time.

This facilitates several advantages for the user.

For one, it’s easier to catch errors. While coding, compilation errors are identified with a red line directly in the IDE. And when you have questions about what functions a library might offer, you can get inline help, thanks to code completion. This streamlines workflow, as you no longer need to stop and seek help from external, online references.
This enhanced IDE support boosts overall user productivity.

- **Static Typing and Type Inference**
JavaScript is dynamically typed. In other words, until a variable is instantiated at runtime, JavaScript cannot know what type it is.

But in some scenarios, this may be too late. And if a variable is falsely assumed to be a certain type, this can cause significant bugs.

This is another area where TypeScript adds support for the loosely typed JavaScript.

With TLS (the TypeScript Language Service mentioned above), TypeScript has an optional static typing and type inference system that can infer undeclared variables. Thus, by adding type support to JavaScript, TypeScript can effectively mitigate type errors during compilation to JavaScript.

- **ECMAScript Features**

While the JavaScript language is standardized through the ECMAScript standards, not all browsers and JavaScript runtimes support all ECMAScript standards.

This is where TypeScript steps in to make the difference, helping users access the future of JavaScript — today. Because with TypeScript, developers can use many of the latest ECMAScript features (e.g., modules, lambda functions, classes, the spreader operator, and destructing) even before web browsers or other environments fully support them.

Moreover, the language allows users to translate ECMAScript features to older ECMAScript targets of their choosing. This gives the ability to safely use new features while always having the assurance to remain backward compatible with older browsers and JavaScript runtimes.

- **Object Oriented Programming**

Finally, unlike JavaScript, which has yet failed to embrace object-oriented programming, TypeScript supports object-oriented programming concepts in the vein of classes, interfaces, and inheritance.

## How to Get Started with TypeScript

**The most common way to get started with TypeScript for first time**
1. Install nodejs
2. install Typescript ```npm install -g typescript```
3. Install Code Editor Like Vscode
4. Write the TypeScript code.
5. Then, use TSC to compile the TypeScript code into plain JavaScript code.
6. Finally, deploy the JavaScript code to any environment that runs JavaScript.