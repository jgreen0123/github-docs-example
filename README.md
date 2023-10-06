# Github Docs Example

## Step1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good _Cloud Engineer_ uses Codebloks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues


- In order to create codeblocks in markdown you need to use three backticks (`).
- Not to be confused with quotation (')
```
def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
number = 5
result = factorial(number)
puts "The factorial of #{number} is #{result}"

```

- When you can you shoul attempt  to apply syntax highlighting to you codeblocks

```ruby
def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
number = 5
result = factorial(number)
puts "The factorial of #{number} is #{result}"

```
- Make note of where the bakctick button is located.
- It should appear above the tab key, but it may vary based on your keyboard type
<img width="200px" src="https://github.com/jgreen0123/github-docs-example/assets/23021503/a4d29246-2e00-48bc-86b1-713a8efc0870" />

Good Cloud Engineers use codeblock for both code and errors that appear in the console.
```bash
An error occurred: divided by 0
Backtrace:
example.rb:2:in `/'
example.rb:2:in `divide'
example.rb:8:in `<main>'
```

> Here is an example of using a codeblock for an error that apears in bash.

## Step 3 - Use Github Flavoured Task Lists

Github extends markdown to have a list where you can check off items. [<sup>[1]</sup>](#references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

# Step 4 - Use Emojis (Optional)

Github Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | `:cloud_with_lightning:` | 🌩️ |

# Step 5 - how to create a table

You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | `:cloud_with_lightning:` | 🌩️ |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#references)
## References
- [Githib Flavored Markdown Spec](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Basic writing and formatting syntax (Github Flavoured Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)
- [ChatGPT](https://openai.com/blog/chatgpt)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sub>[1]</sub>
- [GTM - Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
