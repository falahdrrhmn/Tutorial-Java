<div id="top" align="center">
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

