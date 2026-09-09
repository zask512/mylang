# SeekhoLang — Beginners Course
### Ek chhoti si language ke zariye programming ki bunyaad seekhein

**Maqsad:** Ye course "SeekhoLang" (Roman Urdu commands wali chhoti language) ke zariye programming ke core concepts sikhata hai. Har concept ke saath Python aur JavaScript mein bhi wahi cheez dikhayi jayegi, taake baad mein koi bhi real language seekhna aasan ho jaye.

**Tareeka:** Har module mein — concept ki explanation → SeekhoLang mein example → Python/JS comparison → practice exercise. Aakhir mein mini-project.

---

## Module 0: Programming Kya Hai?
**Concept:** Computer ko step-by-step instructions dena. Program = instructions ki list jo computer top-to-bottom follow karta hai.

**Practice:** Apni ek subah ki routine 5 steps mein likhein (jaise ek program).

---

## Module 1: Variables aur Data Types
**Concept:** Variable ek "dabba" hai jisme value store hoti hai.

```
naam = "Ali"
umar = 20
lamba = 5.6
shaadi_shuda = jhoot
```

**Data Types:** number, string (matlab), boolean (theek/jhoot)

| SeekhoLang | Python | JavaScript |
|---|---|---|
| `naam = "Ali"` | `naam = "Ali"` | `let naam = "Ali";` |
| `umar = 20` | `umar = 20` | `let umar = 20;` |

**Exercise:** Apna naam, umar, aur city variables mein store karein.

---

## Module 2: Input / Output
**Concept:** Computer se baat karna — batana (`likho`) aur poochna (`sunlo`).

```
likho "Aapka naam kya hai?"
naam = sunlo()
likho "Salam, " + naam
```

| SeekhoLang | Python | JavaScript |
|---|---|---|
| `likho x` | `print(x)` | `console.log(x)` |
| `sunlo()` | `input()` | `prompt()` |

**Exercise:** User se uska favorite khaana poochein aur print karein.

---

## Module 3: Operators
**Concept:** Math (+, -, *, /) aur comparison (<, >, ==) operators.

```
x = 10
y = 3
likho x + y
likho x > y
```

| Operator | Matlab |
|---|---|
| `+ - * /` | jama, tafreeq, zarb, taqseem |
| `== ` | barabar hai? |
| `< >` | chota/bara hai? |

**Exercise:** Do numbers lekar unka jama, tafreeq, zarb nikalein.

---

## Module 4: Conditions (Faislay)
**Concept:** Program ko decision lene dena.

```
umar = 18
agar (umar >= 18) {
    likho "Aap bara ho"
} warna {
    likho "Aap chota ho"
}
```

| SeekhoLang | Python | JavaScript |
|---|---|---|
| `agar / warna` | `if / else` | `if / else` |

**Exercise:** Ek number lekar batayein wo even hai ya odd.

---

## Module 5: Loops (Dohrana)
**Concept:** Ek kaam baar baar karna.

```
i = 1
jabtak (i <= 5) {
    likho i
    i = i + 1
}
```

| SeekhoLang | Python | JavaScript |
|---|---|---|
| `jabtak` | `while` | `while` |
| `har-aik` | `for` | `for` |

**Exercise:** 1 se 10 tak ginti print karein.

---

## Module 6: Functions (Kaam)
**Concept:** Code ka reusable tukda banana.

```
kaam banao salam_karo(naam) {
    likho "Salam, " + naam
}
salam_karo("Ali")
```

| SeekhoLang | Python | JavaScript |
|---|---|---|
| `kaam banao` | `def` | `function` |

**Exercise:** Ek function banayein jo do numbers ka jama nikale.

---

## Module 7: Lists (Fehrist)
**Concept:** Multiple values ek jagah store karna.

```
phal = ["seb", "kela", "anaar"]
likho phal[0]
```

| SeekhoLang | Python | JavaScript |
|---|---|---|
| `[...]` | `list` | `array` |

**Exercise:** 5 shehron ki list banayein aur unhe loop se print karein.

---

## Module 8: Errors (Ghaltiyan)
**Concept:** Jab kuch ghalat ho to program crash na ho.

```
koshish {
    x = 10 / 0
} pakdo (ghalti) {
    likho "Kuch ghalat hua: " + ghalti
}
```

| SeekhoLang | Python | JavaScript |
|---|---|---|
| `koshish/pakdo` | `try/except` | `try/catch` |

**Exercise:** Ek code likhein jo divide-by-zero handle kare.

---

## Module 9: Mini Projects
Ab sab kuch mila kar chhote projects banayein:

1. **Calculator** – do numbers lekar +,-,*,/ karein
2. **Guessing Game** – computer ek number soche, user guess kare
3. **To-Do List** – tasks add/remove/print karein
4. **Grade Checker** – marks lekar grade batayein (agar/warna use karke)

---

## Course Ke Baad — Agla Qadam
Jab ye 9 modules complete ho jayein, student in concepts ko lekar seedha in mein se koi bhi language seekh sakta hai:
- **Python** – sabse aasan, agla step
- **JavaScript** – websites banane ke liye
- **C++/Java** – agar computer science deeper samajhna ho

Har jagah wahi concepts hain (variables, loops, conditions, functions) — sirf likhne ka tareeqa (syntax) badalta hai.

---

## Requirements Is Course Ko Deliver Karne Ke Liye
- SeekhoLang interpreter (Python mein bana hua) jisme sab features (loops, functions, lists, error-handling) kaam karein
- Har module ke exercises ka answer-key
- Practice ke liye online ya local editor jahan student code likh kar turant run kar sake

---

*Agla step: interpreter ko expand karna taake ye saare commands (jabtak, kaam banao, lists, koshish/pakdo) asal mein chal sakein.*
