---
description: >-
  *Assembly AI generated transcripts may not be 100% accurate, listen to video
  for original audio.
---

# April 19th DAO Call

{% embed url="https://www.youtube.com/watch?v=1WlZfVdfVEs" %}

## DJSTRIKANOVA's General Summary

* Dashboard updates coming, maybe live next week
* DoraHacks hackathon being setup, team looking into potential collaboration with other AI projects. Good synergy would be between Ocean Protocol and Effect AI. Have workers build datasets that are posted to Ocean Protocol for example.
* Defibox Special Mining promotion will go live tomorrow April 20th.
* Discussion about AutoGPT with Jesse
* Jesse discussed a general idea to revamp the qualifications system so it can use soul-bound EOS NFT's, this would make qualifications a lot more versatile.

## Assembly AI Generated Transcript

{% embed url="https://www.assemblyai.com/playground/transcript/6omjwn1qkg-eb5e-461c-806f-35234bd32c32" %}

#### DJSTRIKANOVA

Let's go.

#### Rochelle

Okay. Hi everybody. Welcome to the Dow call. Today we have a few things to discuss. I put two things on the agenda for this week's call. One thing is developer update about the UI. I know Jesse will weigh in on that and then box. Yeah, D five box. Mining pool promotion with D five box. So let's get started. I know Jesse has some exciting developer updates, so take it away, Jesse.

#### Jesse

Yes, sure. I'm not sure if it's exciting updates, but I would like to just share the progress in general on the development side because it's been a while before we like this progress of this epidemic progress for a while and it's been a while since we released anything. But they're still brewing. So there's a few things happening right now that we're actively developing. It's been going a bit slow this month because we had some of the developers not active. Like David is on a holiday, lawrence is out of the running for a few weeks. So, yeah, the team has been on the development side a bit lighter, but we have been progressing quite a bit. One of the things I'm pretty excited about, because it's almost ready, is the Dow Dashboard update. It's got to look a lot fresher and more logical. I think that part we already discussed before, what it entails in general. But we've added some things like the profile pictures from Atomic Assets, basically NFTs and EOS that can be used as the Dow profile pictures. We've made it so that you can whitelist a couple of collections so the Dow could actually, through a proposal vote of which collections to add or remove from the allowed collections that you can choose from to set as your profile picture. So for the default, we will just pick, I don't know, just kind of a nice selection of the collections that are supported. And those will be the ones that you can select in Edit Profile for the picture to set. And the Dashboard will have things like an ATP selection interface. So when you create a proposal, you can select what kind of ATP you want to use. So that will make it a lot easier for anyone to create different types of ATP proposals. Right now you have to manually craft the ATP through the comment line or through blocks, which is a little bit tricky, and then add it to the proposal. But in the new interface it will be kind of more smooth. So that update is coming. I don't have a definite date yet, but we will have some support, some more developers working actively from Monday. So this week it's mainly me doing some of the updates. But I think like end of next week is when we will have a kind of big update available for preview, for comments before we actually finalize everything. And we're also developing stuff still on the platform side. Obviously we've engineered like it's not going to be a new version of Effect Network of the whole application, but the architecture is going to change in a few ways because right now we're encountering these bottlenecks where basically the front end of App Effect Network is always fetching all the submissions to figure out what campaigns can be joined by a worker. And it's causing us a lot of trouble because the notes are often quiet. Like the RPC notes we use are quite restricted in how quickly they sync or how many requests you can do. And it's causing some issues that it takes a long time to load. Joining a campaign can be pretty time consuming. So with this new architecture, we made it so that the smart contract will basically hand you a task when you call the reserve task action. It's kind of a technical deep dive maybe, but compared to before, the front end had to figure out what task can I reserve? And that's why it needed to fetch all tasks. And in the new architecture, we've reverted that to basically say the front end just tells the smart contract, give me a task and the smart contract will figure out what task to give. So it means that you'll never have race conditions. It will be really quick that fetch all the submissions. It's like after some discussions with Lawrence, we just suddenly saw the light and the solution popped up and we're going to architecture it that way, which means it will be way more performant to do tasks. But this update is also coming along pretty quick, so we're looking to release that, to release that also in the next few weeks. But those are the two major things that we're sort of still wrapping up that are taking way longer than we wanted them to take. But those should be out pretty soon and then, yeah, they're open for feedback. But of course we're also really excited to work on the next things coming up. But this was mainly the update for the current State of Deaf update, what we've been working on and what's coming up, like end of next week.

