# Writing Good Documentation

## Step 1 - Using Codeblocks


Codeblocks in markdown make it very easy for tech people to copy, paste, share code.
A good cloud engineer uses Codeblocks whenever possible because it allows others to copy and paste their code to replicate or research their issues



In Order to create codeblocks in markdown you need to use three backsticks (```) not to be conffused with quotations which is the @' button without shift. 

``` ruby
# Define a person class

Class person
  def initialise (name, age)
 @name = name  # Instance variable for the person's name
 @age = age    # Instance variable for the person's age
 end

 # Instance method to return a greeting
 def greeting
 "Hello, my name is #{@name} and I am #{@age} years old."
  end
 end
```
Github extends Markdown to have a list where you can check off items. [<sup>[list-items]</sup>](#list-items)


![me_photo](https://github.com/user-attachments/assets/b7c6159d-eee6-477b-a235-62187fb86e10)

<img width="200px" src="https://github.com/user-attachments/assets/b7c6159d-eee6-477b-a235-62187fb86e10" />

This is an example of an error of a codeblock that appears in bash

``` ruby
Traceback (most recent call last):
    2: from /usr/bin/irb:23:in '<main>'
    1: from (irb):1
RuntimeError: This is a custom error message
```

> Here is an example of using a codeblock for an error that appears in bash.



## list-items
- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3      

``` md
| Name | Shortcode | Emoji |
```

## References

- ([https://github.com/octo-org/octo-repo/issues/7400](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax))
- ([https://github.com/octo-org/octo-repo/issues/740](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#headings))
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images)

- (https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)

