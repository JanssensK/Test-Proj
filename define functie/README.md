#define a methode

Author: Kevin Janssens
**Everything is typed or made in Visual studio Code**

* Traditional "Hello World"

What if we want to say “Hello” a lot without getting our fingers all tired? We need to define a method!

```ruby

irb(main):010:0> def hi
irb(main):011:1> puts "Hello World!"
irb(main):012:1> end
=> :hi

```
The code def hi starts the definition of the method. It tells Ruby that we’re defining a method, that its name is hi.
The next line is the body of the method, **Puts "Hello World**.
Finally, the last line end tells Ruby we’re done defining the method. Ruby’s response => :hi tells us that it knows we’re done defining the method.

-> While running the methode you get the next result:

```ruby

irb(main):013:0> hi
Hello World!
=> nil
irb(main):014:0> hi()
Hello World!
=> nil

```

#### DEF_HelloWorld.rb, this file is  a bigger test based on def, class in a hello world.

To try it out, use 'ruby DEF_HelloWorld.rb' in a terminal from the same map.

Result:

```

Hello World!
Goodbye World.  Come back soon!
Hello Zeke!
Goodbye Zeke.  Come back soon!
Hello Albert!
Hello Brenda!
Hello Charles!
Hello Dave!
Hello Engelbert!
Goodbye Albert, Brenda, Charles, Dave, Engelbert.  Come
back soon!

```

#### HelloWorld_For.rb, a test to try a forloop that generate random numbers who are combined with Strings.

To try it out, use 'ruby HelloWorld_For.rb' in a terminal from the same map.

Result:

```

Still Testing..

```