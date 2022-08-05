<div id="top" align="center">
  <h3 align="center">Java Basic</h3>
  <h1>Java Methods</h1>

  <p align="center">
    Menjelaskan basic Java Methods
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

## Java Methods
```
A method is a block of code which only runs when it is called.
You can pass data (meneruskan atau memasukan), known as parameters, into a method.
Methods are used to perform certain actions(melakukan beberapa aksi), and they are also known as functions.
Why use methods? To reuse code: define the code once, and use it many times.

Sebuah metode harus dideklarasikan di dalam sebuah kelas. Itu didefinisikan dengan nama metode, diikuti oleh tanda kurung (). Java menyediakan beberapa metode yang telah ditentukan sebelumnya, seperti System.out.println(), tetapi Anda juga dapat membuat metode sendiri untuk melakukan tindakan tertentu:
```

Contoh membuat method dalam kelas main
```java
public class Main {
  static void myMethod() {
    // code to be executed
  }
}
```

```
Penjelasan method
myMethod() is the name of the method
static means that the method belongs to the Main class and not an object of the Main class. You will learn more about objects and how to access methods through objects later in this tutorial. (static berarti bahwa metode tersebut milik kelas Utama dan bukan objek dari kelas Utama. Anda akan mempelajari lebih lanjut tentang objek dan cara mengakses metode melalui objek nanti dalam tutorial ini.)
void means that this method does not have a return value. You will learn more about return values later in this chapter-
```

Call a Method (memanggil method)

```java
public class Main {
  static void myMethod() {
    System.out.println("I just got executed!");
  }

  public static void main(String[] args) {
    myMethod();
  }
}

// Outputs "I just got executed!"
```
<br><br><br>

### Java Methods Parameter
```
Parameters and Arguments
Informasi dapat diteruskan ke metode sebagai parameter. Parameter bertindak sebagai variabel di dalam metode.
Parameter ditentukan setelah nama metode, di dalam tanda kurung. Anda dapat menambahkan parameter sebanyak yang Anda inginkan, cukup pisahkan dengan koma.
```

Contoh parameter dalam method

```java
public class Main {
  static void myMethod(String fname) {
    System.out.println(fname + " Refsnes");
  }

  public static void main(String[] args) {
    myMethod("Liam");
    myMethod("Jenny");
    myMethod("Anja");
  }
}

output:
Liam Refsnes
Jenny Refsnes
Anja Refsnes
```

Multiple Parameters 
You can have as many parameters as you like:

```java
public class Main {
  static void myMethod(String fname, int ageString fname, int age) {
    System.out.println(fname + " is " + age);
  }

  public static void main(String[] args) {
    myMethod("Liam", 5);
    myMethod("Jenny", 8);
    myMethod("Anja", 31);
  }
}

// Liam is 5
// Jenny is 8
// Anja is 31
```

Return Values
The void keyword, used in the examples above, indicates that the method should not return a value. If you want the method to return a value, you can use a primitive data type (such as int, char, etc.) instead of void, and use the return keyword inside the method:

```java
public class Main {
  static int myMethod(int x) {
    return 5 + x;
  }

  public static void main(String[] args) {
    System.out.println(myMethod(3));
  }
}
// Outputs 8 (5 + 3)
```

This example returns the sum of a method's two parameters:

```java
public class Main {
  static int myMethod(int x, int y) {
    return x + y;
  }

  public static void main(String[] args) {
    System.out.println(myMethod(5, 3));
  }
}
// Outputs 8 (5 + 3)
```
You can also store the result in a variable (recommended, as it is easier to read and maintain):

```java
public class Main {
  static int myMethod(int x, int y) {
    return x + y;
  }

  public static void main(String[] args) {
    int z = myMethod(5, 3);
    System.out.println(z);
  }
}
// Outputs 8 (5 + 3)
```

It is common to use if...else statements inside methods:

```java
public class Main {

  // Create a checkAge() method with an integer variable called age
  static void checkAge(int age) {

    // If age is less than 18, print "access denied"
    if (age < 18) {
      System.out.println("Access denied - You are not old enough!");

    // If age is greater than, or equal to, 18, print "access granted"
    } else {
      System.out.println("Access granted - You are old enough!");
    }
  }

  public static void main(String[] args) {
    checkAge(20); // Call the checkAge method and pass along an age of 20
  }
}

// Outputs "Access granted - You are old enough!"
```

<br><br><br>

### Java Methods Overloading

Dengan metode overloading, beberapa metode dapat memiliki nama yang sama dengan parameter yang berbeda:

Perhatikan contoh berikut, yang memiliki dua metode yang menambahkan nomor dari jenis yang berbeda:

```java
public class Main {
  static int plusMethodInt(int x, int y) {
    return x + y;
  }
  
  static double plusMethodDouble(double x, double y) {
    return x + y;
  }
  
  public static void main(String[] args) {
    int myNum1 = plusMethodInt(8, 5);
    double myNum2 = plusMethodDouble(4.3, 6.26);
    System.out.println("int: " + myNum1);
    System.out.println("double: " + myNum2);
  }
}

output:
int: 13
double: 10.559999999999999
```

Daripada mendefinisikan dua metode yang seharusnya melakukan hal yang sama, lebih baik membebani satu metode.
Pada contoh di bawah ini, kami membebani metode plusMethod agar berfungsi baik untuk int maupun double:

Contoh parameter dalam method

```java
static int plusMethod(int x, int y) {
  return x + y;
}

static double plusMethod(double x, double y) {
  return x + y;
}

public static void main(String[] args) {
  int myNum1 = plusMethod(8, 5);
  double myNum2 = plusMethod(4.3, 6.26);
  System.out.println("int: " + myNum1);
  System.out.println("double: " + myNum2);
}
```

```java
  public static void main(String[] args) {
    checkAge(20); // Call the checkAge method and pass along an age of 20
  }
}

// Outputs "Access granted - You are old enough!"
```

Note: Multiple methods can have the same name as long as the number and/or type of parameters are different.

<br><br><br>

### Java Scope

Di Java, variabel hanya dapat diakses di dalam wilayah tempat mereka dibuat. Ini disebut ruang lingkup (Scope).

1. Method Scope <br>
Variables declared directly inside a method are available anywhere in the method following the line of code in which they were declared: (Variabel yang dideklarasikan langsung di dalam suatu metode tersedia di mana saja dalam metode yang mengikuti baris kode di mana mereka dideklarasikan):

```java
public class Main {
  public static void main(String[] args) {

    // gabisa make x dikode bagian sini

    int x = 100;

    // bisa make x dikode bagian sini
    System.out.println(x);
  }
}
```

2. Block Scope<br>
A block of code refers to all of the code between curly braces {}.<br>
Variables declared inside blocks of code are only accessible by the code between the curly braces, which follows the line in which the variable was declared (Blok kode merujuk ke semua kode di antara kurung kurawal {}.<br>
Variabel yang dideklarasikan di dalam blok kode hanya dapat diakses oleh kode di antara kurung kurawal, yang mengikuti baris di mana variabel dideklarasikan):
contoh
```java
public class Main {
  public static void main(String[] args) {

    // Code here CANNOT use x

    { // This is a block

      // Code here CANNOT use x

      int x = 100;

      // Code here CAN use x
      System.out.println(x);

   } // The block ends here

  // Code here CANNOT use x
  
  }
}

output:
100
```

A block of code may exist on its own or it can belong to an if, while or for statement. In the case of for statements, variables declared in the statement itself are also available inside the block's scope.

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

