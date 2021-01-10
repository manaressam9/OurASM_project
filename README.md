# Stepper-Motor :cd:
1. [ Description. ](#desc)
2. [ Usage tips. ](#usage)

c

<?php
        echo "Hello world!";
    ?>
    

sometext
    

<a name="usage"></a>
## 2. Usage tips

sometext

> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");
Running `cargo readme` will output the following:

~~~markdown
# Half proc

code




~~~
 * [ Description. ](#desc) 
 + Green 
     * dark  green 
     * lime  
 - Blue      
     1. Item one
        1. subitem 1
        1. subitem 2
     1. Item two

          This is is a first paragraph.

          * Green 
          * Blue

          This is a second paragraph.

     1. Item three

```javascript
Full:
 FULLP PROC
 FULLP ENDP
```

 put the Gif
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 # newwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwww
# this project explains how to control -5 leads unipolar- stepper motor using 8086 micro processor This project is programmed in assembly language, and designed using protous 8.6
# we start with controlling the mode of the motor:
# stepper motor works in 3 different modes ,we will cover only two of them :
  - full mode
  - half mode
# stepper motor rotates in two direction:
  - anti clockwise
  - clockwise
# stepper motor works in different speeds: 
  - low speed
  - midium speed 
  - high speed

 #  1-FULL MODE مش هنكتب الجمله الكلام اللى جاى عند ال FULL MODE
 - The motor rotates a full revolution in 4 steps ,each step is a 90o  step angle , In this mode two coils are energized - logic 1 is given to two coils - at a time 
# This table shows the logic of programming stepper motor in full mode in clock wise direction where A,B,C and D are the coils of the motor.
 - To rotate the motor in anti-clock wise just reverse the logic from bottom to top

|A|B|C|D|
|---|---|---|
|0|0|1|1|
|---|---|---|
|1|0|0|1|
|---|---|---|
|1|1|0|0|
|---|---|---|
|0|1|1|0|
|---|---|---|
