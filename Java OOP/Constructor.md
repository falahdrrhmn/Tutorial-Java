<div id="top" align="center">
  <h3 align="center">Java OOP</h3>
  <h1>Java Constructors</h1>
  <p align="center">(Java Object Oriented Programming)</p>

  <p align="center">
    Menjelaskan Java Constructors
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
  <summary id="list"><H3>List Materi Java OOP</H3></summary>
  <ol>
    <li>
      <a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20OOP/README.md">Java OOP</a>
      <ul>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20OOP/DasarOOP.md">Dasar OOP</a></li>
        <li><a href="#installation">Class dan Object</a></li>
        <li><a href="#built-with">Class Methods</a></li>
        <li><a href="#built-with">Constructor</a></li>
        <li><a href="#built-with">Encapsulation</a></li>
        <li><a href="#built-with">Abstraction</a></li>
        <li><a href="#built-with">Inheritance</a></li>
        <li><a href="#built-with">Polymorphism</a></li>
      </ul>
    </li>
  </ol>
</details>

# Penjelasan Singkat Method pada Materi sebelumnya

Method di class sebelumnya ada 2, yakni method void (yg gada return value) sama method biasa

Method tanpa return value
```java
public class Main {
  static void myMethod(String fname, int age) {
    System.out.println(fname + " is " + age);
  }

  public static void main(String[] args) {
    myMethod("Liam", 5);
    myMethod("Jenny", 8);
    myMethod("Anja", 31);
  }
}

output: 
Liam is 5
Jenny is 8
Anja is 31

```
When a parameter is passed to the method, it is called an argument. So, from the example above: fname is a parameter, while Liam, Jenny and Anja are arguments.

public, private, default, protected itu access modifier

Method dengan return value
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

output:
8
```

<br><br><br>

# Method Static vs. Non-Static

Singkatnya Ada Method static dan metode non-static (public). bedanya apa? Kalo static bisa diakses tanpa perlu buat object class, beda sama public yang hanya bisa diakses oleh object. contoh:

```java
public class Main {
  // Static method
  static void myStaticMethod() {
    System.out.println("Static methods can be called without creating objects");
  }

  // Public method
  public void myPublicMethod() {
    System.out.println("Public methods must be called by creating objects");
  }

  // Main method
  public static void main(String[] args) {
    myStaticMethod(); // Call the static method

    Main myObj = new Main(); // Create an object of MyClass
    myObj.myPublicMethod(); // Call the public method
  }
}

output:
Static methods can be called without creating objects
Public methods must be called by creating objects
```
<br><br><br>

# Access Methods With an Object

contoh
```java
// Create a Main class
public class Main {
 
  // Create a fullThrottle() method
  public void fullThrottle() {
    System.out.println("The car is going as fast as it can!");
  }

  // Create a speed() method and add a parameter
  public void speed(int maxSpeed) {
    System.out.println("Max speed is: " + maxSpeed);
  }

  // Inside main, call the methods on the myCar object
  public static void main(String[] args) {
    Main myCar = new Main();     // Create a myCar object
    myCar.fullThrottle();      // Call the fullThrottle() method
    myCar.speed(200);          // Call the speed() method
  }
}

output:
The car is going as fast as it can!
Max speed is: 200
```

Penjelasan:
1) Membuat kelas Utama dengan nama Main

2) Membuat metohod fullThrottle() dan speed() di kelas Main.

3) Metode fullThrottle() dan metode speed() akan mencetak beberapa teks, saat dipanggil.

4) Metode speed() menerima parameter int yang disebut maxSpeed - kita akan menggunakan ini di 8).

5) Untuk menggunakan kelas Utama dan metodenya, kita perlu membuat objek dari Kelas Utama.

6) Kemudian, masuk ke metode main(), yang Anda tahu sekarang adalah metode Java bawaan yang menjalankan program Anda (kode apa pun di dalam main dieksekusi).

7) Dengan menggunakan kata kunci baru kami membuat objek dengan nama myCar.

8) Kemudian, kita memanggil metode fullThrottle() dan speed() pada objek myCar, dan menjalankan program menggunakan nama objek (myCar), diikuti dengan titik (.), diikuti dengan nama metode ( fullThrottle(); dan kecepatan(200);). Perhatikan bahwa kita menambahkan parameter int 200 di dalam metode speed().


<br><br><br>


# Menggunakan Multiple Class

Main.java

```java
public class Main {
  public void fullThrottle() {
    System.out.println("The car is going as fast as it can!");
  }

  public void speed(int maxSpeed) {
    System.out.println("Max speed is: " + maxSpeed);
  }
}
```

Second.java

```java
class Second {
  public static void main(String[] args) {
    Main myCar = new Main();     // Create a myCar object
    myCar.fullThrottle();      // Call the fullThrottle() method
    myCar.speed(200);          // Call the speed() method
  }
}

output:
The car is going as fast as it can!
Max speed is: 200
```








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

