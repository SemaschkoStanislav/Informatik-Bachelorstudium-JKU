# Übung 1 - zur Vorlesung Digitale Schaltungen

## Aufgabe 1 - *Wahrheitstabelle*

**a)** ¬(x + y) ⇔ ¬x · ¬y

| x  	| y  	| x + y | ¬(x + y) | ¬x · ¬y |
|:-----:|:-----:|:-----:|:--------:|:-------:|
| t  	| t  	| t     | f 	   | f 	     |
| t  	| f  	| t 	| f 	   | f 	     |
| f  	| t  	| t 	| f 	   | f 	     |
| f  	| f  	| f 	| t 	   | t 	     |


**b)** ¬x · ¬y + x · y = ¬(x · ¬y + ¬x · y)

| x  	| y  	| ¬x · ¬y + x · y | x · ¬y + ¬x · y | ¬(x · ¬y + ¬x · y) |
|:-----:|:-----:|:---------------:|:---------------:|:------------------:|
| t  	| t  	| t               | f 	            | t 	             |
| t  	| f  	| f 	          | t 	            | f 	             |
| f  	| t  	| f 	          | t 	            | f 	             |
| f  	| f  	| t 	          | f 	            | t 	             |

**c)** x · y + ¬x · z + y · z = x · y + ¬x · z

| x  	| y  	| z  	| x · y + ¬x · z + y · z | x · y + ¬x · z |
|:-----:|:-----:|:-----:|:----------------------:|:--------------:|
| f  	| f  	| f     | f 	                 | f 	          |
| f  	| f  	| t     | t 	                 | t 	          |
| f  	| t  	| f 	| f 	                 | f 	          |
| f  	| t  	| t     | t 	                 | t 	          |
| t  	| f  	| f     | f 	                 | f 	          |
| t  	| f  	| t     | f 	                 | f 	          |
| t  	| t  	| f     | t 	                 | t 	          |
| t  	| t  	| t     | t 	                 | t 	          |

## Aufgabe 2 - *Boolesche Algebra*

**a)**

 ¬(a · b) + b  /De Morgan

 ¬a + ¬b + b   /Komplementierung

 ¬a + 1        /Extremalgesetz

 = 1

**b)**

x · ¬y + ¬x · y     /

**c)**

## Aufgabe 3 - *Kombinatorische Schaltung: Smart Home*