#### Rochelle

That's a great update. Thank you. I wrote notes and I'm going to write that up in a post here in the server as soon as the call is over.

#### Jesse

And we will also start because these things have been brewing for way too long. I'm really eager to get them out, but we will start doing weekly updates on the dev side again because we have quite a good roadmap now and we will have some devs working dedicated. So we want to do the weekly updates on the dev side as well to keep everyone in the loop on what's coming up.

#### Bree

What's one of the next things you'll be working on?

#### Jesse

Yeah, good question. There's a bunch of things like this is not set in stone, but it's always good to talk about. So one thing is a hackathon that we're structuring. So yeah, that's going to be an important one and incorporating we have a few big items on the roadmap for what's next up, but there is working on the mobile interface and making the worker side way more accessible. That's one that's sort of been in R and D phase, but we're considering picking that up. And there is also some ideas right now on making the AI marketplace element more R and D, more on that and come up with some kind of system for how that would fit into the current place. What we've been thinking about now and what the platform supports would be like to add AI sort of workers in the system that can make it really convenient for if you're making, for example, a campaign that does image classification or maybe translation surfaces, you can have workers do the translation surface, but you can also have algorithms to the translation surface. And the nice thing is that because we have a human in the loop, we can have the algorithms more tightly integrated with the platform. So it should be like having the human in the loop really close to the AI because right now it's kind of complicated. To get data from an AI into the platform, you need to set up a manual bridge, I think digestrik and OPA. You're working on an NFD labeler that's also using AIS to label the images. That's one element that we would love to work out further once the, once the platform is more solid running and of course getting tasks online. So we have a few that's also what the hackathon will be for and the hackathon will have like a theme as well that we're still working out altogether. We also want to of course discuss it with the Tao soon and yeah, having more tasks online is also a major importance. But we think the AI integration element, for example, the hugging phase integration or there's a few proposals that came by to make sure we have all features needed and all documentation needed to facilitate tight integration. That's also part of the next up roadmap. So it's quite a bit, but just to get you some thoughts on it.

#### Rochelle

Good, thanks.

#### DJSTRIKANOVA

I know the qualification system could use more love setting it up, making it easier to do.

#### Jesse

Yeah, that's a really good topic as well. So what we thought about was to replace the qualification system completely with NFTs, with atomic assets, which means that we can basically remove that part from effect network and use NFTs as a qualification. There's already some libraries, SDKs interfaces to quickly create a collection or to create and hand out NFT and it would make the codes and simpler. Right? Because right now qualifications are kind of incomplete, they're not working really smooth. But there are also quite a lot of code that's in our code base. It's not ideal, right? So we're thinking to replace it with atomic assets and create a really nice interface around setting up these NFDS. And the cool fact will be, of course they can be solbound atomic assets, right, so that they're by default non tradable. But by swapping it with atomic assets we might be able to create a way more sort of accessible, convenient interface for it. With the upside, you can also see them and they'll feel a bit more like rewards as well.

#### DJSTRIKANOVA

Yeah, I remember talking with David how in the NFC itself you can have parameters and so if you just set the parameter of who created or who the NFT is assigned to, then you can just check it's valid for the user so people can't just send it somewhere else and it becomes invalid. Though I guess the only thing is it would only work on EOS. It wouldn't be transferable, would it, to binance smart chain? Or do you think it could work also?

#### Jesse

You couldn't transfer them to binance smart chain but at the moment we sort of mirror so we have our own account system. We're keeping all the accounts mirrored on EOS so every binance address that's on the force also has an entry in the EOS table. So we could actually have give them the NFDS as well. So it would be compatible. We would make an NFD for fee accounts element. The fee accounts can already handle that so that shouldn't be too tricky to have it work on both systems. But we cannot use NFDS on the binary smart chain. That's a pity, but I think still compared to the current system, we would basically get a way better system with less effort than making a new system ourselves.

#### DJSTRIKANOVA

Yeah, the other ideal of that is I know there are Dowels on EOS. Like you have the for example, the shoot, I just forgot their name, they have the meetings with the video.

#### Jesse

