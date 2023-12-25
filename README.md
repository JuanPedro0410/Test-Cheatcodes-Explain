# Test-Cheatcodes-Explain

```
  vm.expectRevert();
```
This said that the next line should revert (fails).

```
address USER = makeAddr("user");
```
This line make, returns an address for the person "user".

```
uint256 constant STARTING_BALANCE = 10 ether;
vm.deal(USER, STARTING_BALANCE)
```

This gives to the address  of "user" the amount that you pass in ether, in this case it is 10 ether.
