---
description: >-
  *Assembly AI generated transcripts may not be 100% accurate, listen to video
  for original audio.
---

# June 14th 2023 DAO Call

{% embed url="https://www.youtube.com/watch?v=vnQk3xaccZw" %}

## Short Summary by DJSTRIKANOVA

* AI Fund almost ready, will be used to fund tasks for building an OCR LAION dataset.
* Test tasks have been published for bounding box OCR tasks, and a plan is being developed to potentially scale with big LAION datasets that need processing.
* Discussion over adding Fees to workers using BSC accounts. On EOS workers have to pay the RAM fees, while BSC workers have it subsidized through the relayers. We may want to have an extra fee that incentivizes migration to EOS over time, and also not subsidize blockchains outside of EOS.
* pNetwork swap fee Discussion. Matteo from pNetwork dropped by to discuss the new minimum fee and potential solutions
* Jesse suggested a bridge catering to low amount swaps. This bridge will be more centralized but it will allow EFX holders swapping to avoid the $10 minimum fee pNetwork bridges now require. This Foundation sponsored bridge could charge a fee of 2% per swap. This would be cheaper for small transactions compared to $10, but also fund the maintenance of this bridge.
* DAO NFT Profile Picture in progress to be implemented
* DJSTRIKANOVA's NFT Indexer Grant is live, all donations appreciated.&#x20;

{% embed url="https://pomelo.io/grants/nftindexer" %}

## Assembly AI Generated Transcript

{% embed url="https://www.assemblyai.com/playground/transcript/61vd9uaqrt-663d-4c32-9598-2c8ccc2a6c65" %}

#### DJSTRIKANOVA

Let's go.

#### David Britt

Okay, great. Yeah. Today is the 14 June 2023. We have one item on the agenda that is to discuss ideas to reduce the impact on the pNetwork protocol fee. I do think it might be useful to wait for Mateo from Network to join us as well. So I propose that in the meanwhile, we take a look at the proposals. And we currently have one active proposal, and we also have the Effect Dow AI fund that was created by Jesse in the previous cycle. Shall we get started with that one? The effect. Dow AI fund.

#### DJSTRIKANOVA

Yeah, let's go for it.

#### David Brit

So this proposal will establish a fund with Gold to incentivize creation of AI data sets on Effect Network. It passed unanimously, so if everything went well, I think we should still execute the transaction in order to actually withdraw the funds into the specific account. But it is created, so I do think it's good to go in a little bit.

#### Jesse Eisses

Yeah. This proposal is now like this voting just ended, right? So it should be like a definitely passed that all the votes are yes. So that's good. And we actually need this one right now, or at least need it. We can put it to use right now because we're in talks with someone that needs data annotations from lion. And I'm still checking to exactly see the scope and how much epics it would be. But I think our intention is to our intention with this fund is to at least get those annotations started and help the funding of those annotations so we can put it to use. Let's see if there's any specific parts. Yeah, there's no one that's voted. No, I think it was quite clear what these funds are necessary for. So as soon as they come in, we will transfer the funds to the multisick account that's managed by four people that are here. And yeah, if there's any questions, feel free to ask. But I think it will be nice to see these funds being used right now for the Use case I just mentioned.

#### DJSTRIKANOVA

Yeah, I saw some label box tasks. Are those related?

#### Jesse Eisses

Yeah, I created the campaign, so actually I made some scripts and made a campaign template for Label books, so we can integrate it quite nicely now with Effect Network. So actually, Rochelle is currently reviewing that template and hopefully if she thinks it looks good and see adjust the instructions, we can launch those tasks on the platform and see, of course, in collaboration with lion, we can see what more is required. But I think the workflow is really nice because with Labelbox, it's quite an advanced UI for doing these annotations. I must say it's one of the nicer UIs we've had so far on the platform for doing data annotations, because you can nicely see all the annotations that have been made before by who? And we're actually pre filling the annotations by AI. So we have data, have this bot already that's quite capable of doing OCR solocation and transcription of characters in a picture, and those are prefilled before the worker starts on them. So, yeah, I think the flow is a nice one. Hopefully it will also improve the results and the workflow on the platform. I can share the link to that campaign. It's just a demo campaign I created myself, so it's not listed on the front page, but I can share the link with you guys. So you can take a look if you're interested.

#### DJSTRIKANOVA

Yeah, go for it. And I guess in the conversation you also had questions about a validation. What do you think would be a good idea for that?

#### Jesse Eisses

You mean Chris from lion? He had some questions right, on the validation of results?

#### DJSTRIKANOVA

Yeah.

#### Jesse Eisses

