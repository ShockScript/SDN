# Global Objects

## Functions

- The `Prt` function logs message to the debug console.
- The `Rnd` function returns a randomic number. It can be optionally argumented with a range in the form `Rnd(FromN, ToN)`.
- The `Flags` function does nothing. It is used as a decorator for determining flags enumerations.

## Collection

- Provide a generic Collection type and numeric Collection types such as LongCollection.
- Collection types have Count, FstVal and LstVal properties.
- Collection types have Add, Append, Prepend, Remove, Splice, Clear, Reverse, Sort, Shift, Pop, IndexOf, LastIndexOf, Slice, Find, Filter, Map, Reduce, ReduceRight, Any and All methods.