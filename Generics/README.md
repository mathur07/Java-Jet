Generics are used to extend the type or methods to work for objects and specify the data type of many, together.

#### Generic method

:star: Single generic method declaration that can be called with arguments of different types. Based on the arguments passed the method call is done.

Rules for defining generic methods:
1.  type parameter section delimited by angle brackets (< and >)

2.  one or more type parameters separated by commas. A type parameter, also known as a type variable, is an identifier that specifies a generic type name.
3.  type parameters can be used to declare the return type
4.  type parameter can represent only reference types, not primitive types (like int, double and char).

#### Generic classes
Same but followed by by a type parameter section. These classes are known as parameterized classes or parameterized types because they accept one or more parameters.

:star: NOTE: The point class should use toString else instead of giving thye output as (x,y), it will give the memory location.

#### Bounded type parameter
Sometimes we would like to limit the datatype and this used. 
To declare a bounded type parameter, list the type parameter's name, followed by the extends keyword, followed by its upper bound.
Eg.  public static <T extends Comparable<T>> T maximum(T x, T y, T z)
