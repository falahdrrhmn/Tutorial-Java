<div id="top" align="center">
  <h3 align="center">Java Basic</h3>
  <h1>Java Switch Statement</h1>

  <p align="center">
    Menjelaskan basic Java Switch Statement
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

## Java Switch Statement
```
- The switch expression is evaluated once (dievaluasi sekali).
- The value of the expression is compared with the values of each case.
- If there is a match, the associated block of code is executed.
- The break and default keywords are optional, and will be described later in this chapter
```

contoh
```java
int day = 4;
switch (day) {
  case 1:
    System.out.println("Monday");
    break;
  case 2:
    System.out.println("Tuesday");
    break;
  case 3:
    System.out.println("Wednesday");
    break;
  case 4:
    System.out.println("Thursday");
    break;
  case 5:
    System.out.println("Friday");
    break;
  case 6:
    System.out.println("Saturday");
    break;
  case 7:
    System.out.println("Sunday");
    break;
}
// Outputs "Thursday" (day 4)
```

```java
int day = 4;
switch (day) {
  case 6:
    System.out.println("Today is Saturday");
    break;
  case 7:
    System.out.println("Today is Sunday");
    break;
  default:
    System.out.println("Looking forward to the Weekend");
}
// Outputs "Looking forward to the Weekend"
```

Kata kunci default menentukan beberapa kode untuk dijalankan jika tidak ada kasus yang cocok
Note that if the default statement is used as the last statement in a switch block, it does not need a break.

When Java reaches a break keyword, it breaks out of the switch block.
(Ketika Java mencapai kata kunci break, ia keluar dari blok switch.)
This will stop the execution of more code and case testing inside the block.
(Ini akan menghentikan eksekusi lebih banyak kode dan pengujian kasus di dalam blok.)
When a match is found, and the job is done, it's time for a break. There is no need for more testing.
(Ketika kecocokan ditemukan, dan pekerjaan selesai, saatnya untuk istirahat. Tidak perlu untuk pengujian lebih lanjut.)
A break can save a lot of execution time because it "ignores" the execution of all the rest of the code in the switch block.
(Istirahat dapat menghemat banyak waktu eksekusi karena "mengabaikan" eksekusi semua sisa kode di blok switch.)



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

