---
layout: archive
title: "Java Identifiers"
excerpt: "Java identifiers"
tags: [Java]
last_modified_at: 2018-01-15T20:20:16-05:00
author_profile: true
toc: true
---

# Rules for defining Java Identifiers

There are certain rules for defining a valid java identifier. These rules must be followed, otherwise we get compile-time error. These rules are also valid for other languages like C,C++.

1. The only allowed characters for identifiers are all alphanumeric characters([A-Z],[a-z],[0-9]), ‘$‘(dollar sign) and ‘_‘ (underscore).For example “geek@” is not a valid java identifier as it contain ‘@’ special character.
2. Identifiers should not start with digits([0-9]). For example “123geeks” is a not a valid java identifier.
3. Java identifiers are case-sensitive.
4. There is no limit on the length of the identifier but it is advisable to use an optimum length of 4 – 15 letters only.
5. Reserved Words can’t be used as an identifier. For example “int while = 20;” is an invalid statement as while is a reserved word. There are 53 reserved words in Java.

### Examples of valid identifiers :

```java
MyVariable
MYVARIABLE
myvariable
x
i
x1
i1
_myvariable
$myvariable
sum_of_array
geeks123
```
### Examples of invalid identifiers :

```java
My Variable  // contains a space
123geeks   // Begins with a digit
a+c // plus sign is not an alphanumeric character
variable-2 // hyphen is not an alphanumeric character
sum_&_difference // ampersand is not an alphanumeric character
```