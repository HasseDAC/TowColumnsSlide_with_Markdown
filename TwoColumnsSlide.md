---
# configration for marp
# marpの設定
# https://marp.app/
marp: true
paginate: true # add page numbers on the below of the slides
size: 16:9
---
<!-- Styles for 2Column -->
<!-- 2Column用スタイル -->
<style>
.column-left{
  width: 48.5%;
  float: left;
  text-align: left;
}
.column-right{
  width: 48.5%;
  float: right;
  text-align: left;
}
.column-one{
  float: left;
  width: 100%;
  text-align: left;
}
</style>

<!-- Below is a sample article -->
<!-- 以下サンプル記事 -->
<!-- 

Add next page with "---"
"---"で次ページ追加

 -->

# Slide Title
Your Name



---
# Contents
- What is C#
- Data type
- Variable declaration
- Four arithmetic operations
- Incremnt and Decrement
- if, while, for

---
# What is C#
It is a programming language created by a Microsoft team in 2000.
[Documentation](https://docs.microsoft.com/ja-jp/dotnet/csharp/ "https://docs.microsoft.com/ja-jp/dotnet/csharp/")
### Main Use
- Creation of Windows applications
- Programming in Unity (Creation of games, smartphone apps, AR and XR apps)
  
### Features
- Static typing language
- object-oriented language. (Look it up if you're curious.)

---
## Let's display "Hello World!"
Let's display "Hello World!"
The following is a program to display a string in C#. Let's try it out.
<div class="column-one">
<div class="column-left">

### MyApp.cs

```C#
using System;

class MyApp{

    static void Main(){

        Console.WriteLine("Hello World!");

    }

}
```

</div>
</div>

---
## Let's display "Hello World!"
<div class="column-one">
<div class="column-left">

### MyApp.cs

```C#
using System;

class MyApp{

    static void Main(){

    // Inside the round brackets, "any text"
        Console.WriteLine("Hello World!");

    }
  
}
```


</div>

<div class="column-right">

### Execution Result

```
Hello World!

```
</div>
</div>

`using System` is for calling basic C# functions. The `class Test{}` and `static void Main(){}` in it must be written or an error will occur.
Use `Console.WriteLine()` to output characters in C#. (This is also one of the fuction of `System`.) Note that C# is case-sensitive for alphabetic characters. Make no mistake!

---
## Comparison

<div class="column-one">
<div class="column-left">

### Image1

<img src="img/sample.png">

</div>

<div class="column-right">

### Image2

<img src="img/sample.png">

</div>
</div>

