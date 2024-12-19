---
description: >-
  *Assembly AI generated transcripts may not be 100% accurate, listen to video
  for original audio.
---

# March 8th DAO Call

{% embed url="https://www.youtube.com/watch?v=ueoTgGxc3wc" %}

## DJSTRIKANOVA's Summary

* Team is working on upgrading task architecture so things work faster. More people can work on tasks simultaneously and less resources used EOS side.
* Team is working on a DAO update that reconfigures how cycle logic works, this would get rid of a lot of manual things that need to be done.
* Rochelle and Gabby are working on the marketing promotional content.
* David posted on discord a rough draft of his Pomelo grant idea for Effect Network - HuggingFace integration, feedback encouraged
* Jesse says he's enthusiastic about EOS and learning more about EOS EVM. Being able to adapt relayer to work with EOS EVM is being looked into.
* I discuss my grant https://pomelo.io/grants/nftindexer all donations appreciated.
* Emoji competition proposal passed, Bree in talks with .gems people to hash out a plan
* Defibox proposal passed, ATP will be used to send EFX over.
* Effect DAO site has new socials page, which shows endorsed entities as requested in prior proposals (Telegram and Discord icons shown too)
* EOS EVM Mainnet beta launches April 14, 2023

## Generated Transcript

Bree

There was one more thing to add to the agenda, but I didn't put it in there, and that was Richard's request for promotion information.

David B

Okay, that's fine. We'll start off with that. Hi, everybody. Welcome to the 8 march biweekly down call for the Effect network. Today we'll be discussing four agenda points and one proposal. We'll start off with the one that Brie forgot to add, which is Richard request. I'm sorry, Brie, but I missed that last part.

Bree

Promotion material for his upcoming trip. Maybe Alex can help me out with this too, because I'm going by memory. I have to go back into Telegram and see what he wrote.

DJSTRIKANOVA

Well, I think I asked Rochelle to work on it, but I don't know if she got to it. Last dow call. Well, this is related to the defy box proposal because they wanted me to give them materials that explain Effect Network and Effect Dow. Are you able to work on that, Rochelle, or should I start working on that?

David B

I can remember that David was also involved in the conversation. She would also provide Richard with some.

Bree

Details about he was wondering if it had already been done or if it was in progress, rather than needed to start the conversation. And he was needing some feedback on the progress. If I remember, I went skiing this weekend. Rochelle, are you not able to talk? It's in progress, she says. Okay. I think that's all he wanted to know. He's got a timeline.

David B

Yeah, indeed. I'll double check with Gabby, see how far along she was with making that content. I assume she already sent it, but I'll double check with her.

Bree

That would be great. And then if you could get her to contact Richard. I know his trip is upcoming. It's not like it's six months from now anyway. Okay. So I said I would do my best. That wasn't very good. There you go, Richard. He's going to listen to this.

David B

Okay, the next agenda item is it's been super quiet by the team on the socials lately. This assumably means that they are really busy. Please do let us know on what's been happening.

Jesse

Hey, sorry, I can answer that's a question. Has it been really quiet on social? I haven't been personally too much in discord lately because we have been very busy. Bit distracted. I've been sick myself a bit as well. So it's been a bit quiet, I think, on the social content has been going out as usual, I would say.

Bree

I think maybe just for a moment, because I'm not really thinking of Twitter. I'm thinking of you've been sick. Well, that makes sense that we haven't heard a lot from you. Right. More direct comments on this bird.

Jesse

