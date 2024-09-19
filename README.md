# Yet another evm puzzle
This repository is part of a post that belongs to a small series dedicated to motivating myself while learning how the evm works.
You can find the first post [here](https://medium.com/@mattaereal/solving-more-evm-puzzles-differently-part-i-170f2516b88d).

I'll be accepting pull requests for solvable challenges on this repo, so feel free to submit your own!

If you don't want to clone the repo and go straight to the challenges, below there they are with a link directly to the playground.

Note: Some solutions to the challenges will work correctly at evm.codes, but will fail while playing, so be sure to check them both. Trust evm.codes :)

# Challenges
- Puzzle #1  - [Is it zero?](https://www.evm.codes/playground?unit=Wei&codeType=Mnemonic&code=%27uw07rzGTzOR~ptyLOADtzMSTORErtzuzCREATEswpzBqANCEw23vItszREVERTvDESTzSTOP%27~zPUSH1%200xz%5CnyzCqLDATAwzISZERO~vzJUMPuCqLVqUEt~00szDUP1rySIZEqALp22vI%01pqrstuvwyz~_)
- Puzzle #2  - [AAAAAAAAAAAaaaaaaaaaaahhh!!](https://www.evm.codes/playground?unit=Wei&codeType=Mnemonic&code=%27q32smmmm~CCutWAP1v1v3zMSTORE8~10pzSWAP1~01pv1~20zGT~25wIoouzMLOADuzCALLDATALOADzXORzEQ~49wIuv1zREVERTtTOP%27~zq1sz%5CnyrrrrwzJUMPvzDUPu~00twDESTzSs%200xrAAqPUSHpzADDozPOPmyy%01mopqrstuvwyz~_)
- Puzzle #3  - [I don't need charity, thanks.](https://www.evm.codes/playground?callValue=100&unit=Wei&codeType=Mnemonic&code='tu1vIysLOADqMSTOREsSIZEyqCREATEyyqtqSWAP5zGASzwu6vIrqDUP1zREVERTrzSTOP'~zPUSH1%200xz%5Cny~00wCALLvzJUMPuzISZERO~2twVALUEszwDATArvDESTqyz%01qrstuvwyz~_)
- Puzzle #4 - [Who you gonna call?!](https://www.evm.codes/playground?unit=Wei&codeType=Mnemonic&code='p0yGT~p1wIyz00yuvCOPYyru~qA3~ze0~qR~PUq4s890d6908~EQ~p6wItz00~rREVERTtSTOP'~%5CnzPUq1syvSIZE~w~JUMPv~CALLDATAup0~SUBtwDEST~s%200xrDUP1~qSHpz2%01pqrstuvwyz~_)
- Puzzle #5 - [You never eat your stake alive.](https://www.evm.codes/playground?unit=Wei&codeType=Mnemonic&code='w04sSIZEzGT~38yIusLOAD~E0zSHRuuvVALUEzCREATE2zq32t34d5cbd8a2b5e1bb6952581ae65b47ed2bd5ef2dzEQ~3dyIruzDUP1zREVERTrzSTOP'~zwz%5CnyzJUMPwq1tvzCALLu~00t%200xsvDATAryDESTqPUSH%01qrstuvwyz~_)
- Puzzle #6 - [Sender or owner?](https://www.evm.codes/playground?callValue=0&unit=Wei&callData=0xdeadbeef&codeType=Bytecode&code=%27346001116014573060003560601c1832146019575b600080fd5b00%27_&fork=merge)

# Contributions
- [Underflow me](https://www.evm.codes/playground?callValue=0&unit=Wei&callData=0x00&codeType=Bytecode&code=%27600160003504600190037fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff14603057fd5b00%27_&fork=merge)
- [EvenOdd](https://www.evm.codes/playground?fork=shanghai&unit=Wei&codeType=Bytecode&code='zx2z35~81byf81c~1015b~fx101x28015y2657349003y11565bx19050ye114y3657z80fd5b00'~y0z~0y60xz5%01xyz~_)

## How to play

Clone this repository and install its dependencies (`npm install` or `yarn`). Then run:

```
npx hardhat play
```

And the game will start.

In some puzzles you only need to provide the value that will be sent to the contract, in others the calldata, and in others both values.

You can use [`evm.codes`](https://www.evm.codes/)'s reference and playground to work through this.

## Solutions
Write-up by [tnch](twitter.com/tinchoabbate) @ [notonlyowner](https://www.notonlyowner.com/) - [Solving yet another EVM puzzle](https://www.notonlyowner.com/writeups/yet-another-evm-puzzle/).

Write-up by [Norman](https://twitter.com/Normanrockon) - [Write-up for yet another EVM puzzle](https://medium.com/@0xNorman/list/evm-d2129ebffb48)
