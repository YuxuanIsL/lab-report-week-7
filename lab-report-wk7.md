# Lab Report 4

## Part One

**Changing the name of the `start` parameter and its uses to `base`**

This is the shortest sequence our group come up with:

```
/start <enter> dw i base <esc> n dw i base <esc> n dw i base <esc> n dw i base :wq/
```

Firstly, I use `vim DocSearchServer.java` to enter the vim mode of the file.

![image](./%3Cstart%3E.png)

`/start` gets me to this step that it searches for and selects the first occurance of `start` in the java file.

![image](https://github.com/YuxuanIsL/lab-report-week-7/blob/main/%3Center%3E.png) 

`<enter>` gets me to this step, where it selects the first letter of `start`.

![image](https://github.com/YuxuanIsL/lab-report-week-7/blob/main/dw%20i%20base%20(1.png) 

`dw` helps to delete `start`, and `i` helps to enter the insert mode, so I can type `base` to substitude for `start`.

Then I press `<esc>` to get to the normal mode.

![image](https://github.com/YuxuanIsL/lab-report-week-7/blob/main/n%20dw%20(1.png) 

`n` helps me to move to the next `start`, and `dw` helps to delete the selecting word.

![image](https://github.com/YuxuanIsL/lab-report-week-7/blob/main/i%20base%20%3Cesc%3E.png) 

`i` gets me to the insert mode, so that I can type `base` to substitude. `<esc>` gets me to the normal mode.

![image](https://github.com/YuxuanIsL/lab-report-week-7/blob/main/n.png) 

The same, `n` gets me to the next `start`.

![image](https://github.com/YuxuanIsL/lab-report-week-7/blob/main/dw%20i%20base%20%3Cesc%3E.png) 

`dw` helps to delete `start`, and `i` helps to enter the insert mode, so I can type `base` to substitude for `start`.

Then I press `<esc>` to get to the normal mode.

The last `start` continues the same process.

![image](https://github.com/YuxuanIsL/lab-report-week-7/blob/main/last%20one.png) 

`n` helps to get to the next and last `start`, then `dw` helps to delete, `i` enters insert mode, `base`, then `<esc>` 

Then, since I made some changes and would like to keep them, `:wq/` helps to exit vim while keeping the changes.

## Part Two
For method 1, it takes me 1 minute and 37 seconds.
For method 2, it takes me 1 minute and 9 seconds.

*Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?*

I prefer logging into the remote server and edit there directly because I think that is more straight forward. That is, you don't need to think about copy and paste later since the ultimate goal is to get that program work on the remote server. Moreover, if something is already installed in that remote server, you don't need to install again in local server.

*What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)*

If some task requires a lot of new insatllations and I already have that in my local server and I know that the remote one does not, I will consider the first method.
