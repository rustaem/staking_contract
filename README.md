aestaking_contract
=====

Dummy lib for the AEternity project. Contains compiled and ready to use StakingContract.json

Build
-----

No need to build it, just dep it in the rebar.config:

`{deps, [{staking_contract, {git, "git://github.com/rustaem/aestaking-contract.git",}}]}`

Make sure NOT to use `ref` or `tag` tuple (as it will be updated in due time).

