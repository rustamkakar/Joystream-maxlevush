# Community Bounty #15 - "Summary/Transcripts of Community Update Videos"

 *by maxlevush id 2130*

## Video 1 [Community Update #1](https://play.joystream.org/video/12)

videoId, slideId, timestamp_start:

### 12, 1.001, 00:00
![Joystream_Community_Update_1 001](https://user-images.githubusercontent.com/83000549/120277816-1de96100-c2e7-11eb-8c2c-a51cffe57408.jpeg)

**Summary:** This is the first installment of the Joystream community update video series in an effort to share more effectively what it is we are working on, what is coming down the pipe, what’s happening in the community, to bring everyone up to speed on where we are going and the road to mainnet basically.

### 12, 1.002, 00:25
![Joystream_Community_Update_1 002](https://user-images.githubusercontent.com/83000549/120278668-25f5d080-c2e8-11eb-8b65-3f7095e7be97.jpeg)

**Summary:** In this first episode I’m going to be covering first of the three next immediate networks – Antioch, Sumer, and Olympia, in that order.

Then I am going to be covering Hydra which is an infrastructure piece making all these networks possible, and it is really important for delivering the main products we are working on that are consumer-facing – Atlas and Pioneer.

Then I am going to try to go through the community side – what we are doing, what the point of the different initiatives is, what the status is, and, of course, the different new specifications that we have prepared for new exciting improvements that are coming after Olympia.

### 12, 1.003, 01:14
![Joystream_Community_Update_1 003](https://user-images.githubusercontent.com/83000549/120279319-de237900-c2e8-11eb-8326-113f42c23d52.jpeg)

**Summary:** If you have been following us for a while, if you are even inside of JS Genesis trying to build this out, I am sure you must have noticed that the technical and social complexity of what we are trying to deliver has escalated quite significantly in the last six months. And with any growing effort organization you are going to have a lot of difficulty trying to synchronize all that information effectively.

So, the point of this video series is to bring people more up to date on what we are doing as up until now we have been making these network releases and announcements that are themselves kind of quite brief on the details of what’s actually being delivered.

### 12, 1.004, 02:31
![Joystream_Community_Update_1 004](https://user-images.githubusercontent.com/83000549/120279641-42ded380-c2e9-11eb-97f0-a9fc180de2b1.jpeg)

**Summary:** It is not just the scope of what we are trying to do but the number of people involved inside of JS Genesis specifically has grown significantly.

People are involved into sub teams, they are trying to deliver quite complex functionality but still isolated to some smaller part of the system. Then it is very easy to get lost and not see how everything fits together.

So, it’s both for the benefit of the community and us, as an organization, to try to get up to speed and organized around what we are trying to deliver.

## Transcript

Video 1 [Community Update #1](https://play.joystream.org/video/12)

Hi everyone!

And welcome to this first installment of the Joystream community update video series.

So, this is, as I said, the first installment of many to come 
in an effort to try to share a little bit more effectively what it is we are working on, what is coming down the pipe, what’s happening in the community.

Just to try to bring everyone up to speed on where we are going and the road to mainnet basically. 

So, in this first episode I’m going to be covering first of the three next immediate networks – Antioch, Sumer, and Olympia, in that order. 

Then I am going to be covering Hydra which is sort of an infrastructure piece which is part of making all these networks possible and really important for delivering the main products we are working on that are consumer-facing – Atlas and Pioneer. 

Then I am going to try to go through the community side – what are we doing, what is the point of the different initiatives, what is the status, and, of course, least but not last, well, last but not least, the different new specifications that we have prepared for new exciting improvements that are coming after Olympia.

So, I guess I should say a little bit more about what the point is of these update series. 

If you have been following us for a while, if you are even inside of JS Genesis trying to build this out, I am sure you must have noticed that the technical and social complexity of what we are trying to deliver has escalated quite significantly in the last six months or so.

And with any growing effort organization you are going to have a lot of difficulty trying to synchronize all that information effectively.

So, the point of this video series is we’ll just try to open up the floodgates informationally speaking so that people are more up to date on our sort of finer time scale in terms of what we are doing because up until now we have been making these network releases and announcements that are themselves kind of quite brief on the details of what’s actually being delivered. 

You are going to have to dig into a lot of documentation and try a lot of stuff in order to learn to understand. 

So, it is not the best format for conveying where we are and what we are doing and what the point is. 

So, hopefully, these video series will go somewhere towards getting people synchronized on what we are trying to do, and it is not just the scope of what we are trying to do but the number of people involved inside of JS Genesis specifically has grown significantly. 

People are involved into sub teams, they are trying to deliver quite complex functionality but still isolated to some smaller part of the system. 

Then it is very easy to get lost and not see the sort of how everything fits together. 

So, it’s both for the benefit of the community and us, as an organization, to try to get up to speed and organized around what we are trying to deliver. 

So that is the goal and, hopefully, it is informative.

Please, give me feedback on what you think I should cover, how the format can be improved, and I will definitely try to take that on board.

So, this is going to be a six-part series. 

This first update just to try to break it down, reduce the chance that I blow up one of these. 

Well, if I did it all at once, I think I would have blown up the recording so I think just breaking it up is good for everyone. 

So, the next episode, I think, will be about Antioch.

So, see you in that video. 

Thank you for joining me and enjoy!

## Video 2 [Antioch Network](https://play.joystream.org/video/13)

videoId, slideId, timestamp_start:

### 13, 1.005, 00:00 
![Joystream_Community_Update_1 005](https://user-images.githubusercontent.com/83000549/121135345-fc4c2480-c866-11eb-9f43-090c893da476.jpeg)

**Summary:** About two weeks ago we were trying to make a small, not very invasive upgrade to the Babylone network, which had been humming along for about three months or so, mainly to tweak a little bit of tokenomics parameters. We wanted to increase the number of simultaneous proposals there could be - just a few minor things like that to improve the effectiveness of the testnet.

### 13, 1.006, 00:08 
![Joystream_Community_Update_1 006](https://user-images.githubusercontent.com/83000549/121135832-79779980-c867-11eb-830a-1b3f65222ece.jpeg)

**Summary:** Just for context, for people that may not know, the blockchain system or variety that the Joystream platform is built on allows you to upgrade the rules of the chain itself in flight using a special kind of transaction. 

And we tried to use this on-chain upgradability feature at that time, and that was supposed to be fine but what happened was in a matter of 20 blocks or so after the upgrade, there was a split in the network which ended up partitioning the validators into two separate polls. One group thought that the new runtime was in play, and one group thought that the old runtime was in play.

That is obviously very undesirable. The whole point of your consensus system is to have agreement upon what the history and, therefore, the state of your blockchain is.

And we’ve gone through a lot of effort trying to get to the bottom of what happened.
Trying to figure out the root cause of live failures and distributed systems is notoriously difficult, in particular if you haven’t actually prepared yourself for trying to debug those sorts of failures to begin with which we hadn’t.

### 13, 1.007, 00:47
![Joystream_Community_Update_1 007](https://user-images.githubusercontent.com/83000549/121136213-fa369580-c867-11eb-8189-33e61faf878a.jpeg)

**Summary:** We’ve gone through lots of different iterations of or possible hypothesis for what the cause could be. The best hypothesis that we have at the current time is that there is a specific bug in the version of substrate.

The joystick blockchain is built on the substrate blockchain framework which is the framework that the Polkadot blockchain is built on, and, in general, the framework that’s used to build pair chains which are blockchains that connect to Polkadot which Joystream itself may or may not end up doing. 

It’s a great framework because it means you don’t have to focus on peer-to-peer networking or consensus or any of these very low-level things, similarly as if you were deploying on Ethereum, and it really allows you to focus on building exactly the business logic that’s specific to your blockchain.

We are using a specific version of substrate, it isn’t particularly new, and the best hypothesis we could really come up with, for which there is limited evidence, was that there was a specific kind of bug in the version of substrate that we are relying on, and that’s the best candidate for what’s causing the failure.
What we’ve been working on for the past two weeks or so has been to figure that out and then to migrate to a newer version of substrate.

### 13, 1.008, 02:27
![Joystream_Community_Update_1 008](https://user-images.githubusercontent.com/83000549/121136761-9496d900-c868-11eb-9d7e-9a6b2e9f02ad.jpeg)

**Summary:** That’s what we have done. We used to be on version two release candidate four, now we are on 201. 
We are going to be launching a new chain, namely the Antioch network in probably two or three days from now that would be based on a new version of substrate which has benefits of its own, but we are mainly doing it to hopefully resolve this problem.

We would then get the runtime that we were trying to get initially with these improvements of the parameters for the proposal system.
There have also been some other changes to the way the council work.  It is a bigger council. The council period is not shorter.

There are a few things that have happened that have independent benefits but the main issue in Antioch is to get back to the core, use case that Babylon already had with these small improvements.

And then we are trying to get to Sumer as soon as possible.
It’s a big, inconvenient departure from the focus that we had but we had to do it, and now Sumer is hopefully next within a short while.

### 13, 1.009, 03:53 
![Joystream_Community_Update_1 009](https://user-images.githubusercontent.com/83000549/121137206-053df580-c869-11eb-84ff-45674518a4ed.jpeg)

**Summary:** 
