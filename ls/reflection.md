# Reflection

## Reference Equality

A type may overload the equality operator. In that case it is useful to implement the method `Reflect.RefEq(a As Object?, b As Object?)`.

## Constructor

`Reflect.Construct` may be used instead of `New T` where `T` is a dynamic reference.