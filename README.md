<!--
### Hi there 👋
-->

<!--
**SimonFJ20/simonfj20** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# I don't know what to put here.

```hs
fib :: Number
fib 0 = 0
fib 1 = 1
fib n = fib (n-1) + fib (n-2)
```
```nearley
json    ->  object |   array
object  ->  "{" (pair ("," pair):*):? "}"
pair    ->  %string ":" value
list    ->  "[" (value ("," value ):*):? "]"
value   ->  object | list | string | number | "null" | "false" | "true"
```
```ts
const CHARS = 'plmonkij9buvhyc2gtxfr5zde3sw1aqZX4CASDQ0WEVBN7FGHRTYM6JKLU8IOP';
const randchar = () => 
    chars.charAt(Math.floor(Math.random() * chars.length));
const randstr = (length: number): string => 
    length > 0 ? randchar() + randstr(length - 1) : randchar();
```
