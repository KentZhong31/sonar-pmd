# UselessOperationOnImmutable
**Category:** `pmd`<br/>
**Rule Key:** `pmd:UselessOperationOnImmutable`<br/>


-----

An operation on an Immutable object (BigDecimal or BigInteger) won't change the object itself. The result of the operation is a new object. Therefore, ignoring the operation result is an error.