Right. And it has been a bit quiet. There's been a lot brewing. So I would love to talk about a bunch of the things that we're working on, which are maturing a bit that they will come to life pretty soon, but they're more like improvements and sort of planning bigger projects that you want to release that they'll be coming out. So there's a few things me and Lawrence has been doing work on restructuring some of the task layer of effect network because we were hitting some issues again where tasks weren't going so smooth. And at some point we sat together and we figured out a new way to make the task go, like the reservation system and the payout system to make that part way smoother. So we've been working on that a bit. We'll write down the entire update that's coming out. It's mainly going to make things way more quick and basically cheap on the EO side so there won't be any more like if multiple workers want to work on the same tasks or have a lot of reservations or like we had this issue with qualifiers where there is a limit on the number of repetitions. We basically want to solve all of that with an update. On the smart contract side, that's one thing that we've been working on a bit quietly because it was more of a braid store that expanded into something bigger or at least we just found a solution that we didn't see before, but that's going to come out at some point soon. And on the other side, I think for the Dow, there is a lot of improvements that I've been mainly working on and I actually wanted to put them out way, way earlier as proposals or at least bring them up for discussion, which I would like to do. I think I'm done. Maybe if we go through the agenda a bit more, I would like to discuss some of them here as well with you guys, just to get some early feedback and see what you guys think. So yeah, that's something we've been working. I know Gabby has some updates on the marketing side she told us about last time. She's working with Rochelle on some cool stuff. I think maybe Rochelle wants to highlight some of that already or maybe she wants to wait a bit more till it's worked out before she shares. But there is some plants there as well that are pretty interesting to go over. So yeah, that's just quick updates. It's like there is a lot happening that is not really out in the open yet, but that will be at some point really soon.

Bree

Great, well, don't leave it secret too long. The other thing with the updates to the doubt is that including automation of the cycles, so we don't have to wait on somebody to start a cycle.

Jesse

Yes, it does include that as well.

Bree

That would be lovely.

Jesse

So, yeah, so what I want to basically develop is and I've been working on this update in details, in one of the proposals that I made in the last cycle, it was about having an ATP to make a better transaction for paying out the Dow transaction basically. So the reward has to go to a different account than himself basically and for a bigger amount as well. So the proposal was about creating this interface for aTPS which I've already been working on for a little bit, been doing some updates, trying to get some better UI for that as well. But I think where while these pieces are crystallizing and everything is coming into place I think we need to sort of restructure how we are doing cycles at the moment. Slightly restructured so that things get fit technically better into place. Because right now it's kind of hard to do certain things like the recycling of cycle funds. The recycling. Sorry. I have some good news. The recycling of cycle funds is something that it's confusing because there's 30% going to the first of all, we need to calculate what's left over and then 30% of that goes to the people and then 70% goes back to the treasury. And it's hard to get it into a smart contract in the current setting because right now, every cycle we need to make that calculation. The 30% 70% and the leftover has to sort of be manually processed. And then the recycle happens in those in those basically in those 30 70 gradation and leftover also to be calculated. But I was thinking what would work way better in automation parties if we make it so that every proposal becomes an ATP basically so there is no more logic and smart contract codes that's currently quite complex that sort of distributes funds. So it's just the Dow has a certain amount of sort of liquid funds which is not the treasury because those are locked away but the liquid funds is what we have at our disposal right now that we can spend on proposals and aTPS can spend from that liquid pool of funds. That would be like a way easier set up where we don't need to track spend budget and spend budget and the recycle strategy and what I was thinking was to add the recycles to the payouts of proposals. That was basically a proposal that I want to put out because it would fit really good in the ATP setup we have now and it would completely automate the cycle distribution part because then it would mean that and it would change a lot of things. That's why I do need to write it down and we need to talk about it for a bit but that would be one way to fully automate it is that instead of recycling leftovers we actually use whatever gets paid out. We can put a distributed small part from that to the people. So if I had a proposal fund that effects maybe we say that we always add like a 10% fee of that it goes to the people. So it would reverse the logic of the fee distribution, but it would make it technically way more easy to deal with and also to automate. But so yeah, the automation of cycles sort of fits in there as well. It's sort of a bigger story that adds a few, it simplifies technically how we pay out the cycle fees in a big way, but it has a lot of consequence also that we can automatically start new cycles without having any human in the middle to sort of initiate it.

Bree

That's good, that's what we want.

Jesse

It sounds way too complicated when I talk about it because it's something that I guess needs to be written down because it's actually really simple and I think it makes more sense. And when you see the UI that I'm working on, then it will, I think, fall into place and the UI that I'm making now won't be like, I'm not going to just release this. Of course, like, the UI updates of aTPS is something that's been on the planning and that everyone already knows about. But I think the consequences of making everything in ATP will, I think, fall into place pretty well once we've seen that first update.

Bree

