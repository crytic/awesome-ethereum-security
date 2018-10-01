# Awesome Ethereum Security [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated list of awesome Ethereum security references, guidance, tools, and more.

## Contents

* [Learning](#learning)
  * [Development references](#development-references)
    * [Security references](#security-references)
    * [Insecurity references](#insecurity-references)
  * [Capture the Flag and Wargames](#capture-the-flag-and-wargames)
    * [Writeups](#writeups)
  * [Coordinated disclosure](#coordinated-disclosure)
  * [Blogs](#blogs)
  * [Conference talks](#conference-talks)
  * [Podcasts and Episodes](#podcasts-and-episodes)
    * [Podcasts](#podcasts)
    * [Episodes](#episodes)
* [Tools](#tools)
  * [Visualization](#visualization)
  * [Linters](#linters)
  * [Bug finding tools](#bug-finding-tools)
  * [Verification tools](#verification-tools)
  * [Reversing tools](#reversing-tools)
* [Communities](#communities)
* [Other Awesome Lists](#other-awesome-lists)

## Learning

### Development references

#### Security references

* [Consensys Best Practices](https://github.com/ConsenSys/smart-contract-best-practices)
* [Solidity Security Considerations](https://solidity.readthedocs.io/en/latest/security-considerations.html)
* [Comprehensive list of known attack vectors for Solidity](https://blog.sigmaprime.io/solidity-security.html)
* [Decentralized Application Security Project](https://www.dasp.co/)

#### Insecurity references

* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens)
* [EVM Analyzer Benchmark](https://github.com/ConsenSys/evm-analyzer-benchmark-suite)
* [Not So Smart Contracts](https://github.com/trailofbits/not-so-smart-contracts)

### Capture the Flag and Wargames

* [Capture the Ether](https://capturetheether.com/) - A Capture The Flag style set of exploitable contracts at varying levels of difficulty.
* [Ethernaut](https://ethernaut.zeppelin.solutions/) - A Capture The Flag style set of exploitable contracts at varying levels of difficulty.
* [EtherHack](https://etherhack.positive.com/) - A Capture The Flag style set of exploitable contracts at varying levels of difficulty.

#### Writeups

* [Hands on the Ethernaut CTF](https://blog.trailofbits.com/2017/11/06/hands-on-the-ethernaut-ctf/) - Writeups for various Ethernaut CTF challenge contracts.
* [Ethernaut - Naught Coin (ERC20) Exploitation](https://medium.com/coinmonks/ethernaut-naught-coin-erc20-exploitation-218c86bb953b) - A writeup for NaughtCoin, a vulnerable ERC20 implementation, from the Ethernaut CTF.
* [EtherHack CTF Writeup](https://blog.positive.com/phdays-8-etherhack-contest-writeup-794523f01248) - A writeup for EtherHack CTF challenges.
* [How the Fomo3D lottery prize pool was taken](https://medium.com/coinmonks/how-the-winner-got-fomo3d-prize-a-detailed-explanation-b30a69b7813f) - A writeup for how a clever participant in the smart contract based lottery, Fomo3D, used abnormal transactions to ensure that they would collect the winnings.

### Coordinated disclosure

* [Blockchain Security Contacts](https://github.com/trailofbits/blockchain-security-contacts) - Email contact info for blockchain projects if you have security information to report

### Blogs

* [Hacking Distributed](http://hackingdistributed.com/) - Emin Gün Sirer, a professor in Cornell Tech’s IC3 lab focused on blockchain security.
* [Phil Does Security](https://pdaian.com/blog/) - Phil Daian, the software engineer and grad student behind KEVM, Hydra, and other Ethereum academic projects
* [Trail of Bits](https://blog.trailofbits.com/) - Cybersecurity R&D firm with a blockchain security practice
* [Martin Holst Swende](http://swende.se/) - Martin Swende, programmer and appsec consultant

### Conference talks

* [REcon 2018 - Reverse Engineering Of Blockchain Smart Contracts](https://recon.cx/2018/montreal/schedule/system/event_attachments/attachments/000/000/053/original/RECON-MTL-2018-Reversing_blockchains_smart_contracts.pdf)
* [HITB Amsterdam 2018 - Smashing Ethereum Smart Contracts for Fun and Profit](https://conference.hitb.org/hitbsecconf2018ams/sessions/smashing-ethereum-smart-contracts-for-fun-and-actual-profit/)
* [CanSecWest 2018 - Blackhat Ethereum](https://cansecwest.com/slides/2018/Blackhat%20Ethereum%20-%20Ryan%20Stortz%20and%20Jay%20Little,%20Trail%20of%20Bits,%20Inc.pdf)
* [EkoParty 2017 - Automated Bug Finding for the Blockchain](https://github.com/trailofbits/presentations/tree/master/Automatic%20Bug-Finding%20for%20the%20Blockchain)
* [OWASP AppSec California 2018 - Predicting Random Numbers in Ethereum Smart Contracts](https://schd.ws/hosted_files/appseccalifornia2018/00/AppSecCali%202018%20-%20Predicting%20Random%20Numbers%20in%20Ethereum%20Smart%20Contracts.pdf)

### Podcasts and Episodes

#### Podcasts

* [CoinSec Podcast](https://coinsecpodcast.com/)
* [The Smartest Contract](http://www.thesmartestcontract.com/)
* [Zero Knowledge](http://www.zeroknowledge.fm/)

#### Episodes

* [The Smartest Contract #15](http://www.thesmartestcontract.com/15) - Trail of Bits’ Outlook on Security w/ JP Smith
* [The Smartest Contract #8](http://www.thesmartestcontract.com/8) - Smart Contract Security and Honeypots w/ Gerhard Wagner
* [Zero Knowledge #29](http://www.zeroknowledge.fm/29) - The DAO, the White Hat Hacker Group & Giveth w/ Griff Green
* [Zero Knowledge #16](http://www.zeroknowledge.fm/16) - Talking security with JP Smith from Trail of Bits
* [Risky Business #488](https://risky.biz/RB488/) - JP Smith about all things blockchain

## Tools

### Visualization

* [ethereum-graph-debugger](https://github.com/fergarrui/ethereum-graph-debugger) - A graphical EVM debugger. Displays the entire program control flow graph.
* [Slither](https://github.com/trailofbits/slither) - Slither can map method visibility and modifiers, state variables that are read and written, calls, and can print an inheritance graph of a smart contracts
* [Solgraph](https://github.com/raineorshine/solgraph) - Generates DOT graphs with function control flow of a solidity contract
* [Surya](https://github.com/ConsenSys/surya) - Generates various visual outputs of function call graphs
* [sol-function-profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler

### Linters

* [Remix](https://remix.ethereum.org/) - A browser-based Solidity IDE with linting features
* [Solhint](https://github.com/protofire/solhint) - A linter for both security and style-guide validations. It strictly adheres to the [Solidity Style Guide](https://solidity.readthedocs.io/en/latest/style-guide.html).
* [Solium](https://github.com/duaraghav8/Solium) - Another linter for both security and style-guide validations. Does not strictly adhere to the Solidity Style Guide.

### Bug finding tools

* [Echidna](https://github.com/trailofbits/echidna) - The only available fuzzer for Ethereum software. Uses property testing to generate malicious inputs that break smart contracts
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool for Ethereum smart contracts that includes detectors for common security flaws
* [Mythril](https://github.com/b-mueller/mythril/) - Security analysis tool for Ethereum smart contracts built around detector modules
* [Securify](http://securify.ch/) - Static analysis tools from ChainSecurity
* [Slither](https://github.com/trailofbits/slither) - Static analysis framework with detectors for many common Solidity issues. It has taint and value tracking capabilities and is written in Python.
* [MAIAN](https://github.com/MAIAN-tool/MAIAN) - Automatic tool for finding trace vulnerabilities in Ethereum smart contracts

### Verification tools

* [KEVM](https://github.com/kframework/evm-semantics) - K Semantics of the Ethereum Virtual Machine (EVM)
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool for EVM

### Reversing tools

* [Ethersplay](https://github.com/trailofbits/ethersplay) - A visual disassembler for EVM bytecode built on Binary Ninja
* [ethereum-dasm](https://github.com/tintinweb/ethereum-dasm) - An EVM disassembler with static and dynamic analysis abilities, including function signature lookup
* [evm-lab](https://github.com/ethereum/evmlab) - Utilities for interacting with the Ethereum virtual machine
* [IDA-EVM](https://github.com/trailofbits/ida-evm) - An IDA plugin to view EVM instructions within IDA
* [PyEVMAsm](https://github.com/trailofbits/pyevmasm) - An EVM assembler and disassembler with a CLI and a Python API
* [Rattle](https://github.com/trailofbits/rattle) - EVM binary static analysis framework. Produces SSA representations of EVM code.
* [abi-decompiler](https://github.com/beched/abi-decompiler) - Ethereum (EVM) smart contracts reverse engineering helper utility

### Communities

* [ETHSecurity](https://discourse.secureth.org/)
* [Enterprise Ethereum Alliance Security Task Force](https://entethalliance.org/working-groups/)
* [Empire Hacking Slack](https://empireslacking.herokuapp.com/) and [Empire Hacking](https://www.empirehacking.nyc/)

## Other Awesome Lists

* [Awesome AppSec](https://github.com/paragonie/awesome-appsec)
* [Awesome Ethereum Virtual Machine](https://github.com/pirapira/awesome-ethereum-virtual-machine)
* [Awesome Solidity](https://github.com/bkrem/awesome-solidity)

## Contributing

We welcome contributions that help curate this awesome list. Please refer to the [contributing guidelines](CONTRIBUTING.md) when submitting PRs. Thanks!
