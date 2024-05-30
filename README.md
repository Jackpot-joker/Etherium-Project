![logo](jackpot_320_png.png **=300x200**)
<img src="jackpot_320_png.png" alt="image" width="50%" height="auto">

# Smart-Contract-ERC20

WEB3 Project For Play To Earn

## UNCTIONS

### 1. totalSupply()

Returns the value of tokens in existence.


### 2. balanceOf(account)

Returns the value of tokens owned by account.


### 3. transfer(to, value)

Moves a value amount of tokens from the caller’s account to to.

Returns a boolean value indicating whether the operation succeeded.

Emits a transfer event.


### 4. allowance(owner, spender)

Returns the remaining number of tokens that spender will be allowed to spend on behalf of owner through transferFrom. This is zero by default.

This value changes when approve or transferFrom are called.


### 5. approve(spender, value)

Sets a value amount of tokens as the allowance of spender over the caller’s tokens.

Returns a boolean value indicating whether the operation succeeded.

### 6. transferFrom(from, to, value)

Moves a value amount of tokens from from to to using the allowance mechanism. value is then deducted from the caller’s allowance.

Returns a boolean value indicating whether the operation succeeded.

Emits a transfer event.


## EVENTS

### 1. Transfer(from, to, value)

Emitted when value tokens are moved from one account (from) to another (to).

Note that value may be zero.



### 2. Approval(owner, spender, value)

Emitted when the allowance of a spender for an owner is set by a call to approve. value is the new allowance.


# Reference

Etherium ERC20 Smart Contract Reference URL:


https://github.com/OpenZeppelin/openzeppelin-contracts/tree/master/contracts/token/ERC20

Etherium ERC20 Smart Contract Reference License:


OpenZeppelin Contracts is released under the MIT License.
