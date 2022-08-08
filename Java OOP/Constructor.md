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

# Java Constructors

Konstruktor di Java adalah metode khusus yang digunakan untuk menginisialisasi objek. Konstruktor dipanggil ketika objek kelas dibuat. Ini dapat digunakan untuk menetapkan nilai awal untuk atribut objek:

contoh:
```java
// Create a Main class
public class Main {
  int x;

  // Create a class constructor for the Main class
  public Main() {
    x = 5;
  }

  public static void main(String[] args) {
    Main myObj = new Main();
    System.out.println(myObj.x);
  }
}

output:
5
```

Constuctor harus sesuai dengan namanya, constructor dipanggil saat object dibuat. 

Semua kelas memiliki konstruktor secara default: jika Anda tidak membuat konstruktor kelas sendiri, Java akan membuatnya untuk Anda. Namun, Anda tidak dapat menetapkan nilai awal untuk atribut objek.

<br><br><br>

# Constructor Parameters
```java
public class Main {
  int x;

  public Main(int y) {
    x = y;
  }

  public static void main(String[] args) {
    Main myObj = new Main(5);
    System.out.println(myObj.x);
  }
}

output:
5
```

You can have as many parameters as you want:

```java
public class Main {
  int modelYear;
  String modelName;

  public Main(int year, String name) {
    modelYear = year;
    modelName = name;
  }

  public static void main(String[] args) {
    Main myCar = new Main(1969, "Mustang");
    System.out.println(myCar.modelYear + " " + myCar.modelName);
  }
}

output:
1969 Mustang
```



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