It's a dow on EOS, I'm thinking. You don't mean EOS, Doc. Right, that's been quite a while back. I think that they were active.

#### DJSTRIKANOVA

Oh, EOS Eden. Yeah. The Eden.

#### Jesse

Eden, yeah, of course.

#### DJSTRIKANOVA

Yeah. So the members, they prove that they're people and they get like a profile picture as an NFT that represents them as like a member that votes. And so I think NFTs could definitely improve qualifications a lot because it could also allow other groups, for example, let's say Eden dow wanted to sponsor some tasks to do something, but they want to kind of be, let's say, protectionistic about it in a way and only allowed for their Dow members to do it right. That would allow them to designate you have to have one of our NFTs to do these types of tests and that will be totally possible if we can get NFC integration.

#### Jesse

Yeah, exactly, that would be compatible straight away then with doing tasks on the platform.

#### Bree

For BSE. What about partnering with Air NFT which are on BSE or some other NFT platform that's on there.

#### Jesse

We could check it though for the BSE side. Like DJ mentioned, the BSE NFDS will not be compatible with Effect Force platform, so you cannot set them as profile pictures or either we won't be compatible with them. What we might be able to do, and that's something still very much unclear what exactly needs to happen but to integrate with EOS EVM. I'm actually wondering a little bit what the traction is on the EOS EVM side because they did have a really large funding funding available there and I haven't really followed closely. But I'm wondering about what attraction is. Do you guys know if that's going well? The eels EPM side.

#### DJSTRIKANOVA

Well, I don't know about metrics, but they did get big, what is it called? MultiChain or basically a big bridge service that has hundreds of tokens bridged. They're going to include EOS EBM and I know Finance, they've been working on making sure it would be compatible with the biggest exchanges. But in regards to actual DAPs, I've seen the in the house DAPs, they had the Door hacks hackathon for they're being built. Their focus has been a lot on the GameFi, so I'm not sure they're kind of been mum about it. But I know I asked this question to Yves and he said there's no real application for the funding, you just need to contact them directly. So I think you said you do that a while ago and see if maybe there's some collaboration that a SEC network or a SEC Dow can do on the Osevm. I personally suggest see if we can get funds for price pools on the Door hacks hackathon, which that's also I guess we can discuss this Dow call. I guess now it's not that tricky getting the Dow funds because we can use the ATP to send it.

#### Jesse

Yeah, for sure. Yeah, that would be good. I did reach out to them before. We should definitely try if they want to invest a bit in getting effect on the EVM side or integrate with the EVM side. I think that could be interesting for us if there might be a user base there as well. So yeah, definitely worth exploring. I'm going to double follow up on that side because I didn't get a reply from them yet.

#### DJSTRIKANOVA

What are you thinking for the hackathon? I think you've set up the organization now, right?

#### Jesse

Yeah, Gabby set up the organization for us and did filled out most of the fields. It's already like I'm not sure, I think it's already popping up in the hackathon list though. It only like we put the start date really late. But the platform looks good. I think it looks great. The features and the interface, I don't know if you got what you thought of it.

#### Gabbrielle

Yeah, it looks really good. We did a test one, everything looks fine. We just need to figure out the details, like the description, what's going to be the title price pool and all of these things. We're going to see if we can partner up with some other AI project in the space. Also, we're just figuring out details, but yeah, the interface looks really good and their customer service too. So definitely using door hacks.

#### DJSTRIKANOVA

So then we're thinking then of an AI team this time around, right?

#### Gabbrielle

Yes, 100%.

#### DJSTRIKANOVA

