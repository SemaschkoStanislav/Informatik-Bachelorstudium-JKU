# Aufgabe 1 - *Wahrheitstabelle*

#### Gruppenarbeit von: 
#### Muhammet Batuhan Özdogan (12231298)
#### Semaschko Stanislav (12235026)
#### Nico Sami Diaz Cajas (12208474)

---

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
