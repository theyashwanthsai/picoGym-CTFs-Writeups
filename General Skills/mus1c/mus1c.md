### 300 points

AUTHOR: DANNY

### Description

I wrote you a [song](https://jupiter.challenges.picoctf.org/static/c0863a3b0170d6dd176be3a595b4b75e/lyrics.txt). Put it in the picoCTF{} flag format.

### Category:  General Skills

### Hints

> Do you think you can master rockstar?
> 

### Approach

The hint given points to ‘rockstar’ as a tool(?). When you download the song, its simply the lyrics in a text file. The lyrics also seem kinda familiar. Familiar to syntax maybe? But the hint clearly gives off something related to rockstar. Try searching rockstar and you will be shocked to know that it is a programming language.

[https://codewithrockstar.com/docs](https://codewithrockstar.com/docs) 

They have a online compiler

```python
Pico's a CTFFFFFFF
my mind is waitin
It's waitin

Put my mind of Pico into This
my flag is not found
put This into my flag
put my flag into Pico

shout Pico
shout Pico
shout Pico

My song's something
put Pico into This

Knock This down, down, down
put This into CTF

shout CTF
my lyric is nothing
Put This without my song into my lyric
Knock my lyric down, down, down

shout my lyric

Put my lyric into This
Put my song with This into my lyric
Knock my lyric down

shout my lyric

Build my lyric up, up ,up

shout my lyric
shout Pico
shout It

Pico CTF is fun
security is important
Fun is fun
Put security with fun into Pico CTF
Build Fun up
shout fun times Pico CTF
put fun times Pico CTF into my song

build it up

shout it
shout it

build it up, up
shout it
shout Pico
```

> 114
114
114
111
99
107
110
114
110
48
49
49
51
114
> 

This is the output to the ‘code’. Try to maybe convert the numbers into letters using the btoa() function from javascript or an online compiler.

This is what we get when we decode the numbers:

$$
rrrocknrn0113r
$$

This is the flag for this challenge.