Because I feel like you mentioned I have a post on a forum post about my NFT project. So I made a lot of progress and I figured out and yeah, like, hugging Face is really great and how easy they make it for you to use AI models. You really just call one line and import it and then there you go. You can do image recognition. Kind of blows my mind. So I was able to collect all the NFTs on EOS, like the assets, and then download from IPFS all the images. And I was able also to because there was only 20,000 about unique IPS hashes for the 2 million NFTs, which is interesting. And anyway, so I was able to process them with my 30 90. It took I could process about 5000 images in a day, which, I don't know, I guess it's going to be harder to scale for Wax, but I have enough to fully process EOS, at least. The idea I had is that the next step could be for Effect workers to rate these captions then, because the model I use, it generates a lot of phrases and it goes from, I think from the most confident to least confident. But for searching, I wonder what is the optimal amount? Like, for example, is one phrase best or maybe two phrases is better? So yeah, I think for my specific project in the future, if I do Effect Network integration, I think I'm going to focus on having it so that workers can rate the captions for specific model and also between models. Because it's so easy to just swap different models. If I can just get like four different captions generated from different models, we can figure out which captions users in general rate that's better for describing the content of an image. So I think there's a lot of stuff in regards to that that can be done. And finally, the goal after that would be on Ocean Protocol. I feel like there's a very good marketing strategy here where we can publish Effect Network source data sets on there. And even though Ocean Protocol is very big, the actual data sets they have are still the same ones I've seen there last year. They're either public domain stuff that governments publish or they're like finance data, like defy data, which I guess is important, but it's definitely not like a complete marketplace yet. Right? So I feel like if Effect Network could advertise itself by showing off, that can create these data sets where you have AI data rated by human workers. I think that could be a good way to have people get eyes on us.

#### Gabbrielle

That's a really good idea. I actually have the contact for Ocean Protocol so we can talk something up with them as well.

#### DJSTRIKANOVA

Yeah, you could make it. I think what you should allocate is making data sets that are postage Ocean Protocol but are made by Effect Network.

#### Gabbrielle

Yeah.

#### DJSTRIKANOVA

Because that would be then very synergistic.

#### Gabbrielle

Yeah, I'm just writing this down. Nice. Very good ideas as always. You got your hackathon entry ready? Pretty much.

#### DJSTRIKANOVA

Oh, I can't participate myself. That would be yeah, I'm one of the biggest members.

#### Gabbrielle

Yeah.

#### Rochelle

I have a draft description set in there I need to upload now that Gabby's made me an admin to the page. So we'll be adding that in and then looking at all the other fields of writings that need done. So I think once we get a pretty good draft, I think we'll have some more Dow debate on or input on what to officially title it. But it's in the early process and it's shaping up nicely so far. I really like how their platform is. It's really nice. Better I think than the other place we used before. Suits us better anyway. I should say the other platform is great, but this one's better for us.

#### DJSTRIKANOVA

Yeah. And then also in your notes you're writing down now, I'll be on the Fireside chat. Stefan scheduled me for a slot to give Effect Network updates, so you can also add any stuff you want me to talk about.

#### Rochelle

Super cool, super cool. Oh, and the next thing event I should say is the thing with DPI box, the mining pool. So in our chat I got the image and link from Raven and I did a pull request to get our website updated with the D Five box link and image. And GitHub is taking a while. There's something going on. It's been sitting there for 5 hours now, so hopefully maybe overnight my time it'll update and I think his team is going to work on setting up a Twitter spaces for us. So get some updates more on that and let everyone know what he says. But it's looking pretty cool I think, so far.

#### DJSTRIKANOVA

Yeah, it should be pretty good for hopefully it can encourage some Dow members and then other people who just interested in EFX to stake.

#### Jesse

Yeah, nice, that's a good promotion. So hopefully we can also do an AMA or something with their community. But it looks like that's getting off the ground pretty soon, I think already in the next week. I don't remember the date but it was already in April.

#### DJSTRIKANOVA

Yeah, the 20th is when it goes live, I think. So tomorrow.

#### Jesse

All right, tomorrow awesome.

#### DJSTRIKANOVA

And it's also being recycled, so I don't know, I guess in the sense that basically I wonder if the promotion with Box, the token itself will be three months, but the question is, would we want to also continue just EFX rewards? I'm thinking yes, it's good to split up so then we have a presence both on Binance marching and EOS good pools.

#### Jesse

Yeah. And I think the farm you were talking about the farm, right. I think that one is not funded until like October or something, so it should be lasting for quite a bit longer.

#### DJSTRIKANOVA

Yeah, the Bion smart yeah, the BSE farm and so yeah, basically, would we want to continue defy box farms as well? I guess we'll see how successful they are. I think at the very least the problem with the Binance smart chain farm is, I don't know, the best finance smart chain community to really advocate it for. Right. It exists on Pancake swap, but the community itself, of which it is vast, it's hard to really kind of get into it, though. I do know that occasionally people from buying that smart chain jump in chat and stuff. Right?

#### Jesse

