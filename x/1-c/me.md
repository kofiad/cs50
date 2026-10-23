> Source: https://cs50.harvard.edu/x/psets/1/me/

# Hello, It’s Me

## Problem to Solve

In a file called `hello.c`, in a folder called `me`, implement a program in C that prompts the user for their name and then says hello to that user. For instance, if the user’s name is Adele, your program should print `hello, Adele\n`!

Hints

- Recall that you can get a `string` from a user with `get_string`, which is declared in `cs50.h`.
- Recall that you can print a `string` with `printf`, which is declared in `stdio.h`.
- Recall that you can format a `string` with `printf` with `%s`.

## Demo

## How to Begin

Execute `cd` by itself in your terminal window. You should find that your terminal window’s prompt resembles the below:

```
$
```

Next execute

```
mkdir me
```

to make a folder called `me` in your codespace.

Then execute

```
cd me
```

to change directories into that folder. You should now see your terminal prompt as `me/ $`. You can now execute

```
code hello.c
```

to create a file called `hello.c` in which you can write your code.

## Walkthrough

Here’s a “walkthrough” (i.e., tour) of this problem, if you’d like a verbal overview of what to do too!

## How to Test

### Correctness

```
check50 cs50/problems/2026/x/me
```

### Style

```
style50 hello.c
```

## How to Submit

In your terminal, execute the below to submit your work, answering the prompts that come up as well.

```
submit50 cs50/problems/2026/x/me
```
