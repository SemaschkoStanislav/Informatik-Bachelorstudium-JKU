# Weekly Challenge 2: Model Counting

First found satisfying assignment for `42.limboole` is:

c = 0

a = 0

d = 0

b = 0

e = 0

=> & (a | b | c | d | e)

---

c = 0

a = 1

d = 0

b = 1

e = 0


=> & (!a | !b | c | d | e)

---

c = 1

a = 0

d = 0

b = 1

e = 1

=> & (a | !b | !c | d | !e)

---

c = 0

a = 1

d = 1

b = 1

e = 1

=> & (!a | !b | c | !d | !e)

---

c = 0

a = 1

d = 1

b = 1

e = 0

=> & (!a | !b | c | !d | e)

---

c = 1

a = 1

d = 1

b = 0

e = 0

=> & (!a | b | !c | !d | e)

---

name: Semaschko

student number: 12235026

number of solutions: 6

solutions: (a | b | c | d | e) &
(!a | !b | c | d | e) &
(a | !b | !c | d | !e) &
(!a | !b | c | !d | !e) &
(!a | !b | c | !d | e) &
(!a | b | !c | !d | e)
