list of calls in InvtronDAO MVP:

Functions:
- `nominateNewOwner()`
- `upvoteNominee()`
- `downvoteNominee()`
- `nominateFundedWallet(address wallet)`
- `releaseLiquidity()`
- `upvoteFundedWallet()`
- `downvoteFundedWallet()`
- `getVotingPower(address voter)`
- `getTokenPrice()`

Declarations:

- `OwnerNominated(address indexed nominee)`
- `OwnerNominationResult(bool success)`
- `UserVote(address indexed voter, address indexed wallet, uint256 voteAmount, bool isUpvote)`
- `LiquidityPoolReleased(address indexed wallet, uint256 amount)`
