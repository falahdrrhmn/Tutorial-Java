<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h1 align="center">Tutorial Java</h1>

  <p align="center">
    Beberapa basic java buat nginget materiii biar ndak lupa
    <br />
    <a href="https://github.com/falahdrrhmn/Tutorial-Java"><strong>Code lengkap »</strong></a>
    <br />
    <br />
    <a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/README.md">Java Basic</a>
    ·
    <a href="https://github.com/">Java OOP</a>
    ·
    <a href="https://github.com/">Java Data Structure</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary id="list"><H3>List Tutorial Java</H3></summary>
  <ol>
    <li>
      <a href="#Instalasi">Instalasi</a>
      <ul>
        <li><a href="#InstalasiJDKJRE">Instalasi JDK & JRE</a></li>
        <li><a href="#InstalasiNetbeans">Instalasi Netbeans</a></li>
        <li><a href="#InstalasiVSCode">Instalasi Visual Studio Code</a></li>
      </ul>
    </li>
    <li>
      <a href="https://github.com/falahdrrhmn/Tutorial-Java/blob/main/Java%20Basic/README.md">Java Basic</a>
      <ul>
        <li><a href="#built-with">Sejarah Java</a></li>
        <li><a href="#built-with">Syntax Dasar Hello World!</a></li>
        <li><a href="#built-with">Commant</a></li>
        <li><a href="#built-with">Variables</a></li>
        <li><a href="#built-with">Tipe Data</a></li>
        <li><a href="#built-with">Casting</a></li>
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
    <li>
      <a href="#getting-started">Java OOP</a>
      <ul>
        <li><a href="#prerequisites">Dasar OOP</a></li>
        <li><a href="#installation">Class dan Object</a></li>
        <li><a href="#built-with">Class Methods</a></li>
        <li><a href="#built-with">Constructor</a></li>
        <li><a href="#built-with">Encapsulation</a></li>
        <li><a href="#built-with">Abstraction</a></li>
        <li><a href="#built-with">Inheritance</a></li>
        <li><a href="#built-with">Polymorphism</a></li>
      </ul>
    </li>
    <li>
      <a href="#usage">Java Data Structure</a>
       <ul>
        <li><a href="#prerequisites">Array</a></li>
        <li><a href="#installation">LinkedList</a></li>
        <li><a href="#built-with">Queue</a></li>
        <li><a href="#built-with">Stack</a></li>
        <li><a href="#built-with">Binary Tree</a></li>
        <li><a href="#built-with">Binary Search Tree</a></li>
        <li><a href="#built-with">Heap</a></li>
        <li><a href="#built-with">Graph</a></li>
        <li><a href="#built-with">Simple Sorting</a></li>
        <li><a href="#built-with">Recursion</a></li>
        <li><a href="#built-with">Advanced Sort</a></li>
        <li><a href="#built-with">Hash Tables</a></li>
      </ul>
    </li>
  </ol>
</details>

<!-- GETTING STARTED -->
## Instalasi

Jadi sebelum instalasi harus dicek dulu laptop udah keinstall java atau belom. Secara default, windows, macintosh, dan linux (ubuntu) tidak dilengkapi dengan Java (atau Java Runtime Environment, JRE) yang diinstal. Jadi dicek dulu di terminal, disini contohnya terminal windows. Jadi gini kalo kita mau nginstall java di PC kita, kita harus Install yg namanya JDK (Java Development kit). Teruuss apa gunanya JDK? kenapa harus install? Jadiii JDK itu sebuah software yang digunakan untu melakukan proses compilasi dari **java code ke byte code**. Jadi aplikasi android kan umumnya dikembangkan menggunakan bahasa pemrograman java, jadi java app bisa dijalankan jika ada **JVM & JDK**. Njer apalagi JVM? JVM ituu _java virtual machine_ yang merupakan bagian dari **JRE atau _java runtime environtment_**. Nahh tapii klo kita nginstall JDK (Java Development Kit) sebenernya kita sudah menginstall 2 paket yakni JDK dan JRE. Begituhhh, **jadi intinya install JDK** ribett

### Cek Java udah keinstall apa belom?

Cara tau java udah keinstall apa belom
* Cek di terminal
  ```sh
  java -version
  ```
  kalo hasilnya kayak gini berarti udah ke install
  ```sh
  java version "11.0.1" 2018-10-16 LTS
  Java(TM) SE Runtime Environment 18.9 (build 11.0.1+13-LTS)
  Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.1+13-LTS, mixed mode)
  ```
  Kalo selain itu terus ada tulisann cannot be found atau apalah berarti belom ke install, begituhh. tapiii ni tapii walaupun udah keinstall java belom tentu bisa     kepake, karna yg dibutuhin juga compilernya.
  
  
### Instalasi

Sekarang langsung masuk ke instalasi, jadi disini bakal di jelasin instalasi di **netbeans** dan **visual studio code**
<div id="InstalasiJDKJRE"></div>
#### Instalasi JDK & JRE 

1. Buka website https://www.oracle.com/java/technologies/downloads/#java8-windows
    ada tampilan kayak gini nanti. nah itu dipilih dan disesuaikan dengan laptop kalian dari sistem operasi dll
    <img width="699" alt="image" src="https://user-images.githubusercontent.com/92344349/182571405-087d6a8d-c3a8-47aa-87e9-2ca4f8cc309c.png">
    
    biasanya nanti saat ingin download disuruh login, jadi tinggal login ajaa