I think Rochelle explained quite well how we would go about it. To have more of the onboarding of really proper onboarding. So we get some group of annotators on board that really know how it works and how to achieve hard results is really important. I think I didn't really grasp too deeply what lion was aiming at. I think it was more of an open discussion because statistical comparison of these types of data I think is quite hard to accomplish. Hard as in there are so many edge cases and the data science around it is like, I think, a little bit hairy because you're working with location of boxes, ambiguity and vague looking text and stuff. So I think as soon as you try to do statistical analysis, it's going to be harder. So for now, our approach is basically to make sure we have a rock solid group of people that know how to do this test properly that we can trust, and that will basically be the ground truth. And then they basically have to validate most of the work that's being done. But if Rochelle has any addition, feel free to jump in. But I think that's sort of the approach. And we'll definitely structure this out properly with lion so we can get to something that works for them. But I think that's most cost and time effective way to deal with it.

#### Rochelle Trevarrow

Yeah. After that conversation with Chris, I took a deep dive and made a couple of big different plans that would work depending on which way we wanted to handle the data coming in. And a lot of it is work for curation intensive, so I was able to get a lot of information from him as far as edge examples if the text looks this way or cut off, or blurry or box groupings, or how they even wanted the text displayed. So that was very helpful in the planning because a lot of what makes successful results when you're dealing with campaign is how you set it up and how you educate the workers in what the goal result is you're looking for. So it is very worker supportive, intensive, and I think we have a good plan. So we're just trying to figure out the fine details and get something going here. But I think we're set up really good for a good experiment.

#### DJSTRIKANOVA

Sounds good. I'm glad there's progress on that. Looking forward to have used the AI fund on helping build that data set.

#### Jesse Eisses

Yeah, me too. I'm hoping the technical things are not set up. So there's a little bit of polish to do and some discussions to be had. But if they're happy with what comes out of it, I'm pretty sure we can do that entire data set that they're working on. And that would give a nice influx of tasks and workers to be active. So I'm also looking forward to.

#### David Brit

Okay, great. Hey, Mateo, thanks for dropping by. We'll be discussing one more proposal and then we'll continue on to the agenda item about discussing brainstorming ideas for the pNetwork fee that was introduced. So the next proposal was the BSc transaction fee adjustment. This was for the relayer. We keep bumping into the issue of having the relayer needing to be topped up. And I wanted to introduce them this proposal to raise the fee a little bit in order to collect that into a pool that can be used in order to fund the transaction fees for the relayer. That the relayer account can be topped up every cycle because every once in a while this is a bottleneck and it does seem like the kind of thing that should be sponsored by the Dow and that a small percentage of the fee necessary in order to cover these funds would then come from the tasks themselves. And with the hope that if people really want to be able to earn more per task, they would be then incentivized to create an EOS account and pay for the transaction costs themselves instead of us paying it for them.

#### DJSTRIKANOVA

Yeah, I support the idea because I did notice that basically some workers complain sometimes they have to top up their Ram if they do too many tasks, while the people using Binance smart chain don't have to do that. So in essence, we're kind of subsidizing Binance smart chain when we pay for the relay layer cost. So increasing the fee so it encourages them to move over to EOS I think is a good idea.

#### Jesse Eisses

Yeah, I like the spirit. I hadn't seen it before, I don't know if it was posted recently, but it's quite interesting. I was thinking there's a few comments, maybe a few comments I have first, to be clear, so no one is performing tasks on the BSE network, right? All tasks are performed on the EOS network. Some people are just using a BSc wallet to confirm transactions, but that still happens in the US. So the fees would be on the EOS side. I think that's also what the proposal means, but it's just phrased the wrong way in the beginning and then indeed, good point. This proposal kind of assumes that we will have a Dow enabled relayer, I think because the current relayer is maintained basically by the team and funded by the team as well, which is fine, I think it works well enough. But I don't know if there's an undercapacity of relaying power right now. I think it's more just like an infrastructure problem where the maintenance dealing with spikes in the EOS network. Sometimes the resource allocations can shift a little bit but also just maintaining. We rely heavily on the auto power pool from EOS power which is an amazing tool and we're happy to use it. But there is like the infrastructure layer so there's this tool watching our accounts. There is shifts in EOS how much band that you can get from basically the power up that you receive. So there is like this fine line and then that infrastructure sometimes fails and we sometimes run out of the funds because we fund that pool, the power up pool with a certain amount of the effects with EOS stories. So then if that runs out then just it stops. Right, but I think all with all this, this is just a kind of a fragile system because it's easy for a component to fail in which case people cannot do transactions or work or you get this wire from the relayer being low. That's just something spinning in my mind right now. Like we need to fix that infrastructure deal in a way that it's more reliable. I think this proposal sort of assumes we're going to is also intending to have the Dow host another relayer. So we would have two relayer options, which I think is a good thing as well. But do you think that's what you meant as well, David, that the Dow should host its own relayer?

#### David Brit

Not necessarily. What I had in mind was more that funds would be collected and then the 5% extra from the funds would then be swapped over and then those funds would be then sent to the relayer EOS account to the power up tool so that the power up tool is always topped up and is able to continue providing the power up for that specific account. But I do like the idea of having the Tao also being in control of relayer. But.

#### Jesse Eisses