Yeah. Having everything in ATP means we have to be more on guard. Not like even a sentiment that's asking a little bit. Not as simple as it was. If I get it understanding why it's consequence like it.

Jesse

Well, I think it will be actually maybe more secure than before because the way I see it, like aTPS orda will be able to detect if aTPS are like trustworthy ones or non trustworthy ones. So the basic ones will be automatically displayed as sort of verified. So I think it's actually going to be more secure because it gets more simple.

Bree

That's good. Okay, anything else to say right now?

David B

Indeed we have slowed down a little bit on the effect updates as well and we'll pick it back up and be more forthcoming with what's happening with the development on the back end of things.

Bree

Yeah, well, you know, this community likes to be informed, likes to know. Okay, that's awesome. I don't remember what I put on.

DJSTRIKANOVA

The agenda next in regards to these updates. I think they're definitely needed, but I was wondering how because the defy box proposal passed. I don't know, should we do the ATP or should I just make a proposal to do it myself manually?

David B

I feel like we can do the ATP that will kind of showcase the usefulness of the ATP, even though it might be technically a bit more difficult, but we can sit down so that we can create a transaction and make sure that all of the parameters are set correctly.

DJSTRIKANOVA

Would you be able to do that before the next cycle or should we be the cycle following the next cycle?

Jesse

No, that makes it a bit difficult. I think it should be an HP and it has to go out like this cycle, the next cycle. The proposal would be active, else we just get too much delay. Right. And I'm wondering it's already a bit, maybe taking a long time if we have to wait another two weeks, which unfortunately is not something we can adjust now. I think.

DJSTRIKANOVA

I just don't want to make them wait too long because I basically set things up.

Jesse

Yeah. So there's two ways, right. I wouldn't mind to just pay ahead for that amount because if we would need it really quick, but if a two weeks wait isn't too much, then I would say we do the ATP to the address of the well, that's what I told my bucks.

DJSTRIKANOVA

I told him we'll take one cycle for a sentiment and then another cycle for the ATP. So two cycles will be exactly what I said would happen if we can get okay, awesome. Then this coming cycle, ideally an ATP to show off the ATP. But if we can't get an ATP by the cycle, I'm thinking I may just ask for the specific Efx so I can transfer it myself. Or maybe you want to do it yourself if that would be better. I don't know. Just to make sure that the five box gets the Efx next cycle.

Jesse

Yeah. Okay, then we're good, I think, because then we'll definitely do the ATP because that will be ready for sure. So we can trial it. And of course we will pay double attention because it's an early feature to make these aTPS with the UI. So we will pay double attention that it's the right transaction. But luckily, it's not so hard to verify these things in blocks using the EOS multi six step. So it will be completely safe. Let's do the ATP so we can showcase it and we'll definitely make that in time.

DJSTRIKANOVA

Okay, sounds good. And then I have the chat now in the sidebar here so Rochelle can feel free to type. So the marketing stuff, that also is for the five box, right.

Jesse

You mean to do some marketing around $35 pool. Right. And the books?

DJSTRIKANOVA

Well, I mean, they want to just need to share some promotional materials. And is that the same thing Rochelle is talking with the marketing plan, or is that something different?

Jesse

So marketing around the $5 will definitely align on that. I'm pretty sure we want to do marketing there. Right. So, like, Gabby and Rochelle will be working on creating all the content necessary for doing a marketing alongside, especially if they're also doing a marketing initiative, then we will completely align and make sure we release enough content around it as well. That sort of opiates like. We will do that, of course.

DJSTRIKANOVA

Okay, good. Because that's the other thing I said I'll hand them over is basically promotional materials they wanted to have. Another thing I talked to them as well, is they're interested in kind of like what is called like, a dual AMA or effect network user base. Can ask questions about Defy box and then defy Box user base can ask questions about Effect Network. Is that something you'd be interested in?

Bree

Yeah, that would be good.

Jesse

Yeah, for sure. That sounds good. That would definitely be interesting. I think anytime marketing would be completely interesting. Right now. We can use marketing material in general, I think. So something like this, it would be really fun for us to get more involved with community, to get more eyes from the Earth community on the project. So anything like that I think is really important and will be a priority for us to engage with and promote. Definitely.

