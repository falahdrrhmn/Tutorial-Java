<br />
<div align="center">
  <h3 align="center">Java Basic</h3>
  <h1>Java Casting</h1>

  <p align="center">
    Menjelaskan basic java casting
    <br />
    <a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/README.md"><strong>Kembali ke menu utama »</strong></a>
    <br />
    <br />
    <a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/README.md">Java Basic</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Java OOP</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Java Data Structure</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary><H3>List Materi Java Basic</H3></summary>
  <ol>
    <li>
      <a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/README.md">Java Basic</a>
      <ul>
        <li><a href="#built-with">Sejarah Java</a></li>
        <li><a href="#built-with">Syntax Dasar Hello World!</a></li>
        <li><a href="#built-with">Commant</a></li>
        <li><a href="#built-with">Variables</a></li>
        <li><a href="#built-with">Tipe Data</a></li>
        <li><a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/Casting.md">Casting</a></li>
        <li><a href="#built-with">Operator</a></li>
        <li><a href="#built-with">Java String</a></li>
        <li><a href="#built-with">Java Math</a></li>
        <li><a href="#built-with">Java If-else Statement</a></li>
        <li><a href="#built-with">Java Switch Statement</a></li>
        <li><a href="#built-with">Built looping</a></li>
        <li><a href="#built-with">Java Array</a></li>
        <li><a href="#built-with">Java Methods</a></li>
      </ul>
    </li>
  </ol>
</details>

## Java Casting

Jadi singkatnya gini, kalo di casting itu maksudnya merubah suatu tipe data, misalnya tipe data integer diubah jadi string etc. 
Di Java sendiri terdapat dua jenis casting, yakni 
1. Widening Casting (automatically) - mengubah tipe yang lebih kecil ke ukuran tipe yang lebih besar
contohnya: 
```js
    byte -> short -> char -> int -> long -> float -> double
```
2. Narrowing Casting (manually) - mengubah tipe yang lebih besar ke tipe ukuran yang lebih kecil
contohnya: 
```js
   double -> float -> long -> int -> char -> short -> byte 
```

<h3>Widening Casting</h3>
Widening Casting dilakukan secara otomatis saat meneruskan jenis ukuran yang lebih kecil ke jenis ukuran yang lebih besar:
contohnya:

```java
    public class Main {
        public static void main(String[] args) {
        int myInt = 9;
        double myDouble = myInt; // Automatic casting: int to double

        System.out.println(myInt);
        System.out.println(myDouble);
  }
}

output:
9
9.0
```

<h3>Narrowing Casting</h3>
Narrowing Casting Pengecoran penyempitan harus dilakukan secara manual dengan menempatkan jenis dalam tanda kurung di depan nilai:
 
contohnya:

```java
public class Main {
  public static void main(String[] args) {
    double myDouble = 9.78d;
    int myInt = (int) myDouble; // Explicit casting: double to int

    System.out.println(myDouble);
    System.out.println(myInt);
  }
}


output:
9.78
9
```


<p align="right">(<a href="#top">back to top</a>)</p>
