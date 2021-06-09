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

**Summary:** What is the Antioch network?

### 13, 1.006, 00:08 
![Joystream_Community_Update_1 006](https://user-images.githubusercontent.com/83000549/121135832-79779980-c867-11eb-830a-1b3f65222ece.jpeg)

**Summary:** About two weeks ago we were trying to make a small, not very invasive upgrade to the Babylone network, which had been humming along for about three months or so, mainly to tweak a little bit of tokenomics parameters. We wanted to increase the number of simultaneous proposals there could be - just a few minor things like that to improve the effectiveness of the testnet.

### 13, 1.007, 00:47
![Joystream_Community_Update_1 007](https://user-images.githubusercontent.com/83000549/121136213-fa369580-c867-11eb-8189-33e61faf878a.jpeg)

**Summary:** Just for context, for people that may not know, the blockchain system or variety that the Joystream platform is built on allows you to upgrade the rules of the chain itself in flight using a special kind of transaction. 

And we tried to use this on-chain upgradability feature at that time, and that was supposed to be fine but what happened was in a matter of 20 blocks or so after the upgrade, there was a split in the network which ended up partitioning the validators into two separate polls. One group thought that the new runtime was in play, and one group thought that the old runtime was in play.

That is obviously very undesirable. The whole point of your consensus system is to have agreement upon what the history and, therefore, the state of your blockchain is.

And we’ve gone through a lot of effort trying to get to the bottom of what happened.

Trying to figure out the root cause of live failures and distributed systems is notoriously difficult, in particular if you haven’t actually prepared yourself for trying to debug those sorts of failures to begin with which we hadn’t.

### 13, 1.008, 02:27
![Joystream_Community_Update_1 008](https://user-images.githubusercontent.com/83000549/121136761-9496d900-c868-11eb-9d7e-9a6b2e9f02ad.jpeg)

**Summary:** We’ve gone through lots of different iterations of or possible hypothesis for what the cause could be. The best hypothesis that we have at the current time is that there is a specific bug in the version of substrate.

The joystick blockchain is built on the substrate blockchain framework which is the framework that the Polkadot blockchain is built on, and, in general, the framework that’s used to build pair chains which are blockchains that connect to Polkadot which Joystream itself may or may not end up doing. 

It’s a great framework because it means you don’t have to focus on peer-to-peer networking or consensus or any of these very low-level things, similarly as if you were deploying on Ethereum, and it really allows you to focus on building exactly the business logic that’s specific to your blockchain.

We are using a specific version of substrate, it isn’t particularly new, and the best hypothesis we could really come up with, for which there is limited evidence, was that there was a specific kind of bug in the version of substrate that we are relying on, and that’s the best candidate for what’s causing the failure.
What we’ve been working on for the past two weeks or so has been to figure that out and then to migrate to a newer version of substrate.

### 13, 1.009, 03:53 
![Joystream_Community_Update_1 009](https://user-images.githubusercontent.com/83000549/121137206-053df580-c869-11eb-84ff-45674518a4ed.jpeg)

**Summary:** That’s what we have done. We used to be on version two release candidate four, now we are on 201. 
We are going to be launching a new chain, namely the Antioch network in probably two or three days from now that would be based on a new version of substrate which has benefits of its own, but we are mainly doing it to hopefully resolve this problem.  

We would then get the runtime that we were trying to get initially with these improvements of the parameters for the proposal system.

There have also been some other changes to the way the council work.  It is a bigger council. The council period is not shorter.

There are a few things that have happened that have independent benefits but the main issue in Antioch is to get back to the core, use case that Babylon already had with these small improvements.

And then we are trying to get to Sumer as soon as possible.
It’s a big, inconvenient departure from the focus that we had but we had to do it, and now Sumer is hopefully next within a short while.

## Transcript

Video 2 [Antioch Network](https://play.joystream.org/video/13)

Ok, so what is the Antioch network? 

Now, about a week ago or so…I think it’s two weeks ago now. The time flies. We were trying to make a small not very invasive upgrade to the Babylone network which had been humming along for about, well, I want to say, three months or so. 

Mainly to tweak a little bit of tokenomics parameters.

We wanted to increase the number of simultaneous proposals there could be. Just a few minor things like that to improve the effectiveness of the test net. 
And it wasn’t expected to be a big deal but what happened was not that long after the upgrade happened, so just for context, for people that may not know, the blockchain system or variety that the Joystream platform is built on allows you to upgrade the rules of the chain itself in flight using a special kind of transaction. 

And that’s great for lots of reasons that we’ll probably cover in the future. 

And we tried to use this on-chain upgradability feature at this time, at that time, and that was supposed to be fine but what happened was in a matter of a few, I want to say 20 blocks or so after the upgrade, there was a split in the network which ended up partitioning the validators into two separate polls.
One group thought that the new runtime was in play, and one group thought that the old runtime was in play. 
That is obviously very undesirable. 

The whole point of your consensus system is to have agreement upon what the history and, therefore, the state of your blockchain is. 
So that’s obviously a serious problem. 
And, you know, we’ve gone through a lot of effort trying to get to the bottom of what happened.
Trying to figure out the root cause of live failures and distributed systems is notoriously difficult, in particular if you haven’t actually prepared yourself for trying to debug those sorts of failures to begin with which we hadn’t.
And so, we’ve gone through lots of different iterations of or, I should say, possible hypothesis for what the cause could be.
The best hypothesis that we have at the current time is that there is a specific bug in the version of substrate. 
So, taking a step back here as well in case you don’t know, the joystick blockchain is built on the substrate blockchain framework which is the framework that the Polkadot blockchain is built on. 
And, in general, the framework that’s used to build pair chains which are blockchains that connect to Polkadot which Joystream itself may or may not end up doing. 
It’s a great framework because it means you don’t have to focus on peer-to-peer networking or consensus or any of these very low-level things similarly as if you were deploying on Ethereum, let’s say. 

And it really allows you to focus on building exactly the business logic that’s specific to your blockchain. 
So just mentioning where does this substrate thing come from. 
So, we are using the substrate, we are using a specific version of substrate, it isn’t particularly new, and the best hypothesis we could really come up with, for which there is limited evidence I should say, was that there was a specific kind of bug in the version of substrate that we are relying on, and that’s the best candidate for what’s causing the failure. 
So, what we’ve been working on for the past two weeks or so has been to obviously figure that out, and then to migrate to a newer version of substrate. 
So, that’s what we have done.

We used to be on version two release candidate four, now we are on 201. 
And we are going to be launching a new chain, namely the Antioch network, that’s probably going to be in two or three days from now so that actually wrong on the slides because I just made them a few or a while back.
And that would be based on a new version of substrate which has benefits of its own, I should say, but we are mainly doing it to hopefully resolve this problem.  
Of course, we would then get the runtime that we were trying to get initially with these improvements of the parameters for the proposal system and so on, there has also been some other changes to the way the council work. 
I think we expanded from…Actually I don’t remember now, to be honest. 
There are so many things going on but it is a bigger council.
The council period is not shorter.

So there are a few things that have happened that have independent benefits but the main issue here in Antioch is really to get back to the core, use case that Babylon already had with these small improvements. 
And then we are trying to get to Sumer as soon as possible. 
So, that’s the story on Antioch. 
It’s a big, you know, inconvenient departure from the focus that we had but we had to do it, and now Sumer is hopefully next within a short while. 

So that’s it on Antioch. 
Join me again for Sumer. 

## Video 3 [Sumer Network](https://play.joystream.org/video/14)

### 14, 1.0010, 00:00
![Joystream_Community_Update_1 010](https://user-images.githubusercontent.com/83000549/121414685-809ec480-c999-11eb-9e0e-46a399805691.jpeg)

**Summary:** Welcome to this second installment of the first Joystream community update. This segment is about the Sumer network which is a network we’ve been working on for about three months now. It is going to be building on Antioch which either is going to be released or has just been released depending on when this video comes out!

### 14, 1.0011, 00:27
![Joystream_Community_Update_1 011](https://user-images.githubusercontent.com/83000549/121415044-e68b4c00-c999-11eb-94d0-3a70fb370ebb.jpeg)

**Summary:** The goal in the Sumer network is to do three separate things.

First of all, we want to introduce the next and final iteration of our on-chain content directory.

Then we are going to introduce Atlas Studio which is new part of the Atlas product. 

And then we are going to introduce a new working group which we are calling the operations working group. 

### 14, 1.0012, 00:51
![Joystream_Community_Update_1 012](https://user-images.githubusercontent.com/83000549/121415239-176b8100-c99a-11eb-9058-78000f6a9159.jpeg)

**Summary:** The new content directory is an enhancement over the existing one and through pretty important ways.

The first one is that it is radically simplified. The existing content directory that we had was actually very complex because we were trying to achieve the goal of having the community to be able to update what is in the content directory, like videos and channels, and playlists without having to do runtime upgrades.

So, runtime upgrades, as I probably have mentioned in this community update, is a way in substrate chains can change the rules of the system. So, for example, at one point in time a video has a title, and then at some later point in time a video has a title and also  what language the content of the video is recorded in or what language the people in the video speak.

That is a relatively small thing to change but you want to make it easier for the community to change stuff like that, and if changing every little thing like that requires a community update, it's going to be really hard for the community to iterate quickly on this part of the platform which really needs to be very flexible.

If you wanted to introduce other things, not just videos, for example, eBooks or some other mild variation of what we already have, it would also be very inhibiting if you'd have to do a runtime upgrade because you have to dive into the rust code, you have to change it, you have to figure out how to take all the old stuff in your state and turn it into the new stuff through a migration step that runs inside of the consensus of your blockchain, you have to update all sorts of dependencies and libraries and infrastructure to reflect how the new system works, you have to test a lot in advance.

If the change is significantly big, you should probably also do an integration test where you run through a simulated upgrade with some representative state in your system, you see how it works after the runtime upgrade, if your account still works, if your voting system still works. 

So, it's a lot of work. And if you make a mistake, you can permanently destroy your chain. So, it’s risky, it's hard, and it requires a lot of care.

This is a very long-winded way of explaining why we ended up having the old content directory that we had. The point of that content directory was that it was very abstract, almost to the extent that it was like a relational database where it allowed the community to define schemas and concepts on chain so that you didn't have to do runtime upgrades to define new things or change the way things were represented.

The problem was that it was extremely complicated. It became really hard to both have work properly on chain, it became really hard for people to understand how it worked. It turned out that you couldn't actually get all the flexibility that you wanted.

What we're going to do in this release is we're going to put the heart of what it means to be in the content directory on chain, and then we're going to make the metadata associated with all the different things on the chain, such as videos and channels. We're going to make sure that that's actually very easy to change. You don't need to change the low-level business logic of the chain itself in order to make smaller tweaks that I described, such as the fact that a video may have a language. So, you just lift it out of the chain. 

We just decided that this is the way our content directory is supposed to work. That’s a pretty big decision, and that's what's landing in Sumer.

### 14, 1.0013, 05:31
![Joystream_Community_Update_1 013](https://user-images.githubusercontent.com/83000549/121415711-a37da880-c99a-11eb-817f-dc77e23811c9.jpeg)

**Summary:** Let me go through this very quickly. 

The video of myself which is not that useful is covering up a part of the diagram which is useful. What's supposed to be there is a square which shows the unchanged storage system.

The on-chain content directory has in this representation memberships. Members own channels. Channels have within them stuff like videos, and playlists, and series. All those actually exist in the chain but they haven't been fully implemented, and they will not be implemented in the consumer product like in Atlas itself.

It has the idea of curators and curator groups. These are people who are employed in the content working group to manage and make sure that everything in the content directory is going according to plan, and they can also own channels themselves on behalf of the platform to feature official platform content.

Now the interesting part here is that on chain you have this sort of index of what videos exist, who owns them. You also have an index of what data exists, like the images, the cover photos, the actual video media files. There's like a map basically which holds a representation of who owns everything, how much space has member number X used out of all the space available to them to publish to their channel, and, of course, when the storage infrastructure is supposed to be replicating what part of the data. Right now, of course, that's fully replicated in the current storage system but that would be changed in a future version which I’m going to get to in one of the later videos. But that index also lives on chain in the data directory.

The actual storage is on separate off-chain infrastructure and storage nodes that are also responsible for shipping the data to users. One of the things that actually are possible in this release is for things outside the content directory to also use data. For example, we are aiming to have your membership avatars stored in the same storage system.

Before, for your avatar you really have to reference some URL somewhere. The first step of that in this Sumer release is that you could also store assets like that in the storage system itself, just like the videos for the content directory. Likewise, that could be used in other parts of the system, for example, as attachment in proposals or in forum posts.

It’s going to be a general infrastructure piece for the rest of the runtime.

That's the first part of what we're doing in Sumer on the content directory.

### 14, 1.0014, 08:45
![Joystream_Community_Update_1 014](https://user-images.githubusercontent.com/83000549/121416106-02dbb880-c99b-11eb-8116-0e50286e5d9c.jpeg)

**Summary:** The next step is that we're launching Atlas Studio.

Atlas is a viewer product where you can see videos and channels.

And Atlas Studio is sort of the flip side of that experience where you can actually see all your channels, make channels, upload stuff to your channel, manage it, delete stuff - basically like the channel publisher owner experience.

That really is a very big step in the direction of making it easier for people to publish content to the system which before or at the current time has to be done through a command line interface which is a very rough experience.

### 14, 1.0015, 09:30
![Joystream_Community_Update_1 015](https://user-images.githubusercontent.com/83000549/121416517-7978b600-c99b-11eb-9726-7ccd657dfd76.jpeg)

**Summary:** I think I can show a few outtakes of what that experience looks like.

You'll have  a nice experience for filling in the basic metadata and setting up your channel and editing it.

### 14, 1.0016, 09:40
![Joystream_Community_Update_1 016](https://user-images.githubusercontent.com/83000549/121416697-adec7200-c99b-11eb-9ba4-8e9c1cfb012f.jpeg)

**Summary:** You will have a way to view all of your videos, and change and edit the metadata associated with them.

You have drafts for stuff that you haven't committed to chain locally stored.

This all runs in the browser, just as Atlas itself does.

### 14, 1.0017, 09:56
![Joystream_Community_Update_1 017](https://user-images.githubusercontent.com/83000549/121416840-d70d0280-c99b-11eb-8c54-73a74ed7c8e0.jpeg)

**Summary:** There'll be a smooth upload flow for providing the media files and the basic metadata for videos in a step-by-step way which ends with you signing a transaction which, that's interesting, uses the Polkadot JS signer extension rather than the native wallet or local storage wallet that is in the normal Pioneer product that we're currently using.

That's also step in the right direction of having people use an external key manager.

### 14, 1.0018, 10:36
![Joystream_Community_Update_1 018](https://user-images.githubusercontent.com/83000549/121417017-091e6480-c99c-11eb-8ba4-ed960e0c3c70.jpeg)

**Summary:** As I mentioned, we can store assets now like images on the storage infrastructure, so that means we're going to be helping you set and provide the right assets, manage how they're going to be displayed as part of those upload flows.

I think, it's going to be a very big improvement. 

Atlas studio is the second major goal to launch for this release. 

### 14, 1.0019, 11:01
![Joystream_Community_Update_1 019](https://user-images.githubusercontent.com/83000549/121417193-33702200-c99c-11eb-9ae4-5f7a437c41d1.jpeg)

**Summary:** If you have a look at the experience here for uploading and editing videos, you can see there's a tab system here, because we want to make it easier for people to manage multiple things at the same time.

With that of course comes the need to manage a lot of different uploads at the same time as well, so there would be a separate area to manage all the different assets that are uploading at any given time. Uploads can fail, you could lose your connection, so we'll have a graceful way for you to retry anything that hasn't worked in the past. I don't think we could have had anything reasonable even in the CLI to make this possible.

This is a very big step in the right direction, and it's a huge effort from a lot of people, designers and developers, and infrastructure pieces that are needed to get this to work.

### 14, 1.0020, 11:59
![Joystream_Community_Update_1 020](https://user-images.githubusercontent.com/83000549/121417379-6a463800-c99c-11eb-8137-0af981662bab.jpeg)

**Summary:** Then the last piece of the puzzle is the Operations working group.

I am going to get to what a working group is in a little bit more detail later. 

If you're a little bit familiar with Joystream, you’ve probably noticed that there's the council and there are these groups that are responsible for specific things, and the operations working group is a new group like that, and what's special about it is that it's supposed to be for any kind of activity that doesn't have at least yet an on-chain footprint or a role.

If you're a forum moderator, that implies that you can do certain things in the forum that other people can’t do. There's an on-chain forum in Joystream, as most people probably noticed. Likewise for the storage system. 

The operations group is meant for all of those activities we're currently doing and which will be part of the system in the future which don't really have any direct privilege on chain.

We just want to provide the basics of what a working group allows you to model - what the roles are so everyone can see, it's transparent how people got into the roles, how they applied, what were the merits for people being admitted. People have predictable reward schedules for what they will be paid, they have predictable stake at risk, so they can be given a little bit more responsibility in terms of what they can do, what they can be tasked with on behalf of the group and of the system overall.

So, for example, we have at least one of the founding members, I believe, who is looking to be one of the first developers in the operations working group. In general, managers, marketers anyone who would like a role or a job but doesn't require you to do a lot on chain as VM.
I’m hoping that this will be sort of a sandbox for discovering lots of roles that we haven't explicitly modeled into the system. Maybe we will as a result of what we find out but I think it's high time for something like this.

### 14, 1.0021, 14:16
![Joystream_Community_Update_1 021](https://user-images.githubusercontent.com/83000549/121417531-982b7c80-c99c-11eb-956d-ac9e1ac318e6.jpeg)

**Summary:** Again, my little preview thing is covering part of the image. I can’t move it, so I’ll just try to explain. 

The goal of this is just to show how the working group fits into the overall system of Joystream.

There is some general information in this community update series so I'm sort of straddling the line between very general stuff and stuff very specific to the releases. I think in the future we'll do some deep dives where we try to go systematically through each one of these, and give you a more fine-grained and a thorough introduction.

The governance system in Joystream is actually deeper than what you find in a lot of other crypto systems. In a lot of other crypto systems, you just have a flat coin voting, sort of voting pool which has proposals. Typically, they're actually limited to things like signaling and spending in upgrading the protocol. You don't even really have that rich of a portfolio of proposals to choose from.

In Joystream that set of proposals are very broad. The root of trust for the whole system is a coin vote which happens not on individual proposals but on election cycles where you elect a council. A council is a one actor-one vote where you have council members vote on proposals. I think, the current setting we have for that is every two weeks there is a new council elected. That's mostly just informed by what's practical in order to have new people in the community, learn what's going on. It will be interesting to figure out what that number should be on main net but anyway there's a council which lives for a council period. The same, the members can stand for council, and they can be reelected for future councils.

The main responsibility of the council is to vote on proposals, and the proposals do the things that I've just described, including hiring leads for individual working groups. There's one working group per subsystem. 

There's a membership subsystem at least in the Olympia runtime, which I actually haven't mentioned, but that's the third community update, I think, so it’s coming. Prop is mostly preoccupied with invitations to grow the membership pool. You have the storage working group which is primarily about operating the storage system, storage infrastructure. You have the forum for operating and curating the communication on the forum. You have the operations working group that we are talking about here. It's these different subsystems that run some part of what the overall platform needs to work.

Inside of each working group you basically have a leader which is someone who applies to occupy that role through a proposal to the council. That leader is basically responsible for spending money out of budget that is allocated to that group from the council for all sorts of things.
For example, if you're a storage working group leader then you need to figure out how much money we need for the next month, and then you have to go to the council to have them give you that much for your budget.

The leader is able to pay the rewards for himself and everyone else, all the other workers, as they're called, in the working group, for providing the service to the system. The leaders are also able to change what someone has as their reward and can slash them if they do something they're not supposed to do. The same applies to the leader with respect to the council. The council can update the reward, and slash them, and fire them. 

So, the working group is sort of the lowest bureaucratic organ in the overall governance hierarchy of the Joystream system. And we're getting a new working group in Sumer.

That hopefully was a useful introduction to working groups and the operations working group.



