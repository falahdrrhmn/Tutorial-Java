<div id="top" align="center">
  <h3 align="center">Java Basic</h3>
  <h1>Java Access Modifier</h1>

  <p align="center">
    Menjelaskan basic Java Access Modifier
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

## Java Access Modifier

Jadi singkatnya gini access modifier tu hak akses yang dikasi ke variabel/method/class dg tujuan jaga data tersebut ketika ingin diakses

<img width="350" alt="image" src="https://user-images.githubusercontent.com/92344349/183013163-ad040cdb-dc10-477e-a03f-867396ed08fd.png">

di java ada 4 access modifier, yakni 
- Public
- Private
- Default/No access modifier
- Protected

<br><br><br>

### Public 

Access modifier public mempunyai hak akses paling luas dibanding yang lainnya. Karena aksesnya sangat luas, maka access modifier ini biasanya digunakan untuk method setter getter sesuai konsep OOP.

```java
public class Hewan {
	private int jumlahKaki;
	private String namaHewan;
	public int getJumlahKaki() {
		return jumlahKaki;
	}
	public void setJumlahKaki(int jumlahKaki) {
		this.jumlahKaki = jumlahKaki;
	}
	public String getNamaHewan() {
		return namaHewan;
	}
	public void setNamaHewan(String namaHewan) {
		this.namaHewan = namaHewan;
	}
}
```

### Protected

Access modifier protected biasanya digunakan untuk mewariskan variabel yang ada di super class terhadap child class.

```java
public class User{
	protected String nama;
	protected String jabatan;
}
```

### No Access Modifier/Default

Sesuai namanya, hak akses yang satu ini tidak perlu dituliskan di method/variabelnya. Dengan hak akses ini, variabel/method dapat diakses dari class lain asalkan masih dalam satu package yang sama.

```java
public class Kendaraan {
	int jumlahRoda;
	String warna;
}
```

### Private

Access modifier private bersifat tertutup. Sesuai dengan konsep OOP Encapsulation, maka setiap variabel wajib untuk dilindungi hak aksesnya secara langsung dari luar. Oleh karena itu, variabel diberikan hak akses private dan untuk melakukan pengaksesan/perubahan data digunakan setter getter.

```java
public class Hewan {
	private int jumlahKaki;
	private String namaHewan;
}
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

