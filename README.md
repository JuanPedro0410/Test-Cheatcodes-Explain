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

```
vm.prank(USER);
```
The next rtansaction will be send by USER.

```
uint256 gasStart = gasleft();
vm.txGasPrice(GAS_PRICE);
```

txGasPrice returns the transaction gas price and you must to pass the current gasprice.

```
vm.hoax(address, value)
```

This is a combination of makeAddr and deal.

```
        vm.startPrank(fundMe.getOwner());
        (transaction)
        vm.stopPrank();
```
This make that the transaction that you put into the vm.Stop and Start Prank, will be send by the address that you pass.


```
assert(1 == 1)
assertEq(1, 1)
```

this check if the first thing that you pass is equal to the second.