Yeah, I agree. I'm also not sure, I don't think there's a big community of people in buying a smart chain that are I think people do enjoy the liquidity on pancake swap, so probably traders right. Which is a different type of community than people, like using the platform or joining in discord and stuff. But I think trading wise, buying a smart chain is really popular as being used. I think we should just at least keep that one going. Maybe I don't know if there's going to be another farm round because we've been doing the farm for a long time, so maybe we can think of something else than that.

#### DJSTRIKANOVA

Yeah, I wonder if maybe we can keep what the team has on there, but then for dial members, maybe it's better for them to transfer to EOS. I don't know, I guess it's something we have to figure out.

#### Jesse

Yeah, I think maybe it's good to recommend people to be more on the EOS site as like the primary way to because I think the EOS side is more where we are, so maybe that should be the first recommendation. Like if you want to stake, that's the place, I think that makes sense. And people that don't want to be on AOS, they can go to binance smart chain because it's maybe MetaMask and everything, maybe it's more accessible to them.

#### DJSTRIKANOVA

I also made another thread here, I pinged you, I don't know if you saw it a couple of weeks ago. Bias Marching has adapt bay, so like its own, I guess index of DApps and I think FX Force wasn't on there, so if we can get on there too, that'll be good.

#### Jesse

Yeah, I was just checking the link. Nice. All right, let's get registered. I copied the link and we'll register there.

#### DJSTRIKANOVA

Yeah, they also have builder grants as well. We should still keep because we already have the bridge and everything works, so we should explore binance smart chain, see if we can get some traction there as well. The thing is, the Binance Smart chain does have a big community EOS. There aren't that many, though. It's kind of interesting. There's a lot of upside to EOS. They're building out the EVM, but the audience itself is not as big. But I think on a side note, the hackathons, I think I'll be able to just talk to individually and send a message to everyone who participates on Fellow and stuff like that, which could help us increase the pool of participants once the hackathon comes around.

#### Rochelle

I think since we've been around the Camillo community and stuff, I think that's a good audience to try to get people to join our hackathon from. I mean, these are builders and crypto builders, where it was really hard for us to get recognition and traction with the builders and the people who made things and tried to participate in hackathons on the other platform. Yeah, the pomelo page. It's going to be a great asset for recruiting people to try to build on our platform who are already around EOS, too.

#### DJSTRIKANOVA

Yeah, and it'll work great. Even if we have the Ocean Protocol, which is like, I think Polygon based effect network still works on EOS, so it's still like an EOS. It's like EOS and polygon, like, both really are used for something like that.

#### Rochelle

Sounds good. I think that's everything that was on the agenda so far. Anybody else have anything to add? Okay, what do you think? Are we about done? You think my mic working?

#### DJSTRIKANOVA

Yeah, I hear you. I'm just thinking making sure. Anything I forgot? Yeah, I think it covers it. Yeah, just make sure. Is there anything that any of you would like me to mention during the Fireside Chat? Review the articles you wrote and post them.

#### Rochelle

Oh, nice. Thanks. Yeah, those are good ones, especially for the AI stuff. No, I think what you have already planned and then a few things that we discussed in here I think are good.

#### DJSTRIKANOVA

Yeah, I think I'll just say if anyone will just be I'll just ask if anyone how interested to be in the hackathon and what they think of it making data sets, but yeah. Okay.

#### Rochelle

I'll message the draft I have so far for the hackathon description. It might help when you talk about it. Coming up.

#### DJSTRIKANOVA

All right.

#### Rochelle

Let'S paste that over to you real quick.

#### Jesse

Hey, sorry, can you guys hear me now?

#### Rochelle

Yes, now I can hear you.

#### Jesse

I think not working because I don't know why I have to sometimes with this card, but awesome that you're going to be on the Fireside Chat DJ and that you got a slot, I think yeah. Really cool. If you can mention the hackathon, that would be great to already get some.

#### DJSTRIKANOVA

Well, Stefan from there sorry to interrupt you.

#### Jesse

Go ahead.

#### DJSTRIKANOVA

I was saying Stefan pinged me because he read your article, Rochelle, so those articles actually do have some traction.

#### Rochelle

Oh nice.

#### DJSTRIKANOVA