2. Nah nanti kalo udah install, buka folder bakal muncul kayak gini
    <img width="575" alt="image" src="https://user-images.githubusercontent.com/92344349/182572509-24cf8878-db0a-445d-81ad-5b344a91d32d.png">
    
    Nahh jadi nanti di JRE bakal ada JVM juga yg tadi udah dibahas. 
    Tapiii JDK dan JRE yang udah keinstall belom pastii kita bisa make javanya, kita cek dulu dengen ketik di terminal seperti ini
    ```sh
    javac -version
    ```
    kalo hasilnya kayak gini
    ```sh
    javac 18.0.1.1 (atau angka lainnya)
    ```
    berarti kemungkinan sebelumnya udah pernah download, tapi kalo hasilnya kayak gini
    ```sh
    'javac' is not recognized as an internal or external command, 
    operable program or batch file.
    ```
    berarti java compilernya belom teridentifikasi itu normall walaupun pas kita cek di terminal versi java (bukan compiler) hasilnya ada seperti ini 
    ```sh
    java -version
    java version "11.0.1" 2018-10-16 LTS
    Java(TM) SE Runtime Environment 18.9 (build 11.0.1+13-LTS)
    Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.1+13-LTS, mixed mode)
    ```
    nah jadi cara masang java compilernya kita tinggal ke menu windows terus search aja path, nanti ada pilihan kayak gini
    
    <img width="255" alt="image" src="https://user-images.githubusercontent.com/92344349/182575473-f77f0174-5161-4827-8f18-221a5551e966.png">
    
    nahh yaudah tinggal klik itu "Edit System Environment Variable"
    
    <img width="309" alt="image" src="https://user-images.githubusercontent.com/92344349/182575922-88c58c34-20b7-4fdc-8b9d-a8c970c04ce9.png">
    
    terus nanti pilih yang environtment variable, terus nanti muncul tampilan kayak gitu
    
    <img width="368" alt="image" src="https://user-images.githubusercontent.com/92344349/182576667-57941cd5-c1f8-4acd-b650-20e8bae2db3a.png">
    
    itu klik bagian **path** terus **edit**
    abis itu nanti muncul tampilan kayak gini 
    
    <img width="367" alt="image" src="https://user-images.githubusercontent.com/92344349/182577072-3479e538-bfbc-4bbb-aee9-68284f54ff39.png">

    disitu kita klik new buat bikin path baru, pathnya dari mana? kita buka lagi folder JDK, terus nanti didalemmnya ada bin. naahh directory menuju folder itu kita copas, kayak gini contohnya 
    
    <img width="561" alt="image" src="https://user-images.githubusercontent.com/92344349/182577581-f9eb1ca6-6d1e-4537-ba5c-b1a6dd2eb97e.png">

    terus kita copas jadi kayak gini nantinya 
    ```sh
    C:\Program Files\Java\jdk-18.0.1.1\bin
    ```
    
    terus nanti jadinya kayak gini 
    
    <img width="368" alt="image" src="https://user-images.githubusercontent.com/92344349/182578518-d8a0c4dc-8ba2-47f1-a035-ccebe6f6343a.png">
    
    atau sebenernya kita juga bisa make cara lain, yang mana kita jadi bisa make seluruh versi JDK, harusnya yee
    
    jadi caranya dibagian System variable kita klik new
    
    <img width="424" alt="image" src="https://user-images.githubusercontent.com/92344349/182578942-c284b407-994d-4bb0-8764-d3704c0ee357.png">

    terus nanti ada pilihan kayak gini, untuk variable nama kasi nama HOME_JAVA kalo variable value kasi directory ke bin tadi. kayak gini contohnya
    
    <img width="469" alt="image" src="https://user-images.githubusercontent.com/92344349/182579510-5b50d6fa-ed1d-4df6-8cc5-10d5f0c809da.png">
    
    abis itu klik oke, terus kita masuk lagi ke path terus klik edit
    
    <img width="366" alt="image" src="https://user-images.githubusercontent.com/92344349/182580104-d11384ba-4133-4d3d-851e-5f4ba26a093b.png">

    terus tambahin kayak gitu, jadi bebas pilih yang mana


<div align="center">
  <a href="#list">(Back to List)</a>
  ·
  <a href="#top">(Back to Top)</a>
</div>

<br>
<br>


#### Instalasi Netbeans
<div id="InstalasiNetbeans"></div>
setelah berhasil menginstall JDK & JRE selanjutnya kita akan melakukan instalasi netbeans, apabila tidak ingin menggunakan netbeans anda dapat langsung klik ini untuk skip ke instalasi visual studio code

1. yang pertama kita buka website resmi dari dari apache netbeans terlebih dahulu, yakni https://netbeans.apache.org/download/nb14/nb14.html        

   <img width="962" alt="image" src="https://user-images.githubusercontent.com/92344349/182628425-9c535fe5-0b29-4068-a981-447fa5b604b2.png">
   
   Nantinya akan muncul tampilan seperti itu, tinggaal disesuain tipe laptop

2. Terus setelah itu akan muncul tampilan seperti ini 

   <img width="962" alt="image" src="https://user-images.githubusercontent.com/92344349/182628635-61609f7a-6354-479a-ac09-f7e1dd3333ef.png">
   
   Kalo muncul tampilan seperti itu kalian tinggal klik download sesuai yang dikotakin, abis itu yaudah tinggal download kayak biasanya

<div align="center">
  <a href="#list">(Back to List)</a>
  ·
  <a href="#top">(Back to Top)</a>
</div>

<br>
<br>


#### Instalasi Visual Studio Code
<div id="InstalasiVSCode"></div>
Karena lagi males + caranya gampang jadi buat downolad java di VSCode caranya tinggal kayak gini
https://www.tutorialpemrograman.com/desktop/cara-cepat-compile-dan-run-program-java-dengan-visual-studio-code/

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
