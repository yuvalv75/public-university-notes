---
course: 'מבוא למדעי המחשב'
lecture_number: 1
date: 2026-10-13
tags:
  - הרצאה
  - "שנה_א"
  - "סמסטר_א"
---
# מבוא למדעי המחשב - הרצאה 1

> [!info] סיכום קצר
> - **הנושא המרכזי:**
> - **הרעיון המרכזי / מה לקחת מההרצאה:**

---

## 1. מושגים והגדרות מרכזיים

> [!abstract] הגדרות ותכונות נשמרות
> 

---

## 2. סיכום ההרצאה

### נושא 1

> [!note] הערות והסברים
>


$$
\begin{array}{|c|c|c|c|}
  & number & base & solution\\ \hline 
  1  & 110101 & 2 & 1+4+16+32=53  \\ \hline
 2 
\end{array}
$$
בכל מספר בבסיס כלשהו, אם כל הקופסא ממולאת במספרים הכי גבוהים, נקבל את המספר שבקופסא הבא שרק התא האחרון בו ממולא פחות 1

לבייס 8 צריך 3 מקומות על כל ספרה ובה מעבירים כל ספרה לבינארית .
$$
427_{8} = \begin{array}{|c|c|c|c|c|c|c|c|c|}\hline
1 & 0 & 0 & 0 & 1 & 0 & 1 & 1 & 1 \\ \hline 
\end{array}\\ \space\space\space\space\space\space\space\space\space\space\space\space\space\space\space
\underbrace{\space\space\space  } \space\space\space\space\space\space\space\space_{ \space } \underbrace{ }_\space\space\space\space\space\space\space\space{  }\underbrace{}_{ 7 }

$$

בדומה לבייס 8, לבייס 16 צריך 4 מקומות על כל ספרה כדי לייצג אותו בבינארית.

# Shifting Bits - Left

- all existing bits move to the left and then we add another bit on the right with a value of 0.
- a single left-shift doubles the number
- shifting by k bits, the number multiplies by 2^k

# Shifting Bits - Right

- everything moves right, right bit moves off.
- a bit is added on the left with a value of 0.
- shifting right one time divides the number by 2 as long as a 1 is not removed.
- in a case where we remove 1, we divide by 2 and only keep a whole number floored down.

bitwise operators:
& and
| or
^ xor
~ not (unary) // works only on 1 number, basically turns 1 into 0 and 0 into 1.
<< shift left
`>>` shift right
