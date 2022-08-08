<div id="top" align="center">
  <h3 align="center">Java OOP</h3>
  <h1>Java Polymorphism</h1>
  <p align="center">(Java Object Oriented Programming)</p>

  <p align="center">
    Menjelaskan Java Polymorphism
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

# Java Polymorphism

Polimorfisme berarti "banyak bentuk", dan itu terjadi ketika kita memiliki banyak kelas yang terkait satu sama lain melalui pewarisan.

Seperti yang kami tentukan di bab sebelumnya; Warisan memungkinkan kita mewarisi atribut dan metode dari kelas lain. Polimorfisme menggunakan metode tersebut untuk melakukan tugas yang berbeda. Ini memungkinkan kita untuk melakukan satu tindakan dengan cara yang berbeda.

Misalnya, pikirkan superclass bernama Animal yang memiliki metode yang disebut animalSound(). Subkelas Hewan dapat berupa Babi, Kucing, Anjing, Burung - Dan mereka juga memiliki implementasi sendiri dari suara hewan (babi oinks, dan kucing mengeong, dll.):

```java
class Animal {
  public void animalSound() {
    System.out.println("The animal makes a sound");
  }
}

class Pig extends Animal {
  public void animalSound() {
    System.out.println("The pig says: wee wee");
  }
}

class Dog extends Animal {
  public void animalSound() {
    System.out.println("The dog says: bow wow");
  }
}

class Main {
  public static void main(String[] args) {
    Animal myAnimal = new Animal();
    Animal myPig = new Pig();
    Animal myDog = new Dog();
        
    myAnimal.animalSound();
    myPig.animalSound();
    myDog.animalSound();
  }
}

output:
The animal makes a sound
The pig says: wee wee
The dog says: bow wow
```

Ingat dari bab Inheritance bahwa kita menggunakan kata kunci extends untuk menghargai dari sebuah kelas.
Mengapa Dan Kapan Menggunakan "Warisan" dan "Polimorfisme"?
- Berguna untuk penggunaan kembali kode: menggunakan kembali atribut dan metode kelas yang ada saat Anda membuat kelas baru.




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