DJSTRIKANOVA

Okay, good. Then the last thing, I don't know if this is also being worked on with the marketing materials, but with Elsbs, I was able to get my grant translated into Chinese and Korean. So I don't know if you have, like I guess I don't know if the term be in house workers for it, but if you can give me the Raw files as well, I can get them translated into other languages as well. And I think that would help because I think with the five box, they have a very strong Chinese speaking community. So I think it would be great to have the Chinese translated content as well. So it'll be easier for us to explain what Effect Network is.

Bree

I know Richard language, too, but it wasn't Chinese.

DJSTRIKANOVA

Yeah, it's Nepal, which I think is Nepali's, what they speak to, right?

Bree

Yes.

DJSTRIKANOVA

Basically. I think it's bees. I can get them stuff translated, so as long as I can just with the graphics and stuff, I can just edit the text, then I can just ask them to do it.

Jesse

Yeah, sure. I don't have in my mind right now what the promotional materials are that they would do, but I'm assuming like a blog post, maybe like some banners or some infographics I haven't used before, I would totally be sort of supportive of using their Surface. Or is it just a community? I'm not sure.

DJSTRIKANOVA

Well, they are basically like affect socials, but they have like six X more participants, and they also have an international community. And so the guy in charge who shares the same name as you, Jesse, he also facilitates people. He knows people who can offer translation services. And so he connects to whatever language I need. And it can get kind of pricey, but it's like five cents per word. But I think they're pretty good. I think they are. So, yeah, that's what POS. In regards to promotional, I was thinking just like, because Gabby makes these visuals that are pretty good, it'll be nice if there can be like kind of condensed images that we can kind of swap the languages on. That kind of, in a nutshell, explain how Effect Network works, explain how Effect dial works, and I guess how you can participate in just like five images or something like that. I think for me that would be kind of an ideal because.

Jesse

Yeah, it makes sense. The translation part, I think won't be an issue, but yeah, we have some Chinese translators in the community that we can reach out to and they would love to translate some content, so I think that won't be a problem. Let's definitely make sure we have. In the languages that the five box users like to read, like Chinese I think is something that they really need is localized.

DJSTRIKANOVA

Especially because the five box has the speaking community actually, like in the AI sphere, I think because we're on Kucoin, there's man and DPC, which are also, I think, Chinese speaking focus projects. So it would be nice to also be able to have language support for them. And then on broader speaking in EOS, on Pamela, for example, the free languages they allow is English, China and Korean. We can't go overboard. There's so many languages, but Korean is like kind of like the other sphere that the Enf is trying to promote to. So if that's also possible, that would be great.

Jesse

Yeah, for sure. I'll make sure that we share pretty soon we can share a list of marketing materials for the promotion, like also some basics on a network. Make sure that's localized and then share it in discord. And then we can all yeah. Any tips and suggestions is good, but we have quite a bit of marketing materials I think we could use for this sort of reuse.

DJSTRIKANOVA

Yeah, that's exactly it.

Jesse

I'll make sure that Gabby, Me and Rochelle are on top, at least of the D $5 gross promotion, so everything is in order and prepared for it.

DJSTRIKANOVA

Yeah, that would be great. And then having like a repository of promotional materials will help me out as well, because I'm trying to just reach out to the communities on EOS, and that helps me having just everything to explain so I don't have to do it. It's already in a nice neat graphic that I can just post right. It saves me effort and having to repeat, like, making it. And then the ACP will be very useful because I think the five box can be just the first way. But outreach of other EOS platforms can happen. Like, for example, this is not something that's going to happen now, but I know Pomelo like, wants to expand the tokens which contribute to the matching poll, especially with the IBC. Now that Telos and Wax and UX, all these antelope chains, they're now being connected to EOS. And because there are public goods on Pamela that can be forked to work on any antelope chain, there's interest in having these other chains like contribute tokens for the match pool to expand the funding that people can get. And I feel like I know relatively we're a small project, but with the aTPS, we can also contribute a small amount to show that effect network is like an EOS project that supports EOS and stuff like that. So yeah, I think being able to send will help a lot in, I guess establishing deals with other partners kind of in a way without having them to have to go through the whole process of becoming a Dow member and requesting a proposal and stuff like that.

