# Writing Good Documentations

## Step 1 - Using Codeblocks

Codeblocks in markdown make it very *easy for* tech people to **copy, paste and share code**
A Good **Cloud Engineer** uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues

- in other to create codeblocks in markdown, you need to use three backticks(```)
- not to be confused with quotation(''')

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Input a number
num = int(input("Enter a number: "))

# Check if the number is non-negative
if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}.")

```
- when you can, you should attempt to apply syntax highlighting to your codeblocks
  
```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Input a number
num = int(input("Enter a number: "))

# Check if the number is non-negative
if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}.")

```

- Make note of where the backtick button is located.
- It should appear above the tab key
- it may vary based on your keyboard type

![download](https://github.com/El-magnificoxxii/github-docs-example/assets/75856679/36cf98bb-7639-4a47-9032-e9b5ad03dae2)

- there are no current tools in markdown for resizing images so you can use your html here
<img width = 100 src = https://github.com/El-magnificoxxii/github-docs-example/assets/75856679/36cf98bb-7639-4a47-9032-e9b5ad03dae2/>

Good Cloud Engineers use codeblock for both Code and Errors that appear in the console


```bash
Traceback (most recent call last):
  File "example.py", line 5, in <module>
    result = divide(10, 0)
  File "example.py", line 2, in divide
    return a / b
ZeroDivisionError: division by zero

```
> Here is an example of using a codeblock for an error that appears in bash


## Step 3 - Use Github Flavored Markdown Task lists<sup>[1]</sup>

Github extends markdown to have a list where you can check off items.

- [x] Finish step 1
- [ ] Finish step 2
- [x] Finish step 3

## Step 4 - Use Emojis(optional)
Github Flavored Markdown supports emoji short codes
Here are some examples

| Name | Shortcode |Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` |:cloud:|
| Sunny | `:sunny:` |:sunny:|

## Step 5 - How to create Tables

You can use the followinh markdown format to create tables:

```markdown
| Name | Shortcode |Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` |:cloud:|
| Sunny | `:sunny:` |:sunny:|
```
Github extends the functionality of markdown tables to provide more alignment and table cell formatting options [<sup>[2]</sup>](#references)

- Make note of where the Pipe character is located.
- It should appear above the tab key
- it may vary based on your keyboard type

![Photo of backtick on the keyboard](assets/pipe character.jpeg)
>this is a more cleaner way to put in images because the image is located in a folder inside github

## References
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [GitHub Flavored Markdown Tasklist](https://docs.github.com/en/issues/managing-your-tasks-with-tasklists/quickstart-for-tasklists)<sup>[1]</sup>
- [GitHub Flavored Markdown Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [Github Flavored Markdown(With Extensions)](https://github.github.com/gfm/#tables-extension-)<sup>[2]</sup>
