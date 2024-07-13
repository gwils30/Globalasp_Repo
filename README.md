# Writing Good Documentation

## Step 1 - Using Codebblocks


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