David B

I like that idea. Establishes as a legitimate entity within the EOS community.

Jesse

Yeah, I like it. That's great. That would be great. And doable nice stuff. I think that's indeed a great way to interact with other community projects and yeah, it's nice the positioning. Also we have this new social list page with all the endorsements. I think it's a really good direction as a dial, be very involved with all the other initiatives and support us that are helping us as well.

DJSTRIKANOVA

Yeah, and even with EOS EVM, like we talked on the chat, I think the main net beta launches in April. And so I think if we can jump on it because it will be great, because one reason like we have the bridge to buy that smart chain is because a lot of people prefer using a buying smart chain wallet because you don't have to create the EOS account. And so I think jumping on EOS EVM when it's coming out, I think would be a great way to kind of outreach. I don't know how much that would involve, hopefully, I'm thinking it's just you kind of repeat what you did with the binance, because I talked with the Ptokins crew and they said they are very enthusiastic about creating a bridge to EOS EVM. So I think in regards to the bridge part that will be available for efx.

David B

I hope so. Last time I did think it cost us some funds in order to be able to get petokens to build a bridge for us.

Jesse

No, we're pretty close with the pitokens with the P tokens guys. I am wondering though, if we're going to already be on we're already on EOS, right? So the EVM part on the EOS.

DJSTRIKANOVA

They said that other tokens would require third party bridges because the EOS EVM is only like I don't know if atomic is the right word, only EOS is like the gas for EOS EVM and only that will be swapped and they don't intend to make every token cross change. From what I understand, basically p tokens or other bridge type providers would need to do that.

Jesse

Right? Yeah, okay, that makes sense. So we would have to see. But yeah, I wonder how much, like how much ecosystem will become different than the EOS ecosystem? Because we can see because we have two parts, right? We have the binding smart sharing side and then the EOS side and we have like sort of with a relayer, we support doing transactions using metamask basically on the EOS site. So I was thinking one way we could maybe connect is to have, for example, accounts on the EVM side of EOS be usable using our same relayer system in our network so people can onboard on the EVM and eels and have some eels there as their gas, for example. But still that we would accept those transactions somehow or we can even move parts over to the EVM. So I think there's a lot of possibilities. Yeah, you're right. If it's to change, we have to.

DJSTRIKANOVA

Figure out what's the bridge yeah, with the relayer. That's what I'm hoping is like that we can just set something up with the P tokens people and alternatively I don't know if you looked into it, but it may be prohibitively expensive, but the team may consider just hosting a P tokens node as well because that's how they process the transactions. But anyway, I think yeah, with EOS EVM, if we can have real errors on there, we could have potentially find support in getting initiatives for tasks. I know that's related, for example, the hugging face stuff that David wants to do in his proposal potentially if we make it I don't know if you can, I guess discriminate the right word between different types of blockchains, but I wonder if you could have tasks that can only be done on EOS or EOS EVM. I don't know how much they would want or maybe they will be fine with all of them being compatible, but either way, I know for sure that their main goal is they want to bring eyes on EOS EVM. Right. And so maybe they will be interested like in big amount of tasks being done by EOS EVM users. Right, that could just be a qualification. Yeah, maybe. I don't know if it's programmatically possible.

Jesse

And we would have to release some smart contracts on the EVM, which wouldn't be terribly hard to do, I think. And being if we release them on Eocbm they would be compatible with other EVM chains which is also gives some options. But I think Eocbm yeah, it's very exciting. I'm definitely going to look a bit closer into it and if we can do tests on there then I think that would be really interesting. Yeah, we'll definitely try and see what's possible. And if it's not test then at least we can make people use there instead of Binance smart chain or alongside Binance smart chain to have the same effect account attached to their EVM account I think will be also very interesting and that's definitely doable. So being there on the launch is a really exciting and good possibility for us.

David B

Indeed. We'll have to keep an eye on it. When does the EVM launch officially for Maynet?

DJSTRIKANOVA

I forgot the exact date. I know, it's like I think the middle of April or maybe early mid.