He was like, hey, I read this, do you want to talk about it? And I couldn't talk about it last week because these construction workers were like jackhammering outside my house at like 07:00 a.m. In the morning. So I was completely out of it. I also rescheduled, I completely forgot about it. But yeah, so I'm much fresher today.

#### Jesse

Awesome. Maybe one, one item I wanted to just mention. There's one proposal I put up today about it's the last farm. So actually if we complete this one, then the farm will be fully funded, which is awesome. So we completed the full year funding of the farm after this one.

#### DJSTRIKANOVA

Yeah, I don't see any reason it wouldn't pass. It's good to finally have it ready. As for the ATP, I think before we talked about refactoring how the treasury distribute funds, remember?

#### Jesse

Yes, that's still coming up, that discussion basically. So we do want to actually mention this as well at the end of the call, but I asked around in the EOS community about some way to distribute tokens, like in a vesting streaming way, where basically every second some tokens get released. And I couldn't really find a solution. But I got some help from some people from the community that pointed me to some programs and I was looking into, and I think I can actually quite easily write my own sort of smart contract for this, where instead of having this quarterly release of Tokens, we just let the treasury release, like, every second. So continuously release a few tokens to the Dow and we don't have to worry anymore with budgets. That's basically what I'm sort of working on now. So I'm making that program as sort of a proof of concept where there will be a continuous stream of tokens from the treasury to the Dow and we can basically change the rate maybe with a proposal or we just fix it forever on a similar rate that we currently have. But if it's every second there's no more like these quarterly or weekly or bi weekly transactions that have to be authored. But it will just be continuous, which I think will make it way more nicer and we can visualize it nicer and it's easier to understand. And cycles would just be for voting only. But it has nothing to do anymore with budgets or with stuff like that. That's my latest thought on it, but I'm totally still actively working on getting that proposal out.

#### DJSTRIKANOVA

Would it require like claiming?

#### Jesse

Yeah, it would require claiming. So basically anyone will be able to claim at any time and then the amount of tokens would be released that are currently claimable, which is like how I have it in my mind is to have it on a per second basis. So the emission would be x amount of tokens per second and we could sort of secretly embed the claim in certain transactions. So we could, for example, when you do like a fee pool claim as a Dow member or when a new cycle starts or whatever, we can sort of embed the action in there in the user interface so it would sort of be seamless for the end user.

#### DJSTRIKANOVA

And then the other thing that we would combine with this is I think we would want to restructure how the because I think one of the first few proposals was like, of the unused budget, 30% was it goes to the people. On average, it's pretty much the same. I think we can just make it a flat amount and then with that, I don't know if that can be programmed to, at the end of every cycle, just take X amount and distribute it to the people.

#### Jesse

Yeah, that would also be a solution. Because that's the problem, right? If we remove budgets, because that's basically that we remove budgets from cycles and then we don't have the leftover anymore, so we don't like that sort of that doesn't fit well with the system. But we can definitely either pick a fixed amount or yeah, fixed amount might be nice.

#### DJSTRIKANOVA

Yeah, they can just be a fixed amount. And then the Dow can set the amount of ATP. But otherwise at the beginning or I guess that's a good question. I guess at the beginning of every cycle it transfers it into the people. Maybe something like that.

#### Jesse

Yeah, that could work. Maybe. I'll think about it. Definitely. I really want that to be automated. Right? Like that it goes automatically at the end of the cycle, for example. Yeah, that would be great. That would work. I think also for this, I think I want to write out like, a proposal and I'll discuss with you guys in discord. But then instead of voting on every little part, just put a proposal out that sort of encompasses all the changes and have discussions on the Dow calls about what would be a better alternative to some maybe approaches. But I'm writing on sort of the banker, like, the baseline proposal. And from that point we can discuss it. But this one is still open. How do we do the recycle? Right? How do we get the fee pool tokens there? But I think that's a great suggestion, DJ. Yeah, I'll take it into account. I'll work it out, maybe. I think that could work.

#### DJSTRIKANOVA

Sounds good.

#### Jesse

Cool. I think that's it from my side. Like, no more topics. If anyone has anything that he wants to bring up I have a few more minutes here before I have to leave.

#### Rochelle

Forgot I was muted. I think we covered everything. Been a great call.

#### DJSTRIKANOVA

This isn't really effect related, but jesse, have you tried out auto GPT?

#### Jesse

