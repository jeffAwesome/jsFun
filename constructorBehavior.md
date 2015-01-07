Four things happen when you use the new keyword


1. New object created out of thin air. Type of object is simply object.
2. It sets the new objects internal, inaccessible, [[prototype]] property to be the
   constructor functions external accessible, prototype object. Every function object automatically has a prototype property.
3. Brand new object gets bound to this keyword in the context of the function.
4. If the function doesn't return anything it will implicitly return "this"


