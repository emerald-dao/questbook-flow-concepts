# Flow Blockchain Fundamental Concepts

Hello! In this quest, you will be learning the fundamental blockchain concepts necessary to understanding the Flow blockchain. There will be no coding.

This quest was written by your *best* friends at <a href="https://twitter.com/emerald_dao" target="_blank">Emerald City</a>. If you have any questions along the way, don't be afraid to ask in our <a href="https://discord.gg/emeraldcity" target="_blank">Discord</a>. We would be so happy to help you along your journey.

## What the heck is a Blockchain?

<img src="https://raw.githubusercontent.com/emerald-dao/questbook-flow-concepts/main/learn_src/learn_assets/blockchain.png" alt="drawing" width="600"/>

When learning about the Blockchain, you may find some complicated articles. It's easy to get completely lost in the sauce and feel like you want to give up. So, I'm going to explain the Blockchain in a very easy way that may have some innacuracies/left out information but is meant to help you get started.

In one sentence: the Blockchain is an open, decentralized, shared database that allows anyone to store stuff publically.

Okay, woah. What does that mean?

1. **OPEN**: Anyone can interact with it. There are no restrictions. 
2. **DECENTRALIZED**: Nobody owns it. There is no central authority dictating stuff.
3. **DATABASE**: You can store information on it.
4. **PUBLIC**: Anyone can view the data on it.

Because of these things, we can interact with the Blockchain however we please. Often times, we may want to set up "rulebooks" that determine how people can interact with specific parts of the Blockchain so that it has some functionality - specifically our own applications that we will define. This is done with Smart Contracts.

It's also important to note that there are many different Blockchains out there. For example, Ethereum is probably the most popular Blockchain. In this course, we will be learning about the wonderful Flow Blockchain, because that's where my expertise lies ;)

## Smart Contracts? Ooo, that sounds cool.

<img src="https://raw.githubusercontent.com/emerald-dao/questbook-flow-concepts/main/learn_src/learn_assets/smart contract.png" alt="drawing" width="600"/>

Why yes, yes it is. Smart Contracts are very cool. Smart Contracts are programs, or "rulebooks" that developers make. Developers create them because it allows us to specify some functionality that users can interact with. For example, if I want to make an application that allows users to store their favourite fruit on the Blockchain, I need to make a Smart Contract that:

1. Has a function that anyone can call
2. Takes in a parameter (the person's favourite fruit)
3. Stores that parameter in some data
4. Sends the updated data to the Blockchain (happens automatically)

If I created this Smart Contract and "deployed" it to the Blockchain (deployed means we put the contract onto the Blockchain so people can interact with it), then anyone could put their favourite fruit on the Blockchain, and it would live there forever and ever! Unless we also had a function to remove that data. 

So, why do we use Smart Contracts?

1. **Speed, efficiency and accuracy**: Smart Contracts are fast, and there is no middleman. There is also no paperwork. If I want to update the data on the Blockchain by using a Smart Contract that allows me to call some function, I can just do it. I don't have to get approval from my parents or my bank.
2. **Trust and transparency**: The Blockchain, and thus Smart Contracts, are extremely secure if we make them that way. It is near impossible to hack or alter the state of the Blockchain, and while that's due to other reasons, it is largely because of Smart Contracts. If a Smart Contract doesn't let me do something, I simply can't do it. There's no way around it.

What are some downsides?
1. **Hard to get right**: While Smart Contracts are cool, they are NOT smart. They require sophisticated levels of expertise from the developer's side to make sure they have no security problems, they are cheap, and they do what we want them to do. We will learn all of this later.
2. **Can be malicious if the developer is mean**: If a developer wants to make a Smart Contract that steals your money, and then tricks you into calling a function that does that, your money will be stolen. In the world of the Blockchain, you must make sure you interact with Smart Contracts that you know are secure.
3. **Cannot undo something**: You can't just undo something. Unless you have a function that allows you to.

## Transactions & Scripts

<img src="https://raw.githubusercontent.com/emerald-dao/questbook-flow-concepts/main/learn_src/learn_assets/transaction.jpeg" alt="drawing" width="600"/>

*"Okay, so we have a Smart Contract. How do I actually interact with it? You keep saying call a function, but what does that mean!?"*

**A transaction is a glorified, paid function call.** That's pretty much the simplest I can put it. What's important to know is that a transaction CHANGES the data on the Blockchain, and usually is the ONLY way we can change the data on the Blockchain. Transactions can cost different amounts of money depending on which Blockchain you are on. On Ethereum, to store your favourite fruit on the Blockchain, it could cost dang near 100$. On Flow, it's fractions of a cent.

On the other hand, a script is used to VIEW data on the Blockchain, they do not change it. Scripts do not cost any money, that'd be rediculous.

Here is the normal workflow:
1. A developer "deploys" a Smart Contract to the Blockchain 
2. A user runs a "transaction" that takes in some payment (to pay for gas fees, execution, etc) that calls some functions in the Smart Contract
3. **The Smart Contract changes its data in some way**

## Decentralized Applications (DApps)

<img src="https://raw.githubusercontent.com/emerald-dao/questbook-flow-concepts/main/learn_src/learn_assets/dapps.jpeg" alt="drawing" width="300"/>

Oh no, this sounds complicated. Don't worry! It's not too bad. DApps are literally just normal applications (Javascript, Python, etc) that ALSO have Smart Contracts involved. That's it.

You will be building these in the future if you continue the quests on QuestBook :)

## Conclusion

On Flow, we will be making our own Smart Contracts, specifically on the Flow Blockchain. In addition, we will be making Decentralized Applications that *use* those Smart Contracts. In order to build those, we must understand the basics so we can make some cool stuff.

Although all of this may sound very complicated, it really isn't. And if you still don't understand ANY of this, that's totally okay. Sometimes it's better to jump into some examples to make things make more sense. You can do that by exploring the quests ahead.

## Quests

You can do these quests on your own, and submit them for review in the <a href="https://discord.gg/emeraldcity" target="_blank">Emerald City Discord</a> where we will review and give feedback on all your responses.

1. Explain what the Blockchain is in your own words. You can read this to help you, but you don't have to: https://www.investopedia.com/terms/b/blockchain.asp

2. Explain what a Smart Contract is. You can read this to help you, but you don't have to: https://www.ibm.com/topics/smart-contracts

3. Explain the difference between a script and a transaction.