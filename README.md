Rearrange
=========

This module is used for rearranging names.
Turns "LastName, FirstName" into "FirstName LastName".

# Example

* Calling `rearrange_name("Turing, Alan")` will return `"Alan Turing"`
* Calling `rearrange_name("Hopper, Grace M.")` will return `"Grace M. Hopper"`
* Calling `rearrange_name("Voltaire")` will return `"Voltaire"`
* Calling `rearrange_name("Voltaier")` will return `"Voltaier"`
