# A1 Museum Ticketing: My Specifications

**Finish this file first, before any code is written.** You supply the
reasoning and fill in this worksheet in your own words. The AI can then
write the code against it.

## Input and output types

What the program reads and what it prints, with the type of each value:
int, float, str, bool. Say why.

- **Inputs:** what values does the program read, and what type is each?
day(1<= age <= 8), int
age(int > 0), when input -1, end inputting



- **Outputs:** what does the program print, what type is each value, and
  how are the money values printed?



## The rules in my own words

State what the program must do, in your own words, not the assignment's
wording pasted back. Work through each part below:

- **Logic:** what the program must do, rule by rule.
child: age <= 12
senior: age >= 60
adult: 13 <= age <= 59

Ticket prices
|         | Child | Adult | Senior | Group price |
|---------|------:|------:|-------:|------------:|
| Weekday | 30    | 60    | 40     | 35          |
| Weekend | 40    | 80    | 50     | 65          |
| Holiday | 50    | 100   | 60     | 75          |

- **Boundaries:** where exactly the behaviour changes as an input changes,
  and what happens on each side.



- **Order:** the steps as a numbered list in plain sentences, not Python:
  what must happen first, and what can only be done after input ends?


