<div id="top" align="center">
  <h3 align="center">Java OOP</h3>
  <h1>Java Class Methods</h1>
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
### Java Class Attributes

Atribut itu panggilan buat variabel yang ada di dalam class, contoh

class Main punya attributes x dan y
```java
public class Main {
  int x = 5;
  int y = 3;
}
```
Selain attributes juga bisa dipanggil **fields**

### Mengakses Attributes

Mengakses atribut dengan membuat objek kelas, dan dengan menggunakan sintaks titik (.): 

gini contohnya

Buat objek bernama "myObj" dan cetak nilai x:

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

### Ubah Attributes

```java
public class Main {
  int x;

  public static void main(String[] args) {
    Main myObj = new Main();
    myObj.x = 40;
    System.out.println(myObj.x);
  }
}

output:
40
```

Atau ganti nilai yang ada:

```java
public class Main {
  int x = 10;

  public static void main(String[] args) {
    Main myObj = new Main();
    myObj.x = 25; // x is now 25
    System.out.println(myObj.x);
  }
}

output:
25
```

Jika Anda tidak ingin kemampuan untuk mengganti nilai yang ada, nyatakan atribut sebagai **final**:

```java
public class Main {
  final int x = 10;

  public static void main(String[] args) {
    Main myObj = new Main();
    myObj.x = 25; // will generate an error
    System.out.println(myObj.x); 
  }
}

output:
error
```

### Multiple Objects


Jika Anda membuat beberapa objek dari satu kelas, Anda dapat mengubah nilai atribut di satu objek, tanpa memengaruhi nilai atribut di objek lainnya:

```java
public class Main {
  int x = 5;

  public static void main(String[] args) {
    Main myObj1 = new Main();
    Main myObj2 = new Main();
    myObj2.x = 25;
    System.out.println(myObj1.x);
    System.out.println(myObj2.x);
  }
}

output:
5
25
```

### Multiple Attributes

Anda dapat menentukan atribut sebanyak yang Anda inginkan:

```java
public class Main {
  String fname = "John";
  String lname = "Doe";
  int age = 24;

  public static void main(String[] args) {
    Main myObj = new Main();
    System.out.println("Name: " + myObj.fname + " " + myObj.lname);
    System.out.println("Age: " + myObj.age);
  }
}

output:
Name: John Doe
Age: 24
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

