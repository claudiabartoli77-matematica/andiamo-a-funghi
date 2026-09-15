# Andiamo a funghi! - quesiti, soluzioni e controllo delle risposte

## Struttura aggiornata

In ognuno dei tre tratti il primo esercizio è a risposta aperta e il secondo è a scelta multipla. Le quattro alternative del secondo esercizio cambiano ordine a ogni apertura. Il fungo di recupero resta a risposta aperta. Anche le prove MCD/mcm restano aperte.

## Come vengono controllate le risposte aperte

L'app non distingue tra lettere maiuscole e minuscole e ignora tutti gli spazi e il simbolo `*` di moltiplicazione. Per esempio, `X ( X + 1 )`, `x(x+1)` e `x*(x+1)` vengono letti nello stesso modo.

Gli esponenti devono essere digitati con `^`: per esempio `(a-3)^2`. Per gli esercizi aperti sono state aggiunte le principali forme equivalenti: inversione dell'ordine dei fattori, inversione degli addendi e scritture come `(x+2)`/`(2+x)`. Non tutte le trasformazioni algebriche possibili possono essere riconosciute automaticamente: per questo sono riportate le scritture accettate dall'app.

## Primo tratto

### Base - 2 funghi per esercizio

1. `x^3-12x^2+6x`  
   Risposte accettate: `x(x^2-12x+6)`; `x*(x^2-12x+6)`.

2. `-2bx+ax-4b+2a`  
   Risposte accettate: `(a-2b)(x+2)`; `(x+2)(a-2b)`.

### Intermedio - 3 funghi per esercizio

1. `(3a+2x)(a+b)-x(a+b)`  
   Risposte accettate: `(a+b)(3a+x)`; `(3a+x)(a+b)`.

2. `4x-4-3(x-1)^2`  
   Risposte accettate: `(x-1)(7-3x)`; `(7-3x)(x-1)`.

### Avanzato - 4 funghi per esercizio

1. `x^(2n)-x^n`  
   Risposte accettate: `x^n(x^n-1)`; `(x^n-1)x^n`.

2. `a^(2x)+a^(2x+2)-a^(x+1)-a^3`  
   Risposta accettata: `a^3(a^(2x-3)+a^(2x-1)-a^(x-2)-1)`.

### Recuperi del primo tratto

- Base: `y^3-10y^2+4y` -> `y(y^2-10y+4)`.
- Intermedio: `(2a+5x)(a+c)-2x(a+c)` -> `(a+c)(2a+3x)` oppure `(2a+3x)(a+c)`.
- Avanzato: `y^(3n)-y^n` -> `y^n(y^(2n)-1)` oppure `y^n(y^n-1)(y^n+1)`.

## Secondo tratto

### Base - 2 funghi per esercizio

1. `100x^2-25`  
   Risposte accettate: `(10x-5)(10x+5)`; `25(2x-1)(2x+1)`.

2. `a^2-6a+9`  
   Risposta accettata: `(a-3)^2`.

### Intermedio - 3 funghi per esercizio

1. `(a+b)^2-c^4`  
   Risposte accettate: `(a+b-c^2)(a+b+c^2)` e ordine inverso dei due fattori.

2. `4a^4+2a^2(a+1)+(a+1)^2`  
   Risposta corretta: **è il quadrato di un binomio**, precisamente `[2a^2+(a+1)]^2`.

### Avanzato - 4 funghi per esercizio

1. `x^(10n)-a^(6n)`  
   Risposta accettata: `(x^(5n)-a^(3n))(x^(5n)+a^(3n))`.

2. Completa `a^...-...+36=(a^5-...)^2`.  
   Risposte accettate: `10,12a^5,6`; `10,12a5,6`.

### Recuperi del secondo tratto

- Base: `64y^2-16` -> `16(2y-1)(2y+1)` oppure `(8y-4)(8y+4)`.
- Intermedio: `(m+n)^2-d^4` -> `(m+n-d^2)(m+n+d^2)`.
- Avanzato: `y^(8n)-b^(4n)` -> `(y^(4n)-b^(2n))(y^(4n)+b^(2n))`.

## Terzo tratto

### Base - 2 funghi per esercizio

1. `b^3-8` -> `(b-2)(b^2+2b+4)`.

2. `x^2+5x+4` -> `(x+1)(x+4)` oppure `(x+4)(x+1)`.

### Intermedio - 3 funghi per esercizio

1. `a^9+8b^6c^3` -> `(a^3+2b^2c)(a^6-2a^3b^2c+4b^4c^2)`.

2. `a^2+30a+200` -> `(a+10)(a+20)` oppure `(a+20)(a+10)`.

### Avanzato - 4 funghi per esercizio

1. `-a^4+a^2+2` -> `(2-a^2)(a^2+1)` oppure `(a^2+1)(2-a^2)`.

2. `a^(6n)-b^3` -> `(a^(2n)-b)(a^(4n)+a^(2n)b+b^2)`.

### Recuperi del terzo tratto

- Base: `t^2+7t+12` -> `(t+3)(t+4)` oppure `(t+4)(t+3)`.
- Intermedio: `m^2+18m+80` -> `(m+8)(m+10)` oppure `(m+10)(m+8)`.
- Avanzato: `c^6-d^3` -> `(c^2-d)(c^4+c^2d+d^2)`.

## Bivio MCD/mcm - 4 funghi

Polinomi: `(3a^2+3a); (6a^2-2a); (18a^2-12a+2)`.

- MCD: `1`.
- mcm: `6a(a+1)(3a-1)^2`.

### Recupero - 3,5 funghi

- MCD tra `(4x^2+4x); (6x^2-6x); (10x^2+10x)` -> `2x`.
- mcm tra `(2x^2+2x); (3x^2-3x); (5x^2+5x)` -> `60x(x-1)(x+1)`.

## Ultimo bivio

### Salita - 7 funghi

`x^2-4x-x^4+4`  
Risposte accettate: `(1-x)(x+2)(x^2-x+2)`; `-(x-1)(x+2)(x^2-x+2)`.

### Discesa - 3 funghi

`b^5+2b^4-b-2`  
Risposta accettata: `(b+2)(b-1)(b+1)(b^2+1)`.
