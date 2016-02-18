### Item 1: Consider static factory methods instead of constructors

**- ADVANTAGES:**

⋅⋅* One advantage of static factory methods is that, unlike constructors, they
have names. If two constructors whose parameter lists differ only in the order 
of their parameter types, programmer will never be able to remember which 
constructor is which and will end up calling the wrong one by mistake.
      
⋅⋅* Static factory methods is that, unlike constructors, they are not required
to create a new object each time they’re invoked.
      
⋅⋅* A third advantage of static factory methods is that, unlike constructors, 
they can return an object of any subtype of their return type.