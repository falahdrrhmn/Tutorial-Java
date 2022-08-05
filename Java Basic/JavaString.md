<div id="top" align="center">
  <h3 align="center">Java Basic</h3>
  <h1>Java Strings</h1>

  <p align="center">
    Menjelaskan basic Java Strings
    <br />
    <a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/README.md"><strong>Kembali ke menu utama »</strong></a>
    <br />
    <br />
    <a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/README.md">Java Basic</a>
    ·
    <a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20OOP/README.md">Java OOP</a>
    ·
    <a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Data%20Structure/README.md">Java Data Structure</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary id="list"><H3>List Materi Java Basic</H3></summary>
  <ol>
    <li>
      <a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/README.md">Java Basic</a>
      <ul>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/SejarahJava.md#top">Sejarah Java</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/SyntaxDasar.md">Syntax Dasar Hello World!</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/CommentsJava.md">Commant</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/VariablesJava.md">Variables</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/TipeData.md">Tipe Data</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/Casting.md">Casting</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/Operator.md">Operator</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/JavaString.md">Java String</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/JavaMath.md">Java Math</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/JavaIf-elseStatement.md">Java If-else Statement</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/JavaSwitchStatement.md">Java Switch Statement</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/Looping.md">Built looping</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/JavaArray.md">Java Array</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/JavaMethods.md">Java Methods</a></li>
      </ul>
    </li>
  </ol>
</details>

## Java Strings

Sebuah String di Java sebenarnya adalah sebuah objek, yang berisi metode yang dapat melakukan operasi tertentu pada string. Misalnya, panjang string dapat ditemukan dengan metode length() :
1. String.length
contohnya: 
```java
public class Main {
  public static void main(String[] args) {
    String txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
    System.out.println("The length of the txt string is: " + txt.length());
  }
}

output : 
The length of the txt string is: 26
```
2. More String Methods
There are many string methods available, for example toUpperCase() and toLowerCase():
```java
public class Main {
  public static void main(String[] args) {
    String txt = "Hello World";
    System.out.println(txt.toUpperCase());
    System.out.println(txt.toLowerCase());
  }
}

output:
HELLO WORLD
hello world
```



3. Finding a Character in a String
Metode indexOf() mengembalikan indeks (posisi) kemunculan pertama dari teks yang ditentukan dalam string (termasuk spasi):
contohnya: 
```java
public class Main {
  public static void main(String[] args) {
    String txt = "Please locate where 'locate' occurs!";
    System.out.println(txt.indexOf("locate"));
  }
}

output:
7
```

<br>

### String Concatenation

The + operator can be used between strings to combine them. This is called concatenation:
```java
public class Main {
  public static void main(String args[]) {
    String firstName = "John";
    String lastName = "Doe";
    System.out.println(firstName + " " + lastName);
  }
}

output:
John Doe
```

You can also use the concat() method to concatenate two strings:

```java
public class Main {
  public static void main(String[] args) {
    String firstName = "John ";
    String lastName = "Doe";
    System.out.println(firstName.concat(lastName));
  }
}

output:
John Doe
```
<br>

### Java Numbers and Strings

Java menggunakan operator + untuk penambahan dan penggabungan. Angka ditambahkan. String digabungkan
```java

int x = 10;
int y = 20;
int z = x + y;  // z will be 30 (an integer/number)

String x = "10";
String y = "20";
String z = x + y;  // z will be 1020 (a String)

```
If you add a number and a string, the result will be a string concatenation:
```java
String x = "10";
int y = 20;
String z = x + y;  // z will be 1020 (a String)
```

<br>

### Java Special Characters

<img width="563" alt="image" src="https://user-images.githubusercontent.com/92344349/182999723-f9c7e2cf-d928-4ba9-886f-d165f407dbbe.png">

The sequence \"  inserts a double quote in a string:
```java
public class Main {
  public static void main(String[] args) {
    String txt = "We are the so-called \"Vikings\" from the north.";
    System.out.println(txt);
  }
}

output:
We are the so-called "Vikings" from the north.
```

The sequence \"  inserts a double quote in a string:
```java
public class Main {
  public static void main(String[] args) {
    String txt = "It\'s alright.";
    System.out.println(txt);
  }
}

output:
It's alright.
```

The sequence \\  inserts a single backslash in a string:
```java
public class Main {
  public static void main(String[] args) {
    String txt = "The character \\ is called backslash.";
    System.out.println(txt);
  }
}

output:
The character \ is called backslash.
```

### Other common escape sequences that are valid in Java are:

<img width="585" alt="image" src="https://user-images.githubusercontent.com/92344349/182999898-0bebecc4-673b-4b69-a0ed-56c29d33f7b8.png">


<br>
<br>

<div align="center">
  <a href="#list">(Back to List)</a>
  ·
  <a href="#top">(Back to Top)</a>
</div>

<br>
<br>

<div align="center">
    Follow me!<br>
    <a href="https://bit.ly/3Qcg3s4">LinkedIn</a>
    ·
    <a href="https://bit.ly/3oRMMaA">Instagram</a>
    ·
    <a href="https://bit.ly/3zqrTrP">Youtube</a>
</div>

