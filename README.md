# Smart-Contract-ERC20

WEB3 Project For Play To Earn

Etherium ERC20 Smart Contract Reference URL:


https://github.com/OpenZeppelin/openzeppelin-contracts/tree/master/contracts/token/ERC20

Etherium ERC20 Smart Contract Reference License:


OpenZeppelin Contracts is released under the MIT License.


##UNCTIONS

totalSupply()

Returns the value of tokens in existence.


balanceOf(account)

Returns the value of tokens owned by account.

transfer(to, value)

Moves a value amount of tokens from the caller’s account to to.

Returns a boolean value indicating whether the operation succeeded.

Emits a transfer event.

allowance(owner, spender)

Returns the remaining number of tokens that spender will be allowed to spend on behalf of owner through transferFrom. This is zero by default.

This value changes when approve or transferFrom are called.

approve(spender, value)

Sets a value amount of tokens as the allowance of spender over the caller’s tokens.

Returns a boolean value indicating whether the operation succeeded.

transferFrom(from, to, value)

Moves a value amount of tokens from from to to using the allowance mechanism. value is then deducted from the caller’s allowance.

Returns a boolean value indicating whether the operation succeeded.

Emits a transfer event.


##EVENTS


Transfer(from, to, value)

Emitted when value tokens are moved from one account (from) to another (to).

Note that value may be zero.

Approval(owner, spender, value)

Emitted when the allowance of a spender for an owner is set by a call to approve. value is the new allowance.