What would be a cool idea is to have because we can make power pools and power pools are I think semi decentralized. That power pool is always completely registered on Chain, on EOS. So if you look on the EOS power up and you create like a pool, you will see that even the accounts you're watching and that you want to replenish, they're actually registered on chain. So it would definitely be possible to have the Dow create and maintain a power up pool that sort of we endorse. So it means that we could use ATPs to configure that pool. We could add accounts to be watched and change the bandwidth per account. So we could, for example, add the base relayer as an account and make sort of an extra certainty that it gets powered up properly. I think that would definitely be nice to do, which is maybe what this proposal sort of aims at. And then we didn't need increasing fees. We could do that or we could simply use like I'm just starting to debate here because I think increasing fees would be nice is a possible solution. But we could also use fees that are currently just coming into the Dow to finance the power pool. The Dow power pool. There's a caveat that we have to swap EFX to EOS to make it work.

#### David Brit

Indeed, that would be one of the downsides for doing it this way, but hopefully it would also automate it enough and the swapping is also insignificant amount that it won't actually create a lot of down pressure.

#### DJSTRIKANOVA

Yeah, I support a fee just on the principle that I think because EOS is kind of the base chain and it's the least complex to deal with EOS, the fee should be lower. And then if you want to use any chain that requires a relayer, there should be fees involved that to incorporate the cost of maintaining a relayer. And so even if the foundation runs one right now, by increasing the fee, it makes it clear that there's a cost into maintaining it that needs to be financed with the fee. For example, because I think we do want to in a way, kind of set up the incentives that people migrate. If people want to maximize how much their work pays out, it would be ideal if it would eventually like the incentives will align that they migrate to EOS because I think that way they become less dependent on the relayer. And you called it like pretty complicated network of just things interacting with each other because then we have less stress on it as well. Right. In a way I see it. I want the relayer to be just be like the entry level for people who are interested in doing tasks, but they all migrate to OS over time. So that way the relayer never gets as strained as it could be if it was the superior experience. Because if it's the superior experience, it will just keep growing and growing growing and the maintenance can probably get more expensive over time.

#### David Brit

Exactly.

#### Jesse Eisses

Yeah, that makes sense. That's a good comment. I'm thinking more like if I think on the technical level right now, fees are being paid when tasks are being posted, not when tasks are being completed. So I'm just thinking like, if we want to charge a different fee for BSc users compared to EOS users, I'm not sure how to accomplish this, like in the contract level. Right. I think the fee being paid is like in this current architecture, universal across all workers because when it gets posted, the fee gets paid basically. So we have to think. I don't think we can easily change the fee between a binance smart chain address and an EOS user, but I'll give it some thought. I think it's a good idea. I think that's what DJ was talking about and I think it makes a lot of sense if we would charge more. Like if the BSE user would be charged a bit more because they have the convenience of not needing to worry about resources and also we're subsidizing them so it makes sense if they would pay a bit more. I'm not sure if that's in the proposals, but I think that would be really nice.

#### David Brit

Yeah, indeed. This might need some editing in order to make it a bit more clear what the intention is of this proposal and how we would implement it.

#### DJSTRIKANOVA

Yeah, we may want to because I think as Jesse stated, the 10% fee applies to when you create a task as a requester and the requester cannot control who completes the tasks.

#### David Brit

Good point.

#### DJSTRIKANOVA

Raising it 10% to 15% doesn't make sense in this context. Basically it seems like we need a fee we can charge based on the completion of a task or something like something equivalent to that. From what I understand, you need to figure if that is possible first, right?

#### Jesse Eisses

Yeah, I think it is. Maybe I can weigh in a little bit on the technical implementation but I think we could add it at the moment of payout. Like if a worker does a payout, that's basically when the funds go out of escrow and I think it means we add another fee. Right, it's like the payout fee but that's not so hard to add in there. Actually we used to have fees being paid on payout and we swapped it to fees being paid on task creation because it made more sense from a user perspective. But having an extra fee for BSE on payout is, I think, a nice addition. Like I think it would fit nicely. So it might be doable if we give it a little bit of thought then we can probably work it out.

#### DJSTRIKANOVA

Yeah, that sounds as long as we make sure to make it clear to the workers that the fee is for using the MetaMask, basically.

#### David Brit

Yeah, I think potentially we can add it to the SDK as well. So when people are using the foundations products then this fee will be applied. But if they're using their own tools they could potentially mitigate this fee. But indeed we should talk about the implementation and where we should put it.

#### Rochelle Trevarrow

I like that direction, Jesse.

#### David Brit

