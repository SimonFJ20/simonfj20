<!--
### Hi there š
-->

<!--
**SimonFJ20/simonfj20** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->

# I don't know what to put here.

[My Website](https://simonfj20.site/)

[Artisan Solutions](https://www.artisansolutions.dk/)

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
const randchar = (chars: string = CHARS): string => 
    chars.charAt(Math.floor(Math.random() * chars.length));
const randstr = (length: number, chars: string = CHARS): string => 
    length > 0 ? randchar(chars) + randstr(length - 1, chars) : '';
```
