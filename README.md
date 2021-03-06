# Atom Java Snippets

> A collection of Java commands for optimizing modern Java development productivity.

![](https://raw.githubusercontent.com/cliffordfajardo/atom-java-snippets/master/atom-java-snippets-demo.gif)

![The MIT License](https://img.shields.io/npm/l/express.svg)
[![apm](https://img.shields.io/apm/v/atom-java-snippets.svg?style=flat-square)](https://atom.io/packages/atom-java-snippets)
[![apm](https://img.shields.io/apm/dm/atom-java-snippets.svg?style=flat-square)](https://atom.io/packages/atom-java-snippets)




### Install

```shell
apm install atom-java-snippets
```









### Contributing/Suggestions

Feel free to let me know ([link](https://github.com/cliffordfajardo/atom-java-snippets/issues)) what else can be improved/added or you can also submit a PR.










### Snippets Overview

Snippets are optimized to be short and easy to remember. Some snippets are "chainable" and render differently when preceded by a ".".

<!-- For example, `.fe` renders a chain-friendly version of the forEach snippet, while `fe` renders a full code block. -->

- [Control Flow](#Control Flow Snippets)
- [Classes](#Class Related Snippets)
- [Java Doc Comments](#Java Doc Comments Snippets)
- [Miscellaneous](#Miscellaneous)
- [Return Values](#Returning Values Snippets)
- [Types](#Type Snippets)










#### Control Flow Snippets

##### `if⇥` if statement
```java
if(${1:condition}) {
  ${2}
}$3
```

##### `else⇥` else statement
```java
else {
  ${1}
}$2
```

##### `ifelse⇥` if else statement
```java
if(${1:condition}) {
  ${2}
} else {
  ${3}
}$4
```

##### `elseif⇥` else if statement
```java
else if (${1:condition}) {
  ${2}
}${3}
```

##### `for⇥` for loop
```java
for (Integer ${1:i} = 0; ${1:i} < ${2:iterable}${3:.length}; ${1:i}++) {
  ${4}
}${5}
```

##### `fore⇥` iterator based for each loop
```java
for(${1:object_type} ${2:var_name}: ${3:collection_name}) {
  ${4:var_name}
}$5
```

##### `while⇥` while loop
```java
while (${1:condition}) {
  ${2}
}$3
```

##### `trycatch⇥` try/catch
```java
try {
  ${1}
} catch(Exception ${2:exception_name}) {
  ${2:exception_name}
}$3
```

##### `tryfinally⇥` try/finally
```java
try {
  ${1}
} finally {
  ${2}
}$3
```

##### `trycatchfinally⇥` try/catch/finally
```java
try {
  ${1}
} catch(Exception ${2:exception_name}) {
  ${2:exception_name}
} finally {
  ${3}
}${4}
```










### Class Related Snippets

##### `class` class and constructor
```java
${1:public} class ${2:ClassName} {
  ${0}
}$0
```

##### `classAndConstructor⇥` class and constructor
```java
${1:public_or_private} class ${2:ClassName} {
  ${3:public_or_private} ${2:ClassName} (${4:Parameters}) {
    ${5}
  }
}
```

##### `constructorPublic⇥` public class constructor

```java
${1:public} ${2:ClassName} (${3:Parameters}) {
  ${4}
}$5
```

##### `constructorPrivate⇥` private class constructor

```java
${1:private} ${2:ClassName} (${3:Parameters}) {
  ${4}
}$5
```

##### `methodPublic⇥` public method

```java
${1:public} ${2:ClassName} (${3:Parameters}) {
  ${4}
}$5
```

##### `methodPrivate⇥` private method

```java
${1:private} ${2:ClassName} (${3:Parameters}) {
  ${4}
}$5
```

##### `methodStatic⇥` static method

```java
${1:public_or_private} static ${2:ClassName} (${3:Parameters}) {
  ${4}
}$5
```










### Java Doc Comments Snippets

##### `commentMethod⇥` java doc method comment

```java
/**
 * @description your_method_description
 * @param param_name your_param_description
 * @return return_type your_return_description
 **/$1
```

##### `commentModule⇥` java doc module comment

```java
/**
* The ____ program implements/is used for.....
*
* @author
*/
```










### Miscellaneous

##### `print⇥` System.out.println

```java
System.out.println(${1});$2
```










### Returning Values Snippets

##### `r⇥` return
```java
return ${1};${2}
```

##### `rt⇥` return true
```java
return true;
```

##### `rf⇥` return false
```java
return false;
```

##### `rth⇥` return this
```java
return this;
```

##### `rn⇥` return null
```java
return null;
```

##### `r0⇥` return 0
```java
return 0;
```

##### `r1⇥` return 1
```java
return -1;
```

##### `r-1⇥` return -1
```java
return -1;
```










### Contact Me
- [@twitter/cliffordfajard0](https://twitter.com/cliffordfajard0)
- [@github/cliffordfajardo](https://github.com/cliffordfajardo/)











### Credits
- [Idleberg](https://atom.io/users/cliffordfajardo/) for his [Atomizer](https://atom.io/packages/atomizr) package that helped me convert Sublime snippets into Atom's format.
