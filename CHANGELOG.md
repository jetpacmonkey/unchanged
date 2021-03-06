# unchanged CHANGELOG

Yes, the irony is not lost on me. :)

## 1.1.0

* Add `rollup` for building `dist` files
* Replace homegrown curry with `curriable`

## 1.0.7

* Improve speed of curried methods by removing unneeded `slice` calls and calling with initial `0` index

## 1.0.6

* Replace `map` with `slice` when shallow-cloning arrays (performance and footprint)

## 1.0.5

* Fix issue with using array keys when using `add` with nested arrays

## 1.0.4

* Ensure that the original object's prototype is retained on `merge` when it is not a standard object

## 1.0.3

* Use custom `splice` for `remove` instead of native (in case item is an extension of an `Array` and has messed with `splice`)

## 1.0.2

* Do not create a new object if the object type does not match what the key thinks it should be (causes invalid results for array-like objects)

## 1.0.1

* Remove duplicate call to `isCloneable` (performance improvement when cloning)

## 1.0.0

* Initial release
