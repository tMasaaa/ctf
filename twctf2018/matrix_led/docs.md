# Matrix LED
```
MatrixLED.7z

https://youtu.be/C6cux2fM7fg

Update(2018-09-01 20:05 UTC):

The contents of flag.jpg was incorrect, therefore we show below a part of flag.jpg.

00000000: d091 577d 5889 e647 24e3 a93b c1f8 112f  ..W}X..G$..;.../
00000010: 86d0 f06b e859 0728 2962 9b1d a7bf 74b8  ...k.Y.()b....t.
=============================== snip ==============================
0000d100: 761c 538c c367 0f9b 945c 3a3f ca6f 40db  v.S..g...\:?.o@.
0000d110: 3de9 1a4c beab                           =..L..
And the flag is updated.

The new flag is

from hashlib import md5
print 'TWCTF{{{}}}'.format(md5(open('flag.jpg', 'rb').read()).hexdigest())
Flag
```