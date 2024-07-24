# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech peopel to **copy, paste, share** code.
A good **Cloud Engineer** uses Codeblocks whenever possible. 

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks(`)
- Not to be confused with quotation (')

```
conf t
switch access vlan 2005
switchport mode trunk
no shutdown
```

- When you can you should attempt to apply syntax to highlight to your codeblocks

```python
conf t
switch access vlan 2005
switchport mode trunk
no shutdown
```

<img width="250" alt="Screen Shot 2022-04-08 at 10 10 34 AM" src="https://github.com/user-attachments/assets/0000a9e7-463b-45e3-8bc6-89f8a84fc22d">

Good Cloud Engineers use codeblocks for both code and errors that appear in the console. 

```bash
Traceback (most recent call last):
        2: from /usr/bin/irb:23:in '<main>'
        1: from (irb):1
RuntimeError: This is a custom error message
```

> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Task List

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Use emojis

Github Flavored Markdown  (GFM) supports emojis! 

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |

## Step 5 - How to create a table

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |
```

## External References

- https://gitpod.io/workspaces <sup>[1]</sup>
- [LinkedIn Feed](https://www.linkedin.com/feed/) <sup>[2]</sup>