Jesse

Sometime in April 14 April.

DJSTRIKANOVA

Yeah, sounds fair.

Bree

Right?

DJSTRIKANOVA

And they said they wanted to underline this is the main net beta because there are applications that are being built. Like for example, there's trust swap which is uni swap for us EVM because I think there's like a test net right now. So I think you can already work on it to an extent, but yeah, but being like the first I think would be great because it kind of aligns us because even though it's very easy for Metamask users who have Binance smart chain wallets or connected to use Effect Network, the Binance smart chain itself, it's not like they really care right now. Right though maybe on us just having difficulty promoting there. But Posm will be directly connected with all the people and so it would help if they can I think it will help mutually really? So I guess that's why I'm advocating it.

Jesse

Do you know DJ, what would be the main wallet being used for the EVM? Is it like Metamas compatible? The EOS EVM. Yeah.

DJSTRIKANOVA

I'm pretty confident it's made a mass compatible.

Jesse

But I haven't tried their testimony yet.

David B

I think it's just a couple of configurations we might need to add to the SDK in order to support a new EVM chain. But let's schedule and then a developer call for this so that we can talk about like technicalities of adopting a new chain later on because I do think this is a discussion that requires a bit more attention and there are a couple of more agenda items that we need to talk about before our hour is up.

Jesse

Definitely, yes. So we can put this on the agenda for def con. Let's do that.

Bree

Okay. What's the next item?

David B

The next item is the last proposal was not multisig approved. Why not? I understood that we were going to multisig all proposals, even sentiment ones.

Bree

Yeah, that was me.

Jesse

Was it not? Let me see, which proposal wasn't approved?

David B

Um, I understood that only ATP proposals would need to be have a multi.

Bree

SIG oh, need required. Yes. Where is that comment?

DJSTRIKANOVA

The the waste proposal wasn't 127.

Jesse

127 in cycle 56. All right. No, that should have been right. Okay. Yeah, it should have been great. Good to point out that should have been approved, like or executed at least. We need to get into rhythm of executing every cycle. So yeah, automation is really necessary here, but I'm setting up the automation part after done by this cycle. But even for the sentiment once I think yeah, great. I don't know, who knows that it wasn't but we should stay on top of it because every cycle we need to execute them.

DJSTRIKANOVA

This one in particular, I put 100 Efx. So does that mean the EFFX wouldn't be delivered?

Jesse

Oh, this even has Efx on it. I see, so then it means yeah.

DJSTRIKANOVA

Until we approve it because we haven't tested it with our real one. Right?

Jesse

Yeah. So this one you don't get any. Like those funds are still not paid out until we do it as the hiker.

Bree

Is there. A deadline.

DJSTRIKANOVA

Can you do it late?

Jesse

No, there's no deadline. You can do it. You can do it. It can happen any time, but there's no deadline. But unless if the High Guards reject it, then it can never be changed. But now it's sort of unaccepted, but not executed. And we added to this as an extra step. Normally, like where we want to go is where basically when a couple of days passes between voting ending and new cycle starting is when if the new cycle starts, then it should be automatically executed. But for now we need the High Guard to do that step as sort of an extra security with the ADT.

Bree

Well, you're welcome. Let's get that going.

Jesse

Yeah, thanks. Will do. I'll prepare it and share it in the guardian of this court.

Bree

Okay. And was that the last one or.

David B

Is there any other last but not least? There is a last one. There has been much going on with EOS and Palmerlo Grants. There is a fine line between EOS and I think, Enf needs and promotions. Can we have an update on how the team is building relationships with EOS about project ideas up for Pomelo grounds?

Bree

We kind of talked about that.

David B

Indeed.

Jesse