I'll quickly write this out and we can start talking about the next agenda item or the first agenda item about ideas to reduce the impact on the pNetwork protocol fee. I'll quickly introduce the subject for the ones that aren't completely aware yet. So the P Network recently introduced a new fee mechanism in order to collect fees for swapping in between chains. We've been using P Network already for, I think a year now, almost two years for swapping EFX from finance to EOS and vice versa. It used to be zero point 25% per swap, but recently Dow proposal passed with the PNE Network Foundation to make the fees higher. So for smaller transactions, they've introduced a $10 worth of EFX limit in order to make their own nodes more sustainable financially. And one idea that was introduced was to either eliminate the Bridging or just for smaller fees, especially on the force front end. We'll keep using pNetwork as it is for bridging larger funds, especially when it comes to the farm where I think a lot of people are using it at the moment. Or we can potentially aggregate EFX for users and the Dow will pay then the Bridging costs for the user each cycle. So in that way we'll only pay the $10 minimum or whatever it might be each cycle for the users in order to keep it cheap for the users. With the caveat, of course, that they'll only be able to retrieve their funds two weeks in.

#### DJSTRIKANOVA

So let me make a question though. So from what I understand the fee impacts when for example, a worker has $100 worth of tax and if they wanted to withdraw it to their binance smart chain wallet, that would hit them with the $10 fee, right?

#### David Brit

Yes.

#### DJSTRIKANOVA

And then how does it impact requesters? Because I know you still have to transfer EFX from Binance smart chain.

#### David Brit

I.

#### DJSTRIKANOVA

Forgot what it's called. But you transfer to EOS, right?

#### David Brit

Yes.

#### DJSTRIKANOVA

To top off your virtual wallet. So if, for example, someone wanted to buy some social tasks on buying smart chain, like they had say, a budget of say, 1000 EFX, which is probably not a lot, most of it would be in the fee because they would have to transfer it to the virtual wallet, right?

#### Jesse Eisses

Yes, exactly.

#### DJSTRIKANOVA

That's like, I think the biggest issue, workers, they can probably adapt to using their anchor wallets. Right, but we don't want to scare away requesters. Right, because anyone who wants to just experiment a little bit and not have a giant set of tasks, they're going to have to deal with this fee because they have to transfer to the virtual wallet which is on EOS side.

#### David Brit

Yes, exactly. Yeah, that's a good point as well about depositing from BSE and how that would be much more difficult. Up until now, I've only been thinking about how this would impact the workers and I haven't really thought about how this would impact requesters and how easy it would be for them to add patches to the platform.

#### Matteo From pNetwork

Hi guys. I'm Matteo from Pinotwork. Yeah. For this problem, I think what the idea that I proposed a few days ago, the Effect team, could be a solution. I proposed that the Effectile could subsidize the fee each time. In this case, not the workers. But in this case, the work provider needs to launch the task from ESG to EOS and the Effect dow would cover these protocol fees for them. I assume that there are not many transactions every day, so I think that the cost is just covered with the EFX of the treasury of the Dow, basically. I don't know if this is feasible, but maybe this works better from this side compared to the worker side. As we discussed last time. I didn't know about this other approach.

#### David Brit

I do think that would work well for the worker side, but for the requester side, I do feel like we want to be more accommodating to them.

#### Matteo From pNetwork

But the requester can I don't know exactly how it works, but I suppose that the requester can publish request basically and provide the money on a wallet, right? More complicated than that.

#### David Brit

Usually right now it's built that they make the swap right away from their BSE account to their EOS account. But potentially we can think about if they transfer it to an account, a BSE account that Effect owns. That way we can credit it hasn't.

#### Matteo From pNetwork

To be like that. It's enough if there is an interface built by you.

#### David Brit

Very easy.

#### Matteo From pNetwork

Very simple and easy. And using our library, the Pitosing JS library that basically enable each bridge. But in this case you will only need the EFX bridge. And from this custom interface you can subsidize the free on behalf of the sorry, what's the name again?

#### David Brit

The requester.

#### Matteo From pNetwork

The requester, yes, on behalf of the requester. So at the end, the Dow, the Effect Dow pay those $10 fee, but the requester is incentivized first to use your interface instead of our interface. And the requester don't have to pay any fees at all because it's subsidized by the Dow and you don't have to collect anything from him. He's still able to do the deposit by himself. But on your front end and on your front end, there is this specific proxy that basically subsidize the fee on his VR.

#### David Brit

Yeah, I'm thinking a little bit.

#### Jesse Eisses

Yeah.

#### DJSTRIKANOVA

I don't know if that necessarily can be the way because if if there's a spike in activity, we're kind of on the hook for a bunch of fees. I mean, $10 is a lot, even like 100 people, that's $1,000. And the Dow isn't like we're pretty small. I don't think we could really afford a big paying for fees subsidizing like that. I think for now it's just trying to maximize fee avoidance is the best thing we can do.

#### Jesse Eisses