I haven't tried it out, but I was reading their GitHub. It's on my list. It looks really cool. Yeah, they automate, like, they use GPT to basically automate, like interacting with the Internet, right? You can do Google searches and write stuff and do like, actions online. It's been like, high on my list. Does it work? Well, I see all these cool things come by on Twitter about it.

#### DJSTRIKANOVA

It's working in the same way. My project I've been working on, it can work pretty well for general tasks, but if you want something really niche, it's going to struggle because I tried to get it to find the best crypto projects to collaborate for Effect Network, and it struggled to find any. It did find Ocean Protocol, which I already knew, unfortunately, or I guess fortunately to the doomers who think we're going to turn into paperclips next year, are kind of overestimating the capabilities of it. But at the same time it is, I think, novel because yeah, you're basically just letting GPT Four evaluate itself. Oh, actually, that's another thing. That's the thing. It would evaluate itself to see whether the task was completed. But sometimes it will just lie and say, okay, it's done, and I say, no, it's not done. So, yeah, there's a lot of refinements, I'm sure, for this type of thing. I think it'll definitely be useful for researching because I think it's basically a higher level web scraping, in my opinion. Because not only are you downloading all this content, you're also having QPT Four analyze it.

#### Rochelle

So the model is like an eight year old child.

#### DJSTRIKANOVA

What do you say, Michelle?

#### Rochelle

So the model is like an eight year old child right now? Yeah, I did it. Yeah, exactly.

#### DJSTRIKANOVA

Yeah, I know Brie mentioned and Mark, a guy named Mark had the idea of somehow integrating Effect workers in it. And I'm not sure, like, programmatically any idea of how to do it, but I feel like in general, with the state of AI, humans will be more like the managers kind of evaluating, monitoring the AI to make sure it's actually doing what it's supposed to do, making sure it doesn't go off track. So, yeah, I feel like that's definitely going to be like a niche that we should fill through the long term.

#### Jesse

Yeah, and I was looking at it and just thinking it would be cool if we can add a plugin or something where it can tap into Effect Force, maybe. Because then because it makes mistakes. Right. And I think I want to sort of try it out and see what kind of mistakes are common. But if we can sort of have a proxy where you put an Auto GPT task on Effect Force and then Auto GPT does it and the result comes back into Effect Force, but then there's actual some workers that are either evaluating the steps it performed or evaluating the end result before it comes back to you. So there is some human validation for the test you put out. I was thinking, like, that would be cool. And I know that Auto GPT has these plugins where you because for a Google search it knows how to do Google search and feed it back, right? So we could have like a plugin where it does something on Effect Force and then feed it back. So there is this human, while it's doing the task, some feedback so it doesn't go off trail or to avoid common pitfalls or maybe when at certain tasks that are kind of important. Like I can imagine if you do something like to post an order online or even to do trading or to write an email if there is stuff that's kind of high risk that you don't want it to accidentally miswire misunderstand and do something stupid that you can add the worker in there. I was thinking about it if that would be a nice plugin to have. And then if people can just install Effect Force and have the validation part for their outer GPT tasks, that could be like a cool way to integrate as well. The human in the loop.

#### DJSTRIKANOVA

Yeah, as you said, the main question is basically the unknowns. What if you give it ten K E FX and then it generates like a template for a task that pays out 10,000 for something? It would definitely need to be something like tuned to be try to waste your money. But yeah, maybe it's something a theme for a hackathon as well because the auto GPT stuff is really new.

#### Jesse

Yeah, that's even a step further where auto GPD could post tasks. I was more thinking about what if you have auto GPT send an email, right, to a person, but you do want to make sure that that email isn't like insulting or gibberish or something because maybe you don't fully trust auto GPT yet. So then maybe we create a new like instead of sending an email, it would be like send an email through Effect Force. So it would send an email, but it would first need approval from Effect Force before it would send actually the email. So we sort of hard programmed the requirement for human validation in some steps, something like that I was thinking about when I was checking out the GPT, but I definitely have to first try it out and see how it works.

#### DJSTRIKANOVA

Yeah, there's also just a browser, like front end, so you can download it and I guess it's less feature and test compared if you like programmed everything. But in the browser you can set the tasks and it just goes until you stop. Tell it to stop or it believes it's completed the task because it uses your API key from OpenAI GPT. Four one, not the subscription, but the API, which is separate. But it's pretty.

