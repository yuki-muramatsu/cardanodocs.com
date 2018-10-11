---
doc_doc_title: Intro
permalink: /intro-text/
path: '/en/intro-text/'
language: 'en'
keywords: 'intro'
label: content
---

### WHAT IS CARDANO SL?
Cardano SL (or Cardano Settlement Layer) is a cryptographic currency designed and developed by IOHK in conjunction with the University of Edinburgh, the University of Athens and the University of Connecticut. Cardano SL is based on the Haskell implementation of the white paper “Ouroboros: A Provably Secure Proof of Stake Blockchain Protocol” by Aggelos Kiayias, Alexander Russell, Bernardo David and Roman Oliynykov.

You can think of Cardano SL as Bitcoin reimagined with a freedom to fix Bitcoin’s design flaws. Please read “What Makes Cardano SL Special?” for more information about similarities and differences between Cardano SL and Bitcoin.
CRYPTOCURRENCY BASICS
Before giving a definition of a cryptocurrency, let’s talk about why we care about digital currencies in general and cryptographic currencies in particular.

### WHY DO WE CARE?

- ##### SPEED
As opposed to conventional (also known as fiat), centrally banked currencies, such as the Yen or the American Dollar, digital currencies do not require a banking system to move value. With this restriction lifted, working with digital currencies is much faster than working with banking, especially on a global scale. Transferring 10 USD from Osaka to Denver no longer takes days when a digital currency is used. All transactions are made rapidly regardless of the distance.
- ##### YOU OWN YOUR MONEY
All that a commercial bank account owner is given is a promise of being paid a certain amount of money within a reasonable amount of time after receiving a payout request. Banking systems also have limits to any volume of value being moved, rendering an individual unable to withdraw or transfer large amounts quickly. In case of cryptocurrencies, the person who holds a special kind of information called a secret key can spend the money at will. No other entity has a power to manipulate the value that a user owns.
- ##### PSEUDONYMITY
One can have as many cryptocurrency addresses as they wish, receiving and spending money from different addresses as per their purpose. A merchant running an E-Commerce shop can have a set of addresses for receiving money and issuing refunds, and a separate personal “wallet” for their own needs. A single interface is used to control all of these wallets, and there is no need to log in to several payment platforms, which makes the process very time-efficient.
- ##### SECURITY
Your money is as secure as the secret key that allows spending it. This means that storing your secret key on a USB flash drive in a safe is equivalent to having banknotes in a safe. Absolutely nobody can steal this money even by carrying out a successful cyberattack.

### EXTENSIBILITY
Using an approach known as side chains, general purpose cryptocurrencies such as Cardano SL or Bitcoin can enable domain specific cryptocurrencies, such as Ethereum Classic. This way, any innovation developed via domain specific cryptocurrency can have participants who hold value in a general purpose cryptocurrency. Examples of such applications are identity management, gaming and gambling, and verifiable computations.

### WHAT IS A CRYPTOCURRENCY?
Cryptocurrency is a form of digital currency that uses cryptography to manipulate value. Cryptography provides a way to generate proof of genuine authenticity of any kind of information. This is called digital signing. In cryptocurrencies we generate a ledger (a database which provides information on how much money each address has) by signing and sending transactions to the network and receiving blocks of confirmed transactions. Cryptocurrencies are normally decentralized, meaning that many people from all over the globe participate in ledger generation by running cryptocurrency nodes. Thus, a consensus about the state of the ledger has to be achieved. Two most significant approaches for achieving such consensus are discussed in the next section.

### WHAT MAKES CARDANO SL SPECIAL?
While there are similarities between Bitcoin and Cardano SL, there are also many differences between these two cryptocurrencies. The most significant difference is that Bitcoin is a proof of work type cryptocurrency, while Cardano SL makes use of a proof of stake approach to reach consensus. This encourages honesty and long term participation.

### PURPOSE OF A CONSENSUS ALGORITHM
Consensus algorithms are used to produce new transaction blocks, resulting in an updated state of the ledger. Whenever someone publishes a block of transactions, they — or rather, their node that runs the cryptocurrency protocol — have to attach a proof that they have merited it. Below two types of such proofs are discussed.

### PROOF OF WORK AND MINING
Proof of work is the most common consensus algorithm type for cryptocurrencies. It originated in Bitcoin, and this is how this cryptocurrency works. To generate proof of work, a computer has to solve a challenge. The challenge is a computationally heavy problem which is hard to solve, but the solution is easy to verify. When a computer on a proof of work based network finds a solution, it publishes it along with the transactions that the computer has been observing while cracking the problem. The owner of this computer collects the transaction fees and a reward for generating a block. The entire process is called mining. Mining is very energy consuming, and the amount of energy needed is constantly increasing, which can lead to unsound competition.

### PROOF OF STAKE AND MINTING
Proof of stake is a novel approach to block generation. IOHK scientists led by Prof. Aggelos Kiayias have designed the first provably secure proof of stake algorithm called Ouroboros. Ouroboros lies at the heart of Cardano SL. Research team has published a white paper that is a worthy read for anyone with a background in cryptocurrency theory. The core idea of proof of stake is that instead of wasting electricity on cracking computationally heavy problems, a node is selected to mint a new block, with a probability proportional to the amount of coins this node has. If a node has positive (> 0) stake, it is called a stakeholder. If a node eventually becomes chosen to mint a block, it is called a slot leader. You can read more about this process in Proof of Stake in Cardano SL.

### BEYOND SETTLEMENT LAYER
Cardano SL is called “Layer” for a reason. It is the first component of the Cardano Platform. Eventually, it will be expanded with a Control Layer, serving as a trusted computation framework to evaluate a special kind of proofs to ensure that a certain computation was carried out correctly. In gaming and gambling, such systems are used for verifying honesty of random number generation and game outcomes. Accompanied with side chains, it will make possible to accomplish such tasks as provably fair distribution of winnings in games. But the application of Control Layer lies well beyond gaming and gambling. Identity management, credit system and more will be a part of Cardano Platform. We are also aiming to evolve Daedalus, the Cardano SL wallet application, into a universal cryptocurrency wallet featuring automated cryptocurrency trading and cryptocurrency-to-fiat transactions.