Yeah. I must say the DJ has done an excellent job, like getting effect on the Pomelo in the new Pomono season. We have, I think, two proposals or that he's also doing a proposal, but I'm pretty excited. I'm learning a lot being in Pomelo as well. And I think I really value and I think the core team is really valuing now. All of us sort of the EOS community and we were a little bit like right now our feelings and our feelings for the future of EOS is really positive. So I think being part of Pomonal is extremely important and being more in contact with the Enf and really endorsing and also as a project investing in the technology. So building on, for example, the ePM is things that we need to do in order to get value from an ecosystem which is so important in blockchain. And EOS is getting like a second life, which it's uncommon and it's really cool. So we want to be part of that as well. So I guess it's really important we see it and we're adjusting to be more actively and more publicly and more openly in that ecosystem, which yeah, it's something that doesn't happen overnight. But we are really keen on getting it done and absolutely also support and are motivated by the initiatives in the community now to contribute and cross promote.

David B

Indeed, part of the new marketing strategy on Twitter was to be more involved with the EOS community and to retweet more from the Enf, Big Beard, Samurai, Pomelo and other big EOS accounts so that we can also establish more of a presence with the rest of the EOS community.

Bree

Yeah, I noticed that.

DJSTRIKANOVA

To add on yeah, my project is still on there. All the nations are appreciated.

Bree

Even just one EOS.

DJSTRIKANOVA

Yeah, even just one EOS helps a lot because they have like a quadratic funding system. Of course, more is great too. Whatever you can. And I encourage you to just look through the grants, I think in my proposal collection of the ones I like, for example, the EOS power up. I think that's a good one to support because we always suggest using it. Right. If anyone needs resources, that's what we suggest using. So might as well help them out with the grant. Yeah. So I encourage everyone to make an account on there and to donate to grants. And mine too, if you like it. And yeah, I think David published his I think it's worth looking, reading it. I think it kind of needs a bit more revision, but I think it's more just need to make it more clear that it's like, going to be a repo that anyone can copy and build upon. Right.

Bree

Right. Now, can you post your you and David, can you both post your link direct to your project again? Bring them up to the forefront in the chats in both TG and in Discord?

DJSTRIKANOVA

Yeah, I can do that.

Bree

Yeah, just pop them out again and maybe next week again or in a few days again if they moved up.

DJSTRIKANOVA

Yeah, go ahead, David. Sorry.

David B

Yeah, I got some really great feedback from you, DJ, and I still need to incorporate them and I'll do this tomorrow and then I'll post it and share it with everybody on Discord NTG.

Bree

Yeah, I don't mean in a spamming sort of way. If the chats get busy, then those get lost.

DJSTRIKANOVA

Yeah, I'll be attending one of their pitch sessions tomorrow as well. My grant specifically does not use the Fact Network right now, but I think it creates a base for something that can be super useful because it's, like, an issue. It's an idea I've been sitting on for a year. Maybe because, I don't know if you remember, I did something similar with numbers protocol. But when I did numbers protocol, I was thinking this would be so much better. But this was before I learned of Hugging Face, so I kind of sat on the issue. But now with Hugging Face, it's like so easy. They have so their documentation is so great. All you need to do is like a really simple Python script and boom, you're already analyzing images, getting text for them, and it can happen to audio too. It's amazing. I think this grant is just going to be like kind of like I think there's going to be a big general trend of indexing blockchain data now that AI is making it so easy. But hopefully antelope chain side, this will help out and it will create these data sets because I think Nfts are like an incredible source of data that can be used for AI as well because they're all documented and findable and the links. I don't think there's going to be much link rot with Nfts because they have to work, otherwise they're like worthless. We could have, like, a giant data set of all the images on the blockchain what specific models say about their content, and then down the line. This is not part of the scope of the grant, but in the future, I think if we wanted to, we could add another add on where we have workers rate the model text and see how accurate is compared to what it actually is. And that would create an incredible data set for a researchers to evaluate how effective is their model, where are the flaws, where does it not work. And on the other side, the facing. I talked with them and they said they want to make a plug in type tool set so I can make my search or this index I can put like an elastic search and then people can search nfts, like on the collection manager or anyone who forks it and on any blockchain. So yeah, hopefully I can get enough funding for at least the phase one and build it out over the next month or two.

Bree

Well, good luck. I'm sure it'll be fine. You will get there.

David B

Yeah. Exciting. I can really see that. And here you're very passionate about this and I really do hope that you get enough funding and get it off the ground.

Bree

