---
description: >-
  Overview covering why governance systems need to implement functionality for
  voter delegation and some approaches that are worth considering
---

# Voting delegation

Voting delegation will be an important part of making a good voting system that can cater to the needs and preferences of every voter.



## **Why voting delegation is inevitable**

In an ideal world everyone would be willing to participate in every governance decision that impacts their daily lives. In practice, we rarely see this when you look at voter participation statistics. Many people don’t even participate in politician selection decisions that happen every few years. Some people might rather spend their time elsewhere, some might not agree with the voting system itself and others might prefer to let someone else handle this responsibility.

You cannot force a large population of people to all participate and make their own decision. A voter is always able to copy a voting decision from another person. Even if the person was monitored to check they voted themselves this does not mean they are not copying the decision that someone else has made. You cannot prevent people from interacting with other people prior to a governance decision, which also means you can’t prevent them from copying other people's decision choices.

A Web3 ecosystem should implement voting functionality that allows anyone to delegate their voting power to other people. By doing this on the network itself there is a huge opportunity to properly understand the voting behaviours of the users in that ecosystem. If this functionality was not built on-chain it would be more difficult to know whether people are voting with their own opinion or if they are adopting another person's choices.

Data about voting delegation could be highly insightful for understanding the governance process. For instance, delegation data would help with understanding what percentage of voting power is being delegated across each type of decision.



## Why flexible delegation implementations are inevitable

A Web3 network cannot easily prevent people from building systems on top of the network that enable voting behaviour that was not originally intended.

As an example, if a Web3 network does not implement weighted voting delegation a wallet solution could be created that splits up someone’s assets across multiple wallets so they can allocate the exact amount of voting power they want to a given voting option.

This also extends to the number of people that they delegate to. If someone wanted to delegate to three people but the network only allowed them to delegate to one person the solution would be to manage multiple wallets that each have the amount of weighting that the person wants to delegate to each person. Wrapped wallet solutions could make it effortless to manage multiple network wallets in a single abstracted wallet experience.

Web3 ecosystems benefit from just making it easier for people to delegate their voting power exactly how they want to, whether that’s to one person, an organisation or to multiple people.

Flexible implementations for voter delegation should mean that valuable data sources are created for understanding the governance system and how it is being used. On-chain data can help with showing exactly how people are actually participating in governance decisions.

It might be the case that people like to split their voting power across multiple people for the same decision. Alternatively, it could be popular to delegate voting power to one person or a group for each decision instead. In any scenario, the easier it is to see how people are actually voting the easier it becomes to understand overall voter participation and usage patterns.



## Multiple voter delegation approaches

The simplest approach to implement voter delegation is to let someone delegate their entire voting power to someone else. The problem with this approach is it doesn’t give the voter much control over how they can participate and also delegate their voting power. They might want to vote on a few decisions themselves and then enable another person to vote on a handful of other decisions. They also might want to leave the rest of the decisions to another friend they trust. Voters benefit from having the flexibility to delegate their voting power exactly as they want to.



**Priority ranked delegation**

A voter may want to delegate their voting power based on a priority ranked order. For instance, they could delegate their voting power to two different people but they might prefer the opinions of one person over the other. Priority ordered delegation could mean that the voting choice from the top priority person would be used. If the top priority person didn’t vote it would then go to the next person down the priority list and so on.

Someone's own votes would likely be priority ranked by default. Imagine a situation where someone delegates their voting power to another person. For the most part they might agree with the decisions that this other person is making - and this is why they delegated to them. However in certain situations they might have their own opinion which differs from the person they delegated to. In this situation it is beneficial for the voter to be able to cast their own vote and for that vote to take priority over the other persons vote that they delegated to. This is useful as it means the voter only needs to intervene and participate in the governance process when their own opinion differs from the person they have delegated to.



**Percentage weighted delegation**

Voting power could be split and delegated across multiple people. For example, someone may want to delegate a large percentage to one person and a small percentage to multiple other people. Or it might be any other combination of weightings they prefer. Percentage weighted delegation is one approach that could help with preventing people from receiving too much voting power as now people can easily distribute their voting power across a wide range of people that they trust and agree with.

If someone doesn’t vote on a decision the voting power they would have received could be split across the others that did based on the proportional amount of voting power they received from the voter. This could be an effective solution for ensuring that someone's voting power is always fully utilised.



**Averaged outcome delegation**

Voting power could be applied based on the averaged outcome from the people that someone has delegated to. If someone delegated to three different people the outcome from the delegation could be an average of the voting options that were selected. So if two people voted on option A and one person voted on option B the outcome would be that the entire voting power would be applied to option A - this would represent the averaged outcome from the people they delegated to.

The problems with an averaged outcome delegation approach is it requires the voter to delegate to an odd number of people. It also can be problematic for multiple voting option decisions as even with an odd number of voters the outcome might not result in a majority consensus. Percentage weight delegation is preferable for many scenarios as it doesn’t have this problem.



## Decision categorisation approaches

An important part of making a good voting delegation system is to ensure that people can delegate their voting power exactly as they want to. So a voting system will benefit from ensuring that people's ability to delegate to other people is as precise and granular as possible.



**Defined decision types**

One of the main responsibilities for the network in regards to voter delegation is to ensure that decisions are well defined. A common way this is done in programming is with the use of an enum which means a constant value is assigned to the same types of decision. If each governance decision has a defined type it should then be possible to give voters full control of delegating their voting power based on each of these decision types. Decision types should help to maximise the control and flexibility that voters have when delegating their voting power.



**Single tier decision groupings**

If each decision has a defined decision type it then becomes easier for those decision types to then be grouped together under different headings. For instance there might be a number of decisions that are related to monetary policy. Someone could then make a list of these decision types under that heading and people could use that grouping when delegating their voting power to someone.

The functionality for creating and managing these groupings doesn’t need to be handled by the network itself. Instead wallets could let people make their own groupings or let them use other peoples groupings when delegating their voting power. This approach gives the community full control in how they delegate their voting power in a way that is quick and efficient for each person based on their own preferences on how to group the governance decisions together. As long as decision types are well defined a large number of different possible groupings could then be defined. These groupings should help people with delegating their voting power more quickly rather than needing to select which decisions to delegate to each person manually.



**Multiple tier decision groupings**

Multiple tier decision groupings would be an extension of single tier groupings. For example, there might be a larger tier grouping of funding process decisions and then a smaller tier grouping for contributor selection decisions. Some groupings could represent a subset of a larger decision grouping. Using multiple tier groupings can help to further increase the speed in which people can delegate their voting power in the exact way they prefer.