Yeah, I agree. So Mateo, thanks for coming by. Good to have you here. And your proposed solution, I think it makes a bit more sense when we look at the requester side because workers, I think, would tend to have smaller like they would swap smaller amounts. These would be a little bit bigger amounts. But still, as DJ said, I think when it's a $10 fee and if we would have request like, we would have to still have a pretty high minimum for requesters to post death because they would need to have at least if they do 1000 tasks of a dollar and it would be 1000 swaps, it would be $10,000. That would have to be covered in a spike of activity, which would be a bit much in that case. And then it could be more and more. Right, so I think, yeah, we would have to think it's not a use case that's happening often, but it is kind of what we're it is exactly how we want to use the bridge. Basically, we want to be able to have people buy the effects on binance smart chain and then use it to post tests quickly. And even with quite high amounts, like the $10 fee would just be, I think, too much to copy it in that way. So one other solution I was thinking about was basically to either pull the transactions or just to sort of provide liquidity on both sides in more of a centralized way, but to facilitate small swaps where basically if people would transfer a small amount to our wallet on Binance smart chain, then plus a little fee. Then we would sort of transfer that to them on EOS because yeah, we would transfer to them on EOS because then there would be very little fee involved on the blockchain level. It would just mean we would have to write some software that monitors it both ways for small transactions and once every few weeks or months we would have to rebalance the tokens among the two wallets, basically using the P tokens bridge. But I think that might be a solution that would work more scalable for small amounts.

#### DJSTRIKANOVA

Yeah, I think that's ultimately what they wanted because from the Dow proposal it seems like basically the computation cost of dealing with very small transactions isn't really worth the gain. And so what you're going to do is basically create the bridge for the small transactions, right? Jesse?

#### Jesse Eisses

Yeah, exactly. We could make like a bridge, it could either be like an atomic swap based bridge or in a decentralized way, but I think that would be just a bit too much effort in the beginning. But we could easily make our own bridge that basically monitors the things it's very much not decentral. And P tokens would be used for basically if we provide liquidity on both sides. So we have a binance marching wallet where people deposit binance marching EFX and then we have an EOS wallet where we basically transfer that EFX on the EOS side to wherever it needs to go. And you would trust the entity that does that. Right? The entity that controls the bridge has access to both the wallets, but you would need to have enough EFX. Basically, at some point, the EOS EFX will be up, will be gone, and the binary smart chain EFX wallet will be very full. And at that moment, we would do like a bridge transaction using P tokens for a large amount. And then this can repeat forever.

#### DJSTRIKANOVA

And I guess if we can charge like a slightly higher fee because from what I understand it's still like 25%, right? 25% with $10 minimum. Is that the case?

#### David Brit

It's $10 up until the breaking point which can differ between pegging in to EOS or pegging into pegging out of EOS which is then 4000 or $10,000 respectively.

#### Matteo From pNetwork

Yes, correct. Basically it's a minimum fee. So if the amount is lower than the breakeven basically then there is this transaction. Otherwise the percentage is the percentage as always.

#### DJSTRIKANOVA

Then this other secondary bridge, we can set it so it's like 2% or something. So that way the more EFX you want to transfer, the more you're incentivized to just use the regular P tokens bridge. But if you have low amounts it's more beneficial to use the small token like the low amount bridge and that way we won't have to deal with if it's a low amount, we don't have to constantly deal with balancing it. Right, but we still provide the service so the small token holders don't get hit with a big fee. Like 2% isn't that much. If you're getting paid $100 in EFX, it's better to pay a 2% fee $2 than the $10.

#### Matteo From pNetwork

I mean, the 2% is unrelated with pinetric.

#### DJSTRIKANOVA

Yeah, that's what I'm suggesting for the bridge Jesse is thinking of.

#### David Brit

Yeah, I like that idea as well. I don't think it necessarily needs to come from the swapping. I think we can also consider other mechanisms of where we can get that fee from in order to cover the costs or potentially also just subsidize it from the Tao itself for every time that we do larger swaps.

#### DJSTRIKANOVA

I don't know if the Dow necessarily wants to swap it because it's like going back to our previous conversation, we don't necessarily want to swap or we don't want to make it equal using the finance smart chain and the US chain. We want to incentivize people to migrate over time and so a small fee I think is good for that.

#### David Brit

Yeah, good point, good point.

#### DJSTRIKANOVA

As long as the fee is reasonable, right? Like a one or two percentage points, like if they want to do tasks, I don't think one or 2% is going to discourage them or rather if they want to request some likes on their Twitter tweets or get some labeling done. I don't think one or 2% on top of the 10% we already have is going to be too much of a hassle.

#### David Brit

Agreed.

#### DJSTRIKANOVA

And they can always like if they are super interested, they can always just set things up on EOS side.

#### Jesse Eisses

Yeah, exactly. And this way I think in the end the goal is. For small swaps, which is basically what we're looking for on our product. We're looking for small swaps either for workers to go to Binance smart chain, which is maybe less important, but like DJ said, actually for requesters to go to EOS to post test, it's quite important. We want to support that. We have to offer some sort of solution where we facilitate the bridging and then we would still use pNetwork as the underlying bridge, but we would have to sort of pull these swaps to a point where it's close to break even point. So, for example, if the break even point is, I think $20,000 or $10,000 a swap, we would want to do pools of swaps that are close to that amount every once in a while, instead of and then people can we can facilitate in a sort of managed way that people can do smaller swaps of like $10, $20, $50. And then the fee will be like to pay 2% fee even on $50 I think is fine. People won't mind. But the $10 just wouldn't fit in that scenario because of the small amount.

