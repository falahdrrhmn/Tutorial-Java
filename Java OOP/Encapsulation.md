<div id="top" align="center">
  <h3 align="center">Java OOP</h3>
  <h1>Java Encapsulation</h1>
  <p align="center">(Java Object Oriented Programming)</p>

  <p align="center">
    Menjelaskan Java Encapsulation
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





# Java Encapsulation

Tujuan enkapsulasi adalah memastikan bahwa data sensitif disembunyikan dari pengguna, dengan cara
1. Deklarasi class variables/attributes sebagai private
2. Menyediakan method get dan publik untuk mengakses dan memperbarui nilai private variabel 

### Get and Set

Private variabel hanya dapat diakses di dalam kelas yang sama (kelas luar tidak memiliki akses ke sana). Namun, dimungkinkan untuk mengaksesnya jika kita menyediakan method get dan set publik. contoh

Person.java
```java
public class Person {
   private String name;

   // Getter
   public String getName() {
     return name;
   }

   // Setter
   public void setName(String newName) {
     this.name = newName;
   }
}
```

Main.java
```java
public class Main {
  public static void main(String[] args) {
    Person myObj = new Person();
    myObj.setName("John");
    System.out.println(myObj.getName());
  }
}

output:
John
```

### Kenapa Menggunakan Enkapsulasi

1. Kontrol yang lebih baik dari atribut dan metode kelas
2. Atribut class dapat dibuat read-only (jika Anda hanya menggunakan metode get), atau write-only (jika Anda hanya menggunakan metode set)
3. Fleksibel: programmer dapat mengubah satu bagian dari kode tanpa mempengaruhi bagian lain
4. Peningkatan keamanan data




<br><br><br>






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

