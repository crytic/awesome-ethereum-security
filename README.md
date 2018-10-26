# Awesome Ethereum Security [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated list of awesome Ethereum security references, guidance, tools, and more.

## Contents

* [Learning](#learning)
  * [Security references](#security-references)
  * [Insecurity references](#insecurity-references)
  * [Capture the Flag and Wargames](#capture-the-flag-and-wargames)
    * [Writeups](#writeups)
  * [Coordinated disclosure](#coordinated-disclosure)
  * [Blogs](#blogs)
  * [Notable blog posts](#notable-blog-posts)
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

### Security references

* [Consensys Best Practices](https://github.com/ConsenSys/smart-contract-best-practices)
* [Solidity Security Considerations](https://solidity.readthedocs.io/en/latest/security-considerations.html)
* [Comprehensive list of known attack vectors for Solidity](https://blog.sigmaprime.io/solidity-security.html)
* [Decentralized Application Security Project](https://www.dasp.co/)

### Insecurity references

* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens)
* [EVM Analyzer Benchmark](https://github.com/ConsenSys/evm-analyzer-benchmark-suite)
* [Not So Smart Contracts](https://github.com/trailofbits/not-so-smart-contracts)

### Capture the Flag and Wargames

* [Capture the Ether](https://capturetheether.com/)
* [Ethernaut](https://ethernaut.zeppelin.solutions/)
* [EtherHack](https://etherhack.positive.com/)
* [SI Blockchain CTF](https://blockchain-ctf.securityinnovation.com/)

#### Writeups

* [Hands on the Ethernaut CTF](https://blog.trailofbits.com/2017/11/06/hands-on-the-ethernaut-ctf/) - Writeups for various Ethernaut CTF challenge contracts.
* [Ethernaut - Naught Coin (ERC20) Exploitation](https://medium.com/coinmonks/ethernaut-naught-coin-erc20-exploitation-218c86bb953b) - A writeup for a vulnerable ERC20 implementation from the Ethernaut CTF.
* [EtherHack CTF Writeup](https://blog.positive.com/phdays-8-etherhack-contest-writeup-794523f01248) - A writeup for EtherHack CTF challenges.
* [Capture the Ether Writeup - Pt. 1](https://medium.com/@Enigmatic1256/smart-contract-exploits-part-1-featuring-capture-the-ether-lotteries-8a061ad491b/) - Part 1 of the Capture the Ether writeup, focused on the Lotteries section.
* [Capture the Ether Writeup - Pt. 2](https://medium.com/@Enigmatic1256/smart-contract-exploits-part-2-featuring-capture-the-ether-math-31a289da0427/) - Part 2 of the Capture the Ether writeup, focused on the Math section.
* [Capture the Ether Writeup - Pt. 3](https://medium.com/@Enigmatic1256/smart-contract-exploits-part-3-featuring-capture-the-ether-accounts-c86d7e9a1400/) - Part 2 of the Capture the Ether writeup, focused on the Accounts section.
* [Capture the Ether Writeup - Pt. 4](https://medium.com/@Enigmatic1256/smart-contract-exploits-part-4-featuring-capture-the-ether-miscellaneous-232df82a559f/) - Part 4 of the Capture the Ether writeup, focused on the Miscellaneous section.

### Coordinated disclosure

* [Blockchain Security Contacts](https://github.com/trailofbits/blockchain-security-contacts) - Security contact info for blockchain projects

### Blogs

* [Hacking Distributed](http://hackingdistributed.com/) - Emin Gün Sirer, professor in Cornell Tech’s IC3 lab focused on blockchain security.
* [Phil Does Security](https://pdaian.com/blog/) - Phil Daian, grad student behind KEVM, Hydra, and other Ethereum academic projects
* [Trail of Bits](https://blog.trailofbits.com/) - Cybersecurity R&D firm with a blockchain security practice
* [Martin Holst Swende](http://swende.se/) - Martin Swende, programmer and appsec consultant

### Notable blog posts

* [Contract upgrade anti-patterns](https://blog.trailofbits.com/2018/09/05/contract-upgrade-anti-patterns/)
* [How the winner got Fomo3D prize — A Detailed Explanation](https://medium.com/coinmonks/how-the-winner-got-fomo3d-prize-a-detailed-explanation-b30a69b7813f)
* [Missing return value bug in ERC20 tokens](https://medium.com/coinmonks/missing-return-value-bug-at-least-130-tokens-affected-d67bf08521ca)
* [Not A Fair Game – Fairness Analysis of Dice2win](http://blogs.360.cn/post/Fairness_Analysis_of_Dice2win_EN.html)
* [The Anatomy of a Block Stuffing Attack](https://osolmaz.com/2018/10/18/anatomy-block-stuffing/)
* [The phenomenon of smart contract honeypots](https://medium.com/@gerhard.wagner/the-phenomena-of-smart-contract-honeypots-755c1f943f7b)
* [Use our suite of Ethereum security tools](https://blog.trailofbits.com/2018/03/23/use-our-suite-of-ethereum-security-tools/)

### Conference talks

| Title | Conference | Year |
| --- | --- | --- |
| [Predicting Random Numbers in Ethereum Smart Contracts](https://schd.ws/hosted_files/appseccalifornia2018/00/AppSecCali%202018%20-%20Predicting%20Random%20Numbers%20in%20Ethereum%20Smart%20Contracts.pdf) | OWASP AppSec | 2018 |
| [Blockchain Autopsies - Analyzing Smart Contract Deaths](https://github.com/trailofbits/publications/tree/master/presentations/Blockchain%20Autopsies%20-%20Analyzing%20Smart%20Contract%20Deaths) | Blackhat USA | 2018 |
| [Rattle - an EVM binary analysis framework](https://www.trailofbits.com/presentations/rattle/) | reCON | 2018 |
| [Blackhat Ethereum](https://github.com/trailofbits/publications/blob/master/presentations/Blackhat%20Ethereum) | CanSecWest | 2018 |
| [Smashing Ethereum Smart Contracts for Fun and Profit](https://github.com/b-mueller/smashing-smart-contracts) | HITB Amsterdam | 2018 |
| [Automatic Bug Finding for the Blockchain](https://github.com/trailofbits/publications/blob/master/presentations/Automatic%20bugfinding%20for%20the%20blockchain) | EkoParty | 2017 |

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
* [Slither](https://github.com/trailofbits/slither) - Slither can map method visibility and modifiers, state variables that are read and written, calls, and can print the inheritance graph of a smart contract
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
* [Mythril OSS](https://github.com/ConsenSys/mythril/) - Open-source security analysis tool for Ethereum smart contracts built around detector modules
* [Securify](https://github.com/eth-sri/securify) - Static analysis tool from ChainSecurity
* [Slither](https://github.com/trailofbits/slither) - Static analysis framework, written in Python, with detectors for many common Solidity issues

### Verification tools

* [KEVM](https://github.com/kframework/evm-semantics) - K Semantics of the Ethereum Virtual Machine (EVM)
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool for EVM

### Reversing tools

* [abi-decompiler](https://github.com/beched/abi-decompiler) - Ethereum (EVM) smart contracts reverse engineering helper utility
* [ethereum-dasm](https://github.com/tintinweb/ethereum-dasm) - An EVM disassembler with static and dynamic analysis abilities, including function signature lookup
* [Ethersplay](https://github.com/trailofbits/ethersplay) - A visual disassembler for EVM bytecode built on Binary Ninja
* [evm-lab](https://github.com/ethereum/evmlab) - Utilities for interacting with the Ethereum virtual machine
* [IDA-EVM](https://github.com/trailofbits/ida-evm) - IDA plugin to view EVM instructions
* [pyevmasm](https://github.com/trailofbits/pyevmasm) - EVM assembler and disassembler with a CLI and a Python API
* [Rattle](https://github.com/trailofbits/rattle) - EVM binary static analysis framework. Produces SSA representations of EVM code.

### Communities

* [Ethereum Security Events Calendar](https://calendar.google.com/calendar/embed?src=trailofbits.com_56jstkqe74aj76vv83q7h041q4%40group.calendar.google.com&ctz=America%2FNew_York)
* [ETHSecurity](https://discourse.secureth.org/)
* [Enterprise Ethereum Alliance Security Task Force](https://entethalliance.org/working-groups/)
* [Empire Hacking Slack](https://empireslacking.herokuapp.com/) #ethereum

## Other Awesome Lists

* [Awesome AppSec](https://github.com/paragonie/awesome-appsec)
* [Awesome Ethereum Virtual Machine](https://github.com/pirapira/awesome-ethereum-virtual-machine)
* [Awesome Solidity](https://github.com/bkrem/awesome-solidity)
* [Crypto projects that might not suck](https://github.com/sweis/crypto-might-not-suck)

## Contributing

We welcome contributions that help curate this awesome list. Please refer to the [contributing guidelines](CONTRIBUTING.md) when submitting PRs. Thanks!