#### David Brit

Yeah, I think that's a good idea. I think that's a good way of approaching it and dealing with the smaller swaps and keeping it simple and easy to use for users. Do any of you think it'll affect how much people will swap as well going into the future with the farm? Is that going to be an issue?

#### Jesse Eisses

I think at the moment there's very little being swapped anyway, so it's more about the future. We're going to promote people posting a lot of tasks. That's what we will do on the short term and that's the important thing. And people need to be able to conveniently come from binding smart chain when posting tasks. That's sort of what we've been working towards that will create an influx of tasks and stimulate the adoption. Right, so we need to make sure it's possible. I don't think at the moment it will hurt anything on the short term too much. There's only very few people swapping small amounts at the moment, I would say.

#### DJSTRIKANOVA

Okay, yeah, most of the swaps I think is just the Arbitrage trading between the USDT EFX pair and then the B and B E FX pair on Pancake swap. So usually Kucoin goes in one direction and then if you look at the chain data, the swappers are trying to equalize the prices everywhere. So I think that is the vast majority of action and then yeah, of the actual uses of effect network, it's much minor, but we're having this discussion because we don't want anything to discourage it if it is to happen. Right, and so we don't want any fee getting in the way of that.

#### David Brit

Indeed.

#### Jesse Eisses

What do you think, Mateo? Is it a recommended way from your perspective? Do you see other projects using something similar where they provide liquidity for bridge and small transactions? Or is this more of a unique case that we're dealing with when it comes to swapping? Like, I don't know, micro swaps basically between using the P tokens bridge?

#### Matteo From pNetwork

Well, no, there are specifically just one other project that we discussed together like how to reduce the impact of the protocol fee. They agree to basically condensate what you suggest basically to condensate in less number of transactions with your amount and managed by the team, most of them because in this way the impact lower. So yeah, they are working on doing that basically liquid people managed by them where they distribute for the small customers they have and they provide this service basically and they pay the fee by themselves for that, for their bigger customers instead. They don't see any problem because usually they trade larger amounts or it's just for profit for the customer profit. So they don't care that much about it. They found this solution basically which is very similar to the one suggested we suggested to the other ones.

#### Jesse Eisses

Okay, cool.

#### Matteo From pNetwork

I remain a disposal to discuss further option. More ideas from Pinator side. We really want to help you guys and find the best way to reduce the impact for your user but still to use the bridge. We are working well with you and I think we will be able to find a trade off between the sustainability of notes and sustainability of your business. I think there are ways to reduce the impact of this minimum fee with subsidies from the Dows or with the liquidity pool that you aggregate effects token on binance marching and then you distribute them. There are several ways, we just need to find the best solution. What I want to stress out again is that it's very easy to integrate the bridge on your interface and once you do so you have a lot of flexibility on your side to change some dynamics. We can do it on our interface, but if you do so on yours, which is again very simple and we can help you to integrate that, you have much more flexibility. So that's why I was suggesting to integrate the EFX bridge on your interface. It's very simple really and then you have plenty of options.

#### Jesse Eisses

Nice. Yes, we have our own interface already that we use for Bridging. So we have our own bridge effect network where we do most of the Bridging. I'm not sure if we use what the options are that we're using but because you always pay the fee right so there's no option. But you mean there's options that we subsidize part of the fee from subsidized for the user.

#### Matteo From pNetwork

Correct? Yes, correct. Or set some limits, the minimum of what? Set some limits on the amount breached or putting, I don't know, sort of integrated liquidity pool. I mean there are a lot of options once you have that integration. But just one question, you already have integrated. Do you use the latest version of or not?

#### David Brit

Yes, we do. We're using the version two of the bridge, if I'm not mistaken.

#### Matteo From pNetwork

Yes, correct. Okay.

#### David Brit

Am I correct in thinking that there is a version three coming?

#### Matteo From pNetwork

Correct, there is a V three coming, but it will come by the end of the year, realistically. So that's still a long pass from now. V Three is the new architecture of pNetwork and it will be basically 100% decentralized. It will be very integrated with the Pinator Dow network, Dow V two that we recently released and that has a specific and improved economics for PNP. So yeah, there are a lot of that is changing within pNetwork infrastructure and the coming already in the past weeks, but also in the coming months from feature from the user side piano v Three will bring less compared to the migration from V one to V two. But the main thing will be the decentralization aspect. It will be crucial and central in the new infrastructure.

#### David Brit

Okay, yeah, that's exciting. I'll keep an eye out for if anything does get deprecated and we'll need to update something under our end.

#### Matteo From pNetwork