#### Jesse

I'll check it out. It's nice if it works in the browser.

#### DJSTRIKANOVA

If you want to test it, it only costs like maybe $20 for a day's worth of testing, which is what I did.

#### Jesse

Nice, I'll check it out.

#### DJSTRIKANOVA

But yeah, I guess the last thing is this is something you were talking about earlier. I like the direction you're heading with. So basically because of Effect Network, the workers, while assumed to be human, don't have to be. Right. Because the tasks itself are all programmatic. Right. And we actually have qualifications to prevent bots from completing tasks. Right. So basically what you're thinking of is having APIs connected into Effect Network essentially, right.

#### Jesse

Exactly. Yeah. We want to have in the end is basically have something like Chat GPT working on the platform. So there could be campaigns that are basically operated by both. There would be like qualifications exactly. To figure that out. And then it could be subsequent campaigns that are like human expert only. And that's the real value there when you can add those up. Because there would be quite a cheap first of all, it would give a really cheap initial iteration of your task if Chat TPT would do it. So it's cheaper for people to post it. You would get quicker results. It gives like this unified interface because we would like interface the campaign would basically interface the Jet TPT. This is just as an example. I don't know if we actually use Jet TPT, but it could be any model behind it and you would just pay any effects. Right. So it would give you this unified interface for paying and managing for your data flow, basically, which would be cool. But also, then the human in the loop could be in the task after you could actually have a human still validate or do a task after that. But I think that having AI operate on Effect Network is where we want it to go. Of course. And now it feels like there's so many models out there that are so useful that we can actually put it in practice pretty quickly. If the smart contract is actually really working well, as it's supposed to, then we could hook that up. Yeah, exactly. And also the other way around. So having AIS on the platform could also mean it could like for reinforcement learning and stuff, it would be nice if those integrations are really smooth. So if AIS are actually on the platform, they can work on the platform and they can post tasks on the platform. Then the iteration for feedback and creating data sets or validations of outputs would be sort of a natural way to integrate.

#### DJSTRIKANOVA

Yeah, because with my script, I have a Python script that connects to the hugging phase stuff and yeah, the only tricky part is because the Sfjs is in a node module. So I'm not sure the best way to connect. I'm sure there is a way because basically the machine learning community, they love Python. Like everything has to be Python. It's kind of funny because as a web developer, everything was like everything must be JavaScript. Front end, back end, everything must be JavaScript. And then suddenly, boom. The Python people came in, they're like oh no, it's like when I guess actual competition again between languages.

#### Jesse

Yeah, true. So this definitely means we need a Python module for Effect Force, which is also something yeah, that wouldn't be too complicated. We have of course the SDKs and TypeScript, but yeah, we would need to create a Python version of that to integrate with hugging face and machine learning communities. But I think that's doable basically rewriting that TypeScript one to Python. And Python isn't the hardest language. It's really accessible for creating these types of integrations, but it's a good one to put on the roadmap as well. Like the Python Effect SDK or maybe give it a better name, but that would be a nice release for machine learning communities to easy use the platform. I think we need a few things in place to make that really work out, but definitely the Python version is quite a big step forward.

#### DJSTRIKANOVA

Yeah, at the very least it'll make it integration much easier because I plan to do the throughput is good because at some point I do plan to make tasks with this data set I'm building to rate the captions. So yeah, I already built out a tool to communicate with Effect JS and generate campaigns, but it's all in node JS. So for now I'm just going to use a database as the intermediary. So it just scans the database for something new and then it can check do the tasks. But a Python probably will help everyone in the machine learning community who is not familiar that much of JavaScript and TypeScript. I guess even I'm like TypeScript is just more strict JavaScript, right?

#### Jesse

Yeah, exactly. TypeScript is just JavaScript more strict with like JavaScript is a lot of these it's just such a strange language with how it processes things like equalities and stuff. TypeScript just makes more sense and you can have type safety and stuff. I think it's just a better layer on top of it.

#### Rochelle

It is the hour mark and I unfortunately have to go. I can't stay on to chat anymore. But good luck with the try to listen to it.

#### DJSTRIKANOVA

All right, I think we covered everything. So see you all in the next dow call.

#### Rochelle

Bye. Bye.

#### Jesse

Yes, see you next dow call. Nice one. Cheers. Bye.
