# Yet another evm puzzle
This repository is part of a post that belongs to a small series dedicated to motivate myself while learning how the evm works.
You can find the first post [here](https://medium.com/@mattaereal/solving-more-evm-puzzles-differently-part-i-170f2516b88d).

I'll be accepting pull requests for solvable challenges on this repo, so feel free to submit your own!

If you don't want to clone the repo and go straight to the challenges, below there they are with a link directly to the playground.

# Challenges
- Puzzle #1  - [Is it zero?](https://www.evm.codes/playground?unit=Wei&codeType=Mnemonic&code=%27uw07rzGTzOR~ptyLOADtzMSTORErtzuzCREATEswpzBqANCEw23vItszREVERTvDESTzSTOP%27~zPUSH1%200xz%5CnyzCqLDATAwzISZERO~vzJUMPuCqLVqUEt~00szDUP1rySIZEqALp22vI%01pqrstuvwyz~__)
- Puzzle #2  - [AAAAAAAAAAAaaaaaaaaaaahhh!!](https://www.evm.codes/playground?unit=Wei&codeType=Mnemonic&code=%27q32smmmm~CCutWAP1v1v3zMSTORE8~10pzSWAP1~01pv1~20zGT~25wIoouzMLOADuzCALLDATALOADzXORzEQ~49wIuv1zREVERTtTOP%27~zq1sz%5CnyrrrrwzJUMPvzDUPu~00twDESTzSs%200xrAAqPUSHpzADDozPOPmyy%01mopqrstuvwyz~_)
- Puzzle #3  - [I don't need charity, thanks.](https://www.evm.codes/playground?callValue=100&unit=Wei&codeType=Mnemonic&code=%27tu4vIysLOADrMSTOREsSIZEyrCREATEyyrtrSWAP5zGASzwu5vIrDUP1zREVERTvDESTzSTOP%27~zPUSH1%200xz%5Cny~00wCALLvzJUMPuzISZERO~2twVALUEszwDATAryz%01rstuvwyz~_)
- Puzzle #4 - [Who you gonna call?!](https://www.evm.codes/playground?unit=Wei&codeType=Mnemonic&code='p0yGT~p1wIyz00yuvCOPYyru~qA3~ze0~qR~PUq4s890d6908~EQ~p6wItz00~rREVERTtSTOP'~%5CnzPUq1syvSIZE~w~JUMPv~CALLDATAup0~SUBtwDEST~s%200xrDUP1~qSHpz2%01pqrstuvwyz~_)
- Puzzle #5 - [You never eat your stake alive.](https://www.evm.codes/playground?unit=Wei&codeType=Mnemonic&code='w04rSIZEzGT~eeuI~trLOAD~e0zSHR~t~tvVALUEzCREATE2zq32syyyyyy34d5cbd8a2b5e1bb6952581ae65b47ed2bd5ef2dzEQ~39uIzREVERTuDESTzSTOP'~zwz%5Cnyttwq1svzCALLuzJUMPt00s%200xrvDATAqPUSH%01qrstuvwyz~_)

## How to play

Clone this repository and install its dependencies (`npm install` or `yarn`). Then run:

```
npx hardhat play
```

And the game will start.

In some puzzles you only need to provide the value that will be sent to the contract, in others the calldata, and in others both values.

You can use [`evm.codes`](https://www.evm.codes/)'s reference and playground to work through this.

