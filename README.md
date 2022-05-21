# AutoCompounder
Harvest and reinvest example in ApeSwapt.
Using the Matic Network, harvesting and reinvesting the APE-MATIC pair.
Can be used for other pairs, but take in care some functions may vary.
Tasklist:
1-Fix the low nonce (i.e. wait still tx is finnished to start the following tx)
2-Clean code, most functions (liquidity, deposit, harvest, swap) inside the AutoCompounder()
3-Insert parameters trough commander, add a dic with token address so user can chose what pair to farm
4-Create a json for library versions, and one for the dic of the addresses
