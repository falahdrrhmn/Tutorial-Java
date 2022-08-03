<br />
<div align="center">
  <h3 align="center">Java Basic</h3>
  <h1>Java Casting</h1>

  <p align="center">
    Menjelaskan basic java casting
    <br />
    <a href="https://github.com/falahdrrhmn/Tutorial-Java"><strong>Kembali ke menu utama »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">Java Basic</a>
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
      <a href="#about-the-project">Java Basic</a>
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
```
/**
 * Calculator grammar to generate parser in Java.
 */

// -----------------------------------------------
// Lexical grammar.

%lex

%%

\s+     /* skip whitespace */ return null;
\d+     return "NUMBER";

/lex

// -----------------------------------------------
// Operator precedence.
//
// The `*` goes after `+`, so `2 + 2 * 2` is
// correctly parsed as `2 + (2 * 2)`.
//
// Also both are left-associative, meaning
// `2 + 2 + 2` is `(2 + 2) + 2`, which is important
// when we build AST nodes.

%left '+'
%left '*'

// -----------------------------------------------
// Module include.
//
// The code which is included "as is" to the generated
// parser. Can contain `ParserEvents` class to subscribe to
// needed parsing events.

%{

/**
 * The ParserEvents class allows subscribing to
 * different parsing events.
 */
class ParserEvents {
  public static void init() {
    System.out.println("Parser is created.");
  }

  public static void onParseBegin(String str) {
    System.out.println("Parsing is started: " + str);
  }

  public static void onParseEnd(Object result) {
    System.out.println("Parsing is completed: " + result);
  }
}

%}

%%

// -----------------------------------------------
// Syntactic grammar (BNF).
//
// Defines an actual syntactic structure of
// our program.

Expr

    // ---------------------------------------
    // Addition

    : Expr '+' Expr {

        $$ = (Integer)$1 + (Integer)$3
    }

    // ---------------------------------------
    // Multiplication

    | Expr '*' Expr {

        $$ = (Integer)$1 * (Integer)$3
    }

    // ---------------------------------------
    // Simple number

    | NUMBER {

        $$ = Integer.valueOf(yytext)
    }

    // ---------------------------------------
    // Grouping in parens

    | '(' Expr ')' {

        $$ = $2

    };
```


```
    public class Main {
        public static void main(String[] args) {
          int myInt = 9;
          double myDouble = myInt; // Automatic casting: int to double

          System.out.println(myInt);
          System.out.println(myDouble);
  }
}
```

<p align="right">(<a href="#top">back to top</a>)</p>
