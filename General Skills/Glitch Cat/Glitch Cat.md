### 100 points

AUTHOR: LT 'SYREAL' JONES

### Description

Our flag printing service has started glitching!

`$ nc saturn.picoctf.net 51109`

### Category: General Skills

### Hints

**1**

> ASCII is one of the most common encodings used in programming
> 

**2**

> We know that the glitch output is valid Python, somehow!
> 

**3**

> Press Ctrl and c on your keyboard to close your connection and return to the command prompt.
> 

### Approach

Run `$ nc saturn.picoctf.net 51109` in the webshell or in a terminal

```
'picoCTF{gl17ch_m3_n07_' + chr(0x62) + chr(0x64) + chr(0x61) + chr(0x36) + chr(0x38) + chr(0x66) + chr(0x37) + chr(0x35) + '}’
```

this is what we get.

Now lets write a simple python code to get the flag

```python
print('picoCTF{gl17ch_m3_n07_' + chr(0x62) + chr(0x64) + chr(0x61) + chr(0x36) + chr(0x38) + chr(0x66) + chr(0x37) + chr(0x35) + '}')
```

Run this and you get the flag.