Sure. Yes. Now I need to leave. I don't know if you guys, but I need to leave anyway. David or Jesse, if you want to ask me anything, just use the usual telegram group. I'll be happy to answer soon.

#### David Brit

Yeah, we'll do. Thank you very much, Matthew. Thank you for dropping by.

#### Jesse Eisses

Yeah, good to have you here. We'll keep you in the loop on what we decide on and how we continue, but thanks for the support and we'll definitely keep in touch and let you know.

#### Matteo From pNetwork

Sure. The entire prenatal team want to support, so I'm covered the business part, but if you need anything from the technical part, just let me know and I will invite whatever is needed to support you guys. Thank you. Thank you for the invitation.

#### DJSTRIKANOVA

Thank you.

#### David Brit

You too. Have a good one.

#### Jesse Eisses

You too.

#### Matteo From pNetwork

Bye bye.

#### Jesse Eisses

I wonder if someone ever did, like, atomic swaps between EOS and Ethereum, because that would be the nicest solution.

#### DJSTRIKANOVA

But if you create that solution, you should ask for a grant from the EOS Foundation because in the talks there's been complaints that they're doing the swaps on the EVM. Right. But they don't do it for tokens. There's no tokens swap between EOS and we can't send EFX to EOS EVM, for example. And so it makes sense because there's pretty much very few projects on EOS these days.

#### Jesse Eisses

Of course, I keep forgetting the EVM is also there. So that's another EVM that would be really interesting to have.

#### DJSTRIKANOVA

Yeah, I mean, if you're already making bridges now, you might as well make the Ethereum the EFX to US EVM bridge.

#### Jesse Eisses

Yeah, it's interesting. I think for an atomic swap, you need to have the remote asset already existing. So right now we already have a Binance smart chain token. We have an EOS token they're basically being bridged already. But for an atomic swap, it gives you this way to trustlessly exchange, like one EFX and banana swatching for an EFX and EOS. So when you create a bridge, I think often the remote token doesn't exist yet and that's sort of a different problem. But I think with an atomic swap, it can solve like a lot. Yeah, it can solve so much.

#### DJSTRIKANOVA

If you could, like, make that a grant for Pomelo. There's not that many grants actually, right now for EOS EPM.

#### Jesse Eisses

Yeah, nice. I'll look into this. I'm just reading right now some ways, but if we can do the atomic swap, that would be amazing, especially if it can be used on the EOCM, then we can actually get some more traction in the EOC VM side, which I think is really interesting as well to pursue.

#### DJSTRIKANOVA

Yeah. And I think it would get a lot of public interest because there has been interest in swapping tokens between Ethereum or EOS EVM and EOS. So since everything you publish is open source anyway, it would satisfy that requirement.

#### Jesse Eisses

Yeah. I'm going to look into this and see what we can do. But we need to find out a way for the bridge anyway, so I think it would be a good idea to combine it with the eosvm.

#### DJSTRIKANOVA

Yeah. Unfortunately, it seems the foundation is more focused on GameFi, but I do think that if we try hard enough, we can get some support. I know. Rochelle, you said that you submitted the information so they can do the article, the blog projects on EOS.

#### Rochelle Trevarrow

Oh, yes, it's been uploaded to them. We filled out the form.

#### DJSTRIKANOVA

Yeah. Because I definitely still see there is potential in collaboration there, at least, especially if we can get the lay on. If we can deliver a great project, something we could offer EOS is basically we're one of the few. As AI gets bigger, we'll be one of the blockchains that is helping with that trend. Right, so we're helping the cause of AI research by developing open source stuff. So I think it's a good thing to offer in the coming years.

#### David Brit

Yeah. I also noticed in the marketing material of different blockchains how each one is trying to position themselves for a specific use case, such as you mentioned, GameFi. And I agree with you that this might be an interesting angle to use in order to show that EOS can be used for other things that are more interesting instead of only using them in games.

#### DJSTRIKANOVA

Well, yeah, for me it was like it's perfect because you can be like, first you work and then you play, right? Yeah. You do your tasks and then you spend your EFX to play the games.

#### David Brit

Buyerskins.

#### DJSTRIKANOVA

Yes. Basically, the thing about work is actually it's like proof of work in the sense that proof of work isn't that big anymore, ever since Ethereum went off it. But basically you could take any GPU and do computations and then get rewarded for it. And so in that sense, you're just using your brain, right? That's the proof of work, your brain. And so I think work is a way to onboard people who just don't have as much funds to deal with all the hassle. For example, in the US. Coinbase got sued. The regulatory environment is so annoying. But if you really want to get on blockchains, being able to convert your work and cognitive effort into tokens, I think is a very big thing. That's my two cent.

#### David Brit

Yeah, absolutely. Just making it easier, right, for everybody to be able to make a living online.

#### DJSTRIKANOVA

