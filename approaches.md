# Possible approaches to tackle problems

**Problems are as follows :-**

1. [Content Moderation](#1-content-moderation)
2. [Immutability of the Data](#2-immutability-of-the-data)
3. [User Adoption](#3-user-adoption)
4. [Scalibility](#4-scalibility)

## 1. Content Moderation

-> `Content moderation has been a major concern for web2 platforms and will certainly be for web3 social apps`


---
#### As web3 has or will have variety of social apps and diverse set of communities and tenchnologies due to it's decentalized nature. So, it's bit difficult to find a general solution or approach that will fit in all the cases and scenarios when it comes to content moderation.

- *Policies and Moderation practices* :- The first and most convenient approach would be to create policies, rules, norms regarding illicit material like terrorism, child pornography etc. in every community. Although this approach has been followd by many communities and it's time make it more robust and powerful.

- *Incentives* :- Content moderators play a major role in web2 social appps also as it takes great deal to of work to moderate an online platforms, to find and report illicit content. By granting incentives or tokens to those who contribute to moderation. 

- *Third party content moderation filter* :- Some protocols based environments can allow users to integrate third party content moderation filters or solutions. Users can select the oraginzation they trust. 

- *Tools and controls for user* :- If user is having a robust tools and control to block, report, filter content and if they have the ability to curate their feeds would be a good option. As of now it is happening at the client side in the most of the DApps.

- *Important point* :- Moderation is happening at the client side while protocols are open by design. So, anybody can push whatever they want but apps, clients & users can filter & moderate the content on their side

## 2. Immutability of the data

-> `Immutability of the data on social networks is a bad user experience, user should be able to delete the contnet but contents are getting stored on blockchain OR decentralized storage system makes it resistant to delete or alter content easily. Immuatability is a kind of double-edged sword for social content`

- *Time limited encryption* :- User can encrypt the content which they wannna delete or remove and it will be having an expiration date. After the expiration date data will become useless and meaningless as it cannot be decrypted. However, data will be immiuatble if it's in the blockchain or decentralized storage system but it will be meaningless after expiration.

- *Access control* :- Aplications can implement access control where users have different level of control over their content. As one can mark content as private, public, sharable etc.

- *Off chain metadata* :- As it is already implemented and currently being used by many applications as content are stored off-chain while blockchain records the metadata like hashes, pointer to the content etc.

- *Important point* :- As the main goal & approach should be not to store social content on-chain as it is immutable by default. Like, Farcaster is not sending content on-chain but sending it on other distributed network, lens on the other side used to push content on polygon but now they created their own L3 called "Momoka" which is somehow similar to farcaster approach.  


## 3. User Adoption

-> `As world is dominated by centralized apps like Youtube, instagram and twitter, a combination of technical, usability and market strategy could be key points to attract users but it's still bit challenging`

- *Convenient UI* :- Desiging an intutive and user friendly interface is important to attract and attain users. If an app is visually appealing, resposive and easy to naviagte, it can attract users.

- *Starting procedure* :- If one can minizime the complexity of onboarding in the sense of reducing the complexity of wallet creation, private key management etc. will help in attracting non-technical users. Abstracting the blockchain complexities could be one option.

- *Feedbacks* :- Using feedback of users and improving the DApps could be one option. As user knows what he/she wants and if feedback is worthwhile, then one can improve the DApps. This will help in gaining audiance in long term. 

- *Important Point* :- As application and protocols are open source, more people and communities can bring new innovations.

## 4. Scalibility 

-> `Athough Etherium is on the path to solve scalibility problems with sharding where etherium network splits into shard chains that share the load of the network and to increase the overall throughput.`

- *Layer 2* -> Layer 2 solutions such as state channels and sidechains are built on top of existing blockchain and help offload the transaction. It basically reduces the burden on the main chain.

- *Computation Division* :- Complex computation or tasks can moved off chain as it will reduce the computational load on the blockchain. **Truebit Protocol** is an example which enables smart contracts to securely and affordably perfom complex computation. Any smart contract can issue a computation task to this kindof oracle.

- *Storing data off chain* :- By using IPFS or swarm will reduce the reason of storing large amounts of data on the blockchain which can be inefficient.

- *Mixture of approaches* :- Solutions combine with a mixture of different techniques like shrading, layer 2 solution, off chain computation and other approaches directed towards specific requirments could help in increasing the scalability.

- *Important Point* :- Leveraging shrading, state machines, utilizing layer 2 solutions and sidechains are essential ingredient to unlock unparalleled scalability but it's easier said than done.



