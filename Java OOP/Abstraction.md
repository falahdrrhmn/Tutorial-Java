<div id="top" align="center">
  <h3 align="center">Java OOP</h3>
  <h1>Java Abstraction</h1>
  <p align="center">(Java Object Oriented Programming)</p>

  <p align="center">
    Menjelaskan Java Abstraction
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
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20OOP/ClassdanObject.md">Class dan Object</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20OOP/ClassMethods.md">Class Methods</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20OOP/Constructor.md">Constructor</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20OOP/Encapsulation.md">Encapsulation</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20OOP/Abstraction.md">Abstraction</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20OOP/Inheritance.md">Inheritance</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20OOP/Polymorphism.md">Polymorphism</a></li>
      </ul>
    </li>
  </ol>
</details>

# Abstract Classes and Methods

Abstraksi data adalah proses menyembunyikan detail tertentu dan hanya menampilkan informasi penting kepada pengguna.
Abstraksi dapat dicapai dengan kelas atau antarmuka abstrak (yang akan Anda pelajari lebih lanjut di bab berikutnya).

The abstract keyword is a non-access modifier, used for classes and methods:

1. Abstract class: is a restricted class that cannot be used to create objects (to access it, it must be inherited from another class).

2. Abstract method: can only be used in an abstract class, and it does not have a body. The body is provided by the subclass (inherited from).

An abstract class can have both abstract and regular methods:

contoh:
```java
// Abstract class
abstract class Animal {
  // Abstract method (does not have a body)
  public abstract void animalSound();
  // Regular method
  public void sleep() {
    System.out.println("Zzz");
  }
}

// Subclass (inherit from Animal)
class Pig extends Animal {
  public void animalSound() {
    // The body of animalSound() is provided here
    System.out.println("The pig says: wee wee");
  }
}

class Main {
  public static void main(String[] args) {
    Pig myPig = new Pig(); // Create a Pig object
    myPig.animalSound();
    myPig.sleep();
  }
}

output:
The pig says: wee wee
Zzz
```

Mengapa Dan Kapan Menggunakan Kelas dan Metode Abstrak?
Untuk mencapai keamanan - sembunyikan detail tertentu dan hanya tampilkan detail penting dari suatu objek.

Catatan: Abstraksi juga dapat dicapai dengan Antarmuka, yang akan Anda pelajari lebih lanjut di bab berikutnya.








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