There's a lot of potential use for Apex Network with us, so go for it. I just wanted to add on top of this a little bit and give Alex some kudos here. If I had an NFT star to give him, I would do that. But I don't because he has picked up my splash that I have not been able to really do and in addition, is really involved in promoting EOS, which was never part of my wasn't really part of my thinking that we needed to do and has made me and maybe others aware that it's time we start connecting those. I think it's really been a big initiator in this. So yeah. Thank you so much. And other stuff. I think that's all I wrote on the agenda.

David B

Indeed. Those were the three main points and the actual one we added at the beginning.

Bree

Yes. And but there's still the just the proposal that I put up about the competition for Stickers and NFP. Oh, and by the way, Alan, if you missed it, has seconded my kudos statement for Alex. Now I have to plan a competition. There was a few abstains which I expected, but nobody voted no. Nobody said they would rather just have my ideas and go with it. Not a one that is so disappointing. However, I get it. So we need to start seeking out and developing a competition. I'm not some thoughts on it, but I will work to refine thoughts on that. And I think we should also be promoting that competition within the EOS community where we can I'm not sure that's a Mellow grant or anything, but just sharing some formal stuff on it, which means we need to create formal stuff for it and get it out on Twitter. In house, we're a pretty small group. I'm not sure how many graphic designers have a lot of time to spend on stickers and emojis, but I'll spend some deliberate, considered time on it this week. And Allen is at the ready for me whenever I'm ready for him. I'm sure. Gosh, nobody wanted my design. Just go with it. Okay. That's all I have to say on that matter.

David B

Indeed. I'm also excited to see what kind of circuits that produced and what kind of competition comes out of it.

Bree

Yeah, and I see Andre is on this call, too. And yes, I remember that he would like it not too cartoony and more business like. And so that might be part of our discussion, because what we really need to do is come up with the parameters of what type of design we're looking for. And that's really the hard part. Not the prize pool, but how do we want to structure these? What are our limits? What do we want to see come from?

David B

I'm thinking people should just let us with their creativity, and as long as they're not being insulting or trying to offend, I think most of it should be accepted. Right?

Bree

Yeah. It may come to that. I like the cartoony in some situations, but not in all. And for emojis, I like the cartoony and the flashy. Right. And the stickers. Maybe we need two batches of stickers. Maybe somebody does a real nice clean line type of stickers, and someone else comes up with a real bright, vibrant, more cartoony type, and we go with both of them. Maybe we have two categories of prices. I don't know.

David B

Yeah. Let's see what comes out of it.

DJSTRIKANOVA

Keep in contact with Gems people. I'm sure they could be interested in kind of helping facilitate a competition, because I know they have access to a lot of artistic people.

Bree

Yeah. And that's the other part of it. This is also coming from discussions with Martin, so he needs to still be included in those discussions. That is Martin, right? Yeah.

David B

Okay, great. Well, it's an hour. I need to go, but yeah. Everybody else is more than welcome to stay and have a little coffee chat. But thank you, everybody. It's been a great discussion today, and I look forward to the recording.

Bree

Thanks, David.

DJSTRIKANOVA

Bye, David.

Jesse

Thanks, David. I'm also going to have to catch up on this part.

Bree

Yeah, thanks.

DJSTRIKANOVA

One thing. So the socials, is that live yet? The page on the dow.

David B

I see it now.

DJSTRIKANOVA

Okay. It is, yeah.

David B

I'm looking at it right now.

DJSTRIKANOVA

Okay. Because I wanted to share a picture of it in the Fireside chat later this afternoon.

Jesse

Nice.

DJSTRIKANOVA

Yeah. I'm telling that you're enthusiastic about adding effect network functionality to EOS EVM, so I'll share.

Jesse

That awesome. Yes, please do.

DJSTRIKANOVA

All right, I think that covers it.

Bree

Have Lawrence put this meeting next week in his calendar.

Jesse

Yeah, he did say he couldn't make it something. We'll make sure he's here next time.

DJSTRIKANOVA

He did pledge to make it more often, so keep him to it.

Bree

Yeah, we want to hear from him. Want to see him. Busy guy.

David B

Have a good one.

DJSTRIKANOVA

Bye.

Bree

Okay, bye. Thanks.

Jesse

Bye, guys.
