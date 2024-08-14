# Digital Contract Verification with AI Audit
* github link: https://github.com/MartinYeung5/
* network: testnet
* link: https://explorer.aptoslabs.com/account/0x86adc9e2857e9ece1a99f4de87fb41e33591562ee1f80e4351404e47bd8bc778/modules/code/ContractDatabase?network=testnet
* contract address: 0x86adc9e2857e9ece1a99f4de87fb41e33591562ee1f80e4351404e47bd8bc778

## About this project
The project aims to provide a solution for user to verify the contract with ZKP and check the contract with AI audit. 

## Schedule/Milestone
1. Add multied25519
2. Optimize smart contract
3. Optimize UI desgin
4. Update ZK function implementation
5. bug fix
6. Add verification function

## Status (Updating)
20240720
1. update ZK section - using Protokit Framework
2. develop verification function based on Protokit Framework
3. add new function for user to view the sign status of the contract
4. remove all "rawTransaction" (frontend), Bug fixed

20240721
1. add new fucntion - check contract list (which is created by other and is waiting you [expected signer] for sign)

20240722
1. function optimization - check contract list. User can input the address of contract creator and check the contract list. if you are one of expected signer from teh contract, you will see the contract in contract list.
2. create new page - ContractListByOther.tsx
3. function optimization - check contract list. When user signed the contract, the checkbox will be disable on the contract list.

20240723
1. add new function - check contract validity.
* if the contract is valid, will display the message " Contract Valid", otherwise, will display the message " Wrong Contract".

20240724
1. optimize UI design - check contract list
2. fixed the bug - checking contract data is signed or not
3. fixed contract bug - assert!(contract_record.sign == true, ETASK_IS_COMPLETED)

20240725
1. optimize move contract - fixed bug

20240726
1. optimize move contract - setup new assertion

20240727
1. fixed the bug - refresh the page when user create own contract list

20240728
1. optimize move contract - contract sign
2. optimize move contract - contract can upgrade

20240730
1. optimize move contract - contract sign

20240803
1. optimize zk logic

20240805
1. The Protokit Framework is upgraded
2. using Aptos Indexer API with Nodit
3. usecase test

20240807
1. optimize Protokit Framework with different tests

20240808
1. update Move contract

20240809
1. using Nodit - add multisig function (testing)

20240810
1. using Nodit - add Aptos NODE API (successful), tested over 200 times

20240813

## Screen Cap
* main page

* wallet login
