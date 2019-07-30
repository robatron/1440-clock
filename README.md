# 1440-clock

> A simple clock that visualizes the 1,440 precious minutes we have every day
> day https://robatron.github.io/1440-clock/

## Motivation

I wanted a simple visualization of my 1,440 minutes I have in a day. By default,
this clock shows me a visual countdown of the minutes I have remaining before
midnight.

## Usage

https://robatron.github.io/1440-clock/

To change the starting hour, e.g., to your bedtime, you can set it with the `sh`
query param:

https://robatron.github.io/1440-clock/?sh=21

## "Screenshot"

```
2019-06-01 18:32:13:292 (UTC-7:00)

    00 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23
00  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
01  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
02  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
03  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
04  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
05  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
06  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
07  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
08  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
09  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
10  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
11  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
12  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
13  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
14  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
15  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
16  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
17  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
18  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
19  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
20  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
21  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
22  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
23  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
24  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
25  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
26  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
27  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
28  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
29  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
30  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
31  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #
32  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  X  #  #  #  #  #
33  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
34  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
35  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
36  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
37  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
38  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
39  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
40  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
41  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
42  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
43  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
44  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
45  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
46  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
47  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
48  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
49  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
50  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
51  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
52  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
53  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
54  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
55  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
56  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
57  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
58  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
59  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  #  #  #  #  #  #
```

# License

Copyright 2019 Robert McGuire

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
