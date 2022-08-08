<div id="top" align="center">
  <h3 align="center">Java OOP</h3>
  <h1>Dasar Java OOP</h1>
  <p align="center">(Java Object Oriented Programming)</p>

  <p align="center">
    Menjelaskan basic Java OOP
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

# Penjelasan Singkat Java OOP

Di OOP ada yang anmanya class dan object, singkatnya gini

<img width="565" alt="image" src="https://user-images.githubusercontent.com/92344349/183319757-5c862177-0276-4cdc-99b8-adf7633233f7.png">

Kenapa harus OOP? kelebihan OOP dibanding pemrograman prosedural atau yang biasa 
1. OOP lebih cepat dan lebih mudah untuk dieksekusi
2. OOP menyediakan struktur yang jelas untuk program
3. OOP membantu menjaga kode Java KERING "Jangan Ulangi Sendiri", dan membuat kode lebih mudah untuk dipelihara, dimodifikasi, dan di-debug
4. OOP memungkinkan untuk membuat aplikasi penuh yang dapat digunakan kembali dengan lebih sedikit kode dan waktu pengembangan yang lebih singkat

<br><br><br>

# Class & Object

Java adalah bahasa pemrograman berorientasi objek.
Dalam kehidupan nyata, mobil adalah sebuah objek. Mobil memiliki atribut, seperti berat dan warna, dan metode, seperti drive dan rem.

## Cara membuat Kelas

cara buat class ketik **class** terus kasi nama kelas, kayak gini contohnya

```java
public class contohClass {
  int x = 10;
}
```

Kelas itu sama aja kayak class dari yang sebelumnya udah dibuat

di java object dibuat dari sebuah class, gini contohnya 

```java
public class Main {
  int x = 5;

  public static void main(String[] args) {
    Main myObj = new Main();
    System.out.println(myObj.x);
  }
}

output:
5
```

### Multiple Object

Di java object bisa dipanggil berkali2, contoh

```java
public class Main {
  int x = 5;

  public static void main(String[] args) {
    Main myObj1 = new Main();
    Main myObj2 = new Main();
    System.out.println(myObj1.x);
    System.out.println(myObj2.x);
  }
}public class Main {
  int x = 5;

  public static void main(String[] args) {
    Main myObj1 = new Main();
    Main myObj2 = new Main();
    System.out.println(myObj1.x);
    System.out.println(myObj2.x);
  }
}

output: 
5
5
```

### Multiple Class

Kita bisa bikin object class & diakses di class lain, cara ini sering digunakan untuk organisasi kelas yang lebih baik (satu kelas memiliki semua atribut dan metode, sedangkan kelas lainnya memegang metode main() (kode yang akan dieksekusi)). contoh

Main.java
```java
public class Main {
  int x = 5;
}
```

Second.java
```java
class Second {
  public static void main(String[] args) {
    Main myObj = new Main();
    System.out.println(myObj.x);
  }
}

output:
5
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