And speaking of Pomelo, just going to pinch my grant for the NFT indexer. So this season, I made a demo and completed the Python scripts last season. So this season, I'm kind of hoping to get enough to spruce up the front end, have it integrated where you can click on it and buy it if you want it from the Atomic Hub store. And then also just find the collection specific to what you want, maybe even see look at the annotations for your NFT specifically. I think that's still in progress, right. The transaction to enable the profile NFT profiles for the Dow?

#### David Brit

Yeah, it's coming. I'm finishing it up today, so it should be up tomorrow.

#### DJSTRIKANOVA

Yeah. One thing I intend for the front end tool is you can, like, as default, it will show, like, the collections that are accepted. So right away you'll be able to search all the accepted collections for specific characteristics you want so you can find the best Dow profile picture if you want. So I appreciate any donations and any support.

#### David Brit

Yeah, awesome. I'll ask Gabby to also send a Tweet out for you for your Palm Lou grant.

#### DJSTRIKANOVA

Oh, thank you.

#### Jesse Eisses

Yeah, I'll definitely support it. I'll check it out and yeah, sounds like a great plan.

#### David Brit

I completely support it's. Like, I do need to get going, but yeah, thanks for the call and indeed, stay tuned for the profile picture selector. I'll give a shout out when we've pushed it.

#### DJSTRIKANOVA

Sounds good.

#### David Brit

Thank you.

#### Jesse Eisses

All right. Thanks, David. Bye bye. How does the Pomelo look like? Is it as big as last season or you said there was less submission so far?

#### DJSTRIKANOVA

I don't know. Are you also sure in time, I'd say last season they had one consolidated fund, so they had basically I forgot the exact, but let's say like $160,000 worth of EOS and everyone's sent to the same pool. And so this time they created pools with specific goals. Like there's a GameFly pool, which is like 65,000. There's EOS EVM pool another 65,000. Then there's everything else, which is basically a miscellaneous category 28,000. That's the pool I submit in mind because my grant isn't really EVM or GameFi. And then there's also a telos, because their goal also is with the specific goal oriented pools is to have other contributors create their own pools. So there's like many different pools. That's their goal. But from my personal opinion, because there's a less consolidated pool, I guess, or rather because of the focus on EOS EVM and GameFi, I think it kind of discourages people from other EOS projects. So I think there's kind of less participation, especially on those two pools, the EOS EVM and the GameFly pool. So I think if you set up like a grant for the I mean, I can check right now.

#### Jesse Eisses

Yeah, I'm looking at it. I think there's quite a few, only few projects doing Eocpm category.

#### DJSTRIKANOVA

Yeah, there's like there was like there's the NOAA Swap, which I know there's one team called Hokintech and they had a decentralized email and Nnft Marketplace because originally I wanted to submit my NFT indexer, I wanted to adapt it to EOS VM, but there's no marketplace for NFTs. Right. So I don't really have a good source of data, so I can't really realistically say I can do it. But yeah, there's not that many projects submitted. And I think if you created basically a bridge for EOS tokens and if you can make it atomic swap too, I think that could get a good contributions. I definitely would want to contribute to that.

#### Jesse Eisses

Yeah. Interesting. I'm going to take a look at.

#### Matteo From pNetwork

It will be great if it can.

#### Jesse Eisses

Benefit the broader Es community and be used for ESPN as well. Interesting to see the epic categories. I think I start to understand now how it's set up in Everything EOS.

#### David Brit

Right.

#### Jesse Eisses

So I should be able to find it.

#### DJSTRIKANOVA

Yeah, I'll post a link after this call, but in the general chat. But it should be in the Everything. Yeah, you can tell that if you go to Everything Els, there's a lot more submissions, so there's kind of like a lot of competition. So my goal is only like $500 to $1,000, hopefully. I don't think I can get much more because it's pretty competitive, I'd say, but the EOS EBM is not.

#### Jesse Eisses

Yeah, interesting. I'm going to dive into this and see if it's suitable to submit something like an atomic swap ridge. That would be interesting. And definitely I'll support your ticket as well.

#### DJSTRIKANOVA

Great, thank you.

#### Jesse Eisses

I think it's really cool what already came out of it. So keen to see the next updates. Cool. I'm also going to jump, but yeah, good call, everyone. I think it's just us left, but yeah, we'll stay connected in this card and I'll keep you guys updated on how we can do the bridge. Let's keep the discussion going because it would be nice to have a solution soon, and if the atomic swap work, then I'll share with you what comes out of it.

#### DJSTRIKANOVA

All right, sounds good. Yeah, we definitely want the bridge operational before we start the hackathons.

#### Jesse Eisses

Yeah, exactly. That's to be all done before. Way before then, for sure. That's August.

#### DJSTRIKANOVA

All right. See you all next time.

#### Jesse Eisses

Yes, see you. Bye. Bye.

#### Rochelle Trevarrow

Hey, DJ. I wanted to have a quick chat with you if you've got some time.

#### DJSTRIKANOVA

Okay. Is this the Dow call related or should I answer?

#### Rochelle Trevarrow

You can go ahead and record or stop.
