## Building Decentralized Applications with Data Ownership

#### Abstract

Information requires data, and an economy requires a currency as a unit of account to function. It is essential that in the **Information Economy** enabled by the Internet, we own our data. Blockchain, with its native cryptocurrency, enables a unit of account. It can also serves as the base layer for building a Decentralized Public Key Infrastructure (DPKI), enabling every individual to have a Self-Sovereign Identity. The concept of users owning their digital identity enables decentralized applications with Data Ownership.

This thesis explores the different concepts which make up a web application and describes how each can be decentralized using Blockchain and other peer-to-peer protocols. We analyze the state-of-the-art in decentralized applications platforms by building two _proof-of-concept_ applications for file sharing, one built on Ethereum and second built on Blockstack.

The main aim of the thesis is to provide its readers with a better understanding of what Blockchain technology enables in the context of web applications and showcase some properties of a secure decentralized application platform.

#### Introduction

Humans have evolved over thousands of years building systems that deal with land ownership and property rights. With the advent of the Internet, our lives have become more and more digital, with data becoming the new currency in today's digital economy. However, we have no experience in managing data ownership. Big tech companies understood the importance of user data a long time ago. They offered their services free of charge in exchange for our data, which they then used to generate profits, control our perception about how we see the world, and also tamper with public affairs like the election. There is a need to define a model for data ownership and build systems that enable users to own their data.

With data ownership comes the question of digital identity. How can we identify ourselves over the Internet? With username and passwords, we can uniquely identify ourselves when using a service, but then we have to create an identity for each service we want to use. It has another drawback, i.e., our passwords are stored on a central server, which is prone to hacking. There exist systems like _Google Sign-in_ or _Facebook Connect_, which allows us to carry our identity across multiple services, but then again, this identity is not owned by the user but by Google or Facebook. Therefore, there is a need for user-owned identity, which can be verified independently by anyone.

To visualize a model for Data Ownership, let us look at Land Ownership. In the land ownership model, at any given point in time, a property has a fixed Geo-location while the owner can be anywhere in the Geo-space. Conversely, In a data ownership model, at any given point in time, a user has a fixed identity while the data can be anywhere on the Internet.

Blockchain enables the peer-to-peer exchange of value across the Internet. Smart contracts, which are self-executing code running on a Blockchain, enable decentralized marketplaces. Finally, Blockchain's public key cryptography enables a Decentralized Public Key Infrastructure (DPKI), thereby empowering users to create self-sovereign identity. Combining self-sovereign identity with encrypted storage enables us to build systems where users own their identity as well as their data.

In this thesis, we present the concepts which make up a web application and analyze the state-of-the-art for building them in a decentralized way. We start by introducing the concepts and technologies which serve as the building blocks for decentralized protocols (Chapter 2). We describe the three types of web applications and different concepts that make them up. We then describe the evolution of each concept and explain how they will evolve because of Blockchain technology and other peer-to-peer protocols. Combining the concepts at the application layer, we propose an architecture for building decentralized applications (Chapter 3). Using this architecture, we built two proof-of-concepts applications using Ethereum and Blockstack, two popular decentralized applications ecosystem (Chapter 4). We then compare and analyze the two applications and their underlying platform. We also compare similar protocols as used in the applications (Chapter 5). We discuss the findings (Chapter 6) and conclude with a short outlook into the future (Chapter 7).
