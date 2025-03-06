---
description: 'Author: @djstrikanova (DJ)'
---

# March 6th, 2025 Effect AI Community Call



{% embed url="https://www.youtube.com/watch?v=75gkDIyGYps" %}

**Current Focus on Technical Updates** \
\
– The team is building out the core protocols (worker nodes, manager nodes, and requestor nodes) on Solana. \
– A new off-chain architecture minimizes on-chain congestion, learning from previous issues on EOS.

**Off-Chain Task Processing & ZK Rollups** \
\
– Microtask submissions and validations happen mostly off-chain for speed and low cost. \
– Zero-Knowledge (ZK) proofs will batch worker earnings, then settle them on-chain to keep fees small and throughput high.

**Payment & “Base Pay” System** \
\
– Workers earn a “base rate” simply by being online, recognized through periodic challenge tasks (heartbeats). \
– If a worker skips too many assigned tasks (or fails these heartbeats), they risk losing that base pay. \
– The intention is to fairly compensate workers for “wait time” and quickly filter out non-responsive workers.

**Manager Nodes**&#x20;

– Manager nodes serve as middlemen, receiving tasks from requestors and distributing them to available workers. \
– Future plans include robust validation modules (e.g., repeated tasks, automatic checks) so managers deliver high-quality results back to requestors. \
– Managers eventually compete on fees, worker pools, and reliability, creating a market-based ecosystem.

**Migration Lessons from EOS** \
\
– High on-chain load on EOS caused gridlocks in task submissions and payments. \
– The new design on Solana uses off-chain processing with final on-chain settlement, avoiding transaction bottlenecks.

**Upcoming Releases & Roadmap**&#x20;

– Near-Term (Q1/Q2): \
– “V0” release of the product focusing on worker–manager interaction, payment proofs, and microtask completions. \
– Limited user testing (small group of workers) to validate architecture and gather feedback.&#x20;

**Later Phases:**&#x20;

– Integration of task providers with an SDK or REST endpoints.\
– Enhanced validation rules, dispute resolution mechanisms, and possible DAO involvement for conflicts. \
– Additional documentation, tutorials, and user-friendly interfaces (including notifications for workers).

**Community Q\&A Highlights**&#x20;

– Task-Skipping & Cherry-Picking: The system will allow some task skipping but track misuse (e.g., “cherry-picking” only easy tasks).\
– Notifications: Workers will receive browser alerts when new tasks or heartbeat challenges appear. – Longer-Term Vision: The team envisions frictionless experiences for both technical and non-technical users, with thorough documentation and examples.\
– Confidence in Solana: Low transaction fees and speed make Solana well-suited for microtask payments.

**Next Steps**&#x20;

– The team will finalize technical components for V0, then move on to the SDK for task providers. \
– Roadmap details, including major upcoming milestones, will be published after the initial release. \
– Continued community communication via blog posts, Twitter, Discord, and Telegram.



## Transcript:

**DJSTRIKANOVA | Effect DAO**: Hey everyone, this is the community call for, um... march sixth 2025 and I'm handing it off to the team.

**Jesse**: Awesome, its good to be here again. and I'm happy to be here again. Do you want to kick it off for sure?

**Rochelle T. | Effect AI**: Sure, yeah. So thanks everyone for joining us. These community calls are really fun. You know, we're in a transition time where it used to be DAO calls, but right now, you know, since migration to Solana, the DAO's kind of paused at the moment, but we are still doing all of that. This by meeting together and talking and stuff, and we have some great updates for you guys some updates about our development yesterday. We pushed out a blog that talked a lot about the worker nodes and manager nodes and requestor nodes. To try to give everyone an insight. Um. building upon that screenshot we showed of the worker node page on our platform that's currently in development. So happy you guys are joining with us today to get some updates, and I see some... of our OGs from a long time ago popping back up. It's great to see you back in here again, Elizabeth. you know, Mayjaw's always around and burn, burn. And Sharif is always so positive. And of course, Lenny and Dudu and Alan, you know, gosh, all these usernames sound hilarious sometimes. Um... You know, so happy to see everyone here with us. So, yeah, let's start with a few updates. Jeffrey, Jesse, do you guys have anything to pop in? Yeah.

**Jeffrey | Effect AI**: Yeah, sure. I'll kick it off with... with a few updates on the technical technical aspect. Yeah, of course, it's always a little bit hard to give these like technical updates. Because rather, you kind of want to show something to people. So it's so you're not like boring them with with a lot of like technical details. So I'll try to keep it a little bit brief and very high level so everybody can can follow along. I'm also struggling a little bit with a cold so Pardon my nasal sounding voice. So yeah, on a technical level, the main protocol that we're building, the Effect AI protocol basically, that will be comprised of a few smaller subset of protocols. And the most important one, of course, is the tasking protocol. So the tasking protocol is just the underlying software that makes workers and managers understand what tasks are and how to interpret them basically. I think as some of you have already seen, Rochelle, I think it was two weeks ago, we posted a little teaser on The worker dashboard, it's not final or anything, but basically that's a little demo of the tasking protocol and a worker can basically join a pool there, connect up with a manager node and start doing tasks, completing tasks, etc., So another very important part of this whole puzzle, this whole protocol is how are we going to handle payments, basically? Right. Because without payments, you're just going to be doing tasks. Yeah, it's a very important aspect. Right. And of course, we try with this protocol that the main goal is to handle as much off chain as possible because we don't want to fall into the same trap. like pitfalls that we did on EOS. Basically, we've learned from our mistakes. So we tried to do as much off-chain as possible and only do the very necessary things on-chain, basically. So once...

**Rochelle T. | Effect AI**: So you guys, you remember on EOS when you're trying to do tasks, but then it just gridlocked, right? And we couldn't do anything. You couldn't submit a task after you did it, and it was a huge pain. So this is where in the blog yesterday, it talked about those ZK roll-ups, and that's where it allows us to do... A lot of the submission and receiving still all transparent. Um, all all batched together. So all this extra traffic kind of not on the main chain, taking all the resources. So this clears all of that frustration that all of us were having when we were doing tasks, um, on EOS, where everything was like completely pushed right to the main chain in real time and it just gridlocked and. All that problem so. That kind of explains, ties in a little bit with that, so sorry it's I'm excited about it so sorry I had to explain it

**Jeffrey | Effect AI**: you gave a little hint about the technical aspect that we're trying to solve the problem with but Basically, what we're trying to aim for is once a manager gets a task back from a worker and he does his final checks, he thinks it's valid, it's completed, the manager will generate a payment, right? And the payment is basically just a small piece of data. It's basically just a proof that you did work and you can basically redeem that payment. the worker can redeem that payment um hand it over to a smart contract on solana in this case but can very easily be be ported to to any kind of blockchain the logic is is yeah quite uh quite light um yeah and then the worker will get paid out on chain right so just by submitting a basically a payment they will be paid out without any sort of state that you have to... yeah, keep track of on chain like we had on EOS. We had all the campaigns, all the tasks to basically check. Is this task completed? Yes, you can pay it out. But you don't want all that. So. Yeah, there's a few things that that's a few gotchas, I would say it's a few technical roadblocks that we had to tackle with to make this possible, basically to enable like off chain. payments and how they will settle on-chain. The most difficult one is Yeah, we're dealing with micro tasks, obviously. So we're also dealing with micro payments. So payments might be very small, it might be couple cents, might be 10 cents. It depends really on the campaign that you're doing, right? We're lucky that we're on Solana because let's say you would submit one payment and four, four, four, five, four, 10 cents. Solana is quite cheap, but still you don't want the payment to be 10 cents and the transaction costs to be five cents, right? That's, That's, yeah, that's horrible. Like, that's almost like Ethereum-esque gas fees kind of thing. So, yeah, we were trying to, yeah, find a solution for this. Basically, how we can bulk many, many, many different kinds of payments into one single transactions. And maybe Jesse can go a little bit more in detail about how we... Try to solve this issue and what we have in mind for solving this.

**Jesse**: Yeah, of course. That was a good explanation. Jeff thanks for the yeah for that because the main updates we're sharing now are technical ones as we're we're going towards like a finished first usable version of the product that's working from A to Z and a lot of components are there, like, like Jeff just mentioned, the new architecture that we're using is going to ensure that we have like blazing fast interaction. So because not everything has to settle on chain, we're able to have like immediate responses. And once you get a micro task and you submit it, that will just all be instantaneous without having to wait for any settlement. So it means that we're able to keep a lot of the data private. So the tasks going into the network can be private to both the, like not the whole network will be able to see what kind of tasks get posted and also the results that come out of that can be private to the, to the task provider, to the, to the person that puts the data there. So it gives a lot more privacy to the network. But what we're basically doing is creating this second layer where there There was a lot of interactions happening between data being annotated by humans and like little proofs being generated that this has happened. But there is the crucial moment that that's technically like kind of challenging to solve. And that's the one thing I think the update that Jeff referred to and that is, I guess, the most exciting to talk about and without going into too much technical detail. the moment of payment is is what's the most interesting in this setup as once you've been working for maybe a few days in a row you have collected a lot of you have done a lot of data annotations and you will have all these little receipts of the data that you annotated and the system that we're designing now is that you're able to claim the payment for all the tasks that you did through a smart contract on Solana and by using like a zero knowledge proof of the work that you've done. So that's sort of the ZK rollup Rochelle mentioned. It basically means that you generate a proof of the work you've submitted over a period of time and you will get paid on chain for that amount of work. So that is the one feature that we're currently still putting into place in the system we're currently building. And yeah, that's sort of the final piece that's still being finalized. But we're really excited that this all came together now. Like we're very confident that the pieces that are there will work as designed and we'll have the... the benefits that that we just named um that they that it will work out so yeah the payment uh

**Jesse**: The payment system is one of the coolest elements that we've made so far. We're also working on creating a blog post and some accompanying documentation to explain how this works. And yeah, I guess that's as far as it makes sense to discuss the technicalities. Like if you look under the hood, there is a lot of cool like mathematical and new cryptographic constructs that have become very popular lately in Web3 space. We're kind of taking advantage of the fact that the zero knowledge proof sector, like that area of Web3 has been really maturing lately. So there's a lot of tooling available for generating these proofs. And they're so powerful. I think it's one of the most coolest technologies. and they're like a perfect fit for our network right now to be able to scale and be user-friendly. Yeah, that's, that's, that's, I think, on the technical side, the most interesting updates, maybe one other part that's worth to mention is

**Jesse**: Because of course there's more elements to our network. But I think what I would like to quickly mention in this update too is that we're working on a system for making the validation of tasks more easy, but also more trustworthy. That's also an element that historically has been quite tricky to make sure that the workers that are online that are submitting tasks, that they are doing proper work and that we can basically cancel out or that task providers won't be exposed to new workers that don't do work properly. And we have a system in place, we're developing that now for this first version of the product where as your online, a worker will be able to get a base rate. So you will always, for just being online, being available, basically providing that supply of your talent to the network. While that's there, you will get this base income from being available. that's sort of the the system that we have there like this the sort of we call it a heartbeat but like it's it means that you're available you're providing talent and and you get paid for for being there and then we have another system that basically posts challenges to the worker so it means you will get from time to time a special kind of task that the task provider knows the or that the the manager nodes knows the the answer to and once you submit that then when manager will be able to validate that the answer is correct. This is a system that we're also already employing in that first version because it's so vital to getting quality people on the network. So that basically touches on the validation that's sort of mostly automated in this version of the product that we're also excited about is it's going to make the network a lot more manageable in a high quality setting.

**Jesse**: Those are technical updates up to this point. Not sure if you wanted to add more, Rochelle, or we want to leave some space for questions before going to the next topic.

**Rochelle T. | Effect AI**: No, I think you touched on that quite well yesterday in the main chat. DJ, you brought up something about the – Validation and things and how it will work out. Um, but I think Jesse touched on that a little bit. It's still being built. Did you want to ask any more about it, D.J.?

**DJSTRIKANOVA | Effect DAO**: Yeah, so from what I understand, you mentioned that the tasks now are more private. So how would the worker know Like from where do they get the tasks like to see to complete? Is it something the manager node will be responsible for?

**Jeffrey | Effect AI**: You want to answer this one? Let me answer it, Jess.

**Jesse**: You can go ahead.

**Jeffrey | Effect AI**: So in the V0, how it works right now, is it's basically a dumbed down version of how we envision it. But to keep it simple, workers will pair up with manager nodes and manager nodes will basically listen for tasks in the network from providers and they will start assigning tasks to the workers that have connected to them basically. So it's just a simple queue system. So let's say 10 people connect up to a manager node and then the manager node will start to wait for tasks. Once he gets the tasks from providers, he will just give the tasks to the workers in a fair way, basically. That's for the v0. Of course, there's very cool and intricate algorithms that we can think of to make it more fair, to make it more honest. but for now it's just a simple queue system. I don't know if that answers your question.

**DJSTRIKANOVA | Effect DAO**: I see. So then this node is quite literally like a server node that they run. Not only do they stake, but they like... you know, run something on some server to propagate these tasks to workers.

**Jeffrey | Effect AI**: Yeah, exactly. So, yeah, right now we envision it, yeah, a manager node to be ran like a, VPS basically. This might change though, we're not 100% sure yet, but at least for the v0 it's just kind of like a server. run in a hosted environment somewhere or on a decentralized Yeah, compute provider somewhere

**Jesse**: And then for validation, can you go more

**DJSTRIKANOVA | Effect DAO**: Maybe I missed it, but like to verify the tasks that were completed, I assume someone else needs to like review it, right? Yeah. So what does that mean in practice? Yeah.

**Jeffrey | Effect AI**: Yeah, so what Jesse explained is also, I guess, called validating, but of course, there's another part of the validation of tasks, right, to make sure or to check, basically, that the tasks that are submitted by workers are up to a certain standard. Yeah, that system, we're still working on it, how that's exactly going to work, but... I think in a general overview a task provider can basically supply the amount of, basically the rate of how much tasks will be validated inside of their campaigns, maybe percentage-wise or... Because, of course, it's a lot more work, right? And the payment has to come from somewhere. So let's say you have a campaign that requires a very, very accurate work. The task providers have to... basically pay more in order for their tasks to be validated a lot more. Um, and then every time, every time, uh, the worker submits a task, uh, According to the number of the validation rate, basically, the manager will send it out to validators. and they will get it back. That's maybe in a high level overview of how it's going to work. the validation process. But what Jesse explained is also part of it. But it's more to fish out the bad actors from just staying online and not doing any tasks at all, basically. And claiming their... base rate of effect.

**DJSTRIKANOVA | Effect DAO**: I see, so workers will be expected to complete tasks if they're available.

**Jeffrey | Effect AI**: Yes, yes, exactly. If you're in the pool, you're basically saying, I'm ready for work. If you're not ready for work... or you've been shown to not accept enough work or um yeah there might be some sort of punishment for that but yeah this is all still um

**Jesse**: due to change. This is the new sort of paradigm where when you're available as a as a worker you are you're online and you're getting like you you've indicated to the network that you are ready to take on tasks which in that instance you provide basically your talent you provide power to the to the network you you you are you're there ready to to take on so the capacity of the network increases on the number tasks it can handle and you that's also when you get like this base income already for for adding that little value like for for being there it also means that when you get assigned a task that that you are expected to to actually handle that task because if if you're no longer available you should also indicate that you're not available

**Jesse**: And in this new paradigm, basically, we see workers that are online with either a mobile device or in the browser. And once work for them becomes available, they will get a notification. And of course, I mean, there will be some sane amount of like being like reasonable amount of opportunity to skip on a task, for example. Perhaps you can do that once every now and then. And we're not what we're not sure about yet is exactly how harsh the punishment should be and what kind of punishments do we want to add? and exactly what triggers but If you're available, you should basically accept the task assigned to you into a reasonable amount um and that's yeah that's that's that's how that works and when it comes to the validation part like i think jeff explained explained really well and in the beginning we're probably gonna go like as a manager note you can have certain modules in there on how you want to validate tasks and one of them will be to sort of automatically do that through challenges which means that you're from time to time posting tasks that you know the answer to when you use that to automatically validate but we can also add modules later probably that are a bit more in depth for example managers could like post tasks again to the like when when when they receive results to post the task again or to basically post a task to validate that results to a different pool of workers and in that way get a higher confidence on whether the the result is correct that it received as in the end the manager is sort of responsible for what he's going to serve back to the to the provider So the module that takes care of the validation can be more complicated and will become more complicated over time. to get that high confidence score for the results that flow back to the provider.

**DJSTRIKANOVA | Effect DAO**: Got it. And then I guess this is going to be implemented I guess much sooner or much later. But then the slashing, I figure that's where the DAO would have to come in to settle disputes of some sort.

**Jesse**: I think so. I think that's the part that's kind of hard to predict ahead of time. Like we can have some some idea of how this will unfold and, and how that will work. But Yeah, definitely the DAO will play a role. Like when disputes arise, like when data isn't good and, Like there definitely needs to be a sort of dispute resolution on a higher level that will be handled by the, by the DAO. Um, that will definitely be there. But there's also going to be some automatic slashing happening. For example, when workers decline too many tasks, they should be able to, like we should, because they get that base pay, but if they're not available, that means that they should be punished in some way to discourage them from just being, collecting that base pay, but never working. So there is some expectations on different levels of the network. Exactly what kind of punishment will happen, like what kind of slashing will happen, and exactly at what points this boot rest solution is used, these things will be developed at a later time. I think it's also very... as the network grows and as the user network grows then these things become more and more and more relevant i think in the initial release we can get away with quiet basic elementary systems on on punishing workers as it's kind of easier to keep an eye on the whole thing

**DJSTRIKANOVA | Effect DAO**: And in regards to workers, would the manager nodes be responsible for, I guess, recruitment? Like, there's like some sort of way that they designate someone.

**Jesse**: as a valid worker.

**Jesse**: Yeah. Yeah. This is also part that will be like this part will also be like get more evolved and more like advanced later on as we progress but that yeah the manager is responsible for having a group of workers fight and reachable within its network so manager notes actually they they look around the network and they they communicate with workers that are connected to the network and they identify the ones that that are interesting and they will be able to address them so basically delegate tasks to the ones that that they get a connection with and that's currently happening again in a pretty simple way as we're going to start off with just a few types of tasks and a few types of worker talents that are on the network but that can get more complicated and like it's again a module that we can make more complicated and more advanced as the needs of the network might change um so managers might get very advanced ways of recruiting workforce members um that's something that that's uh yeah it's not totally predictable yet but like the first elementary version basically means that workers just say hey i'm i'm available um this is the proof that i'm available and i can do these types of tasks and managers will just basically keep a list of all these announcements of the workers and then yeah just distribute the tasks to the ones that are available it's like the routing like like managers are responsible for routing the the tasks to the right worker.

**DJSTRIKANOVA | Effect DAO**: Got it.

**Rochelle T. | Effect AI**: Oh, quickly, to re-circle back to the task skipping thing, you know, it In our version on EOS. I would get a lot of requests from the workers like, you know, is there a way for us to skip this task? and then you know we instituted a thing where we could report the task but then that caused some problems um with the protocol um so you know that's a feature that all workers even on other platforms you know appreciate being able to just skip that task or, you know, send it back in the pool, you know, and get another one. But also, there is a problem... with on other platforms that I've experienced. And I've leveraged this myself. I have been, we call it cherry picking. And I have done this before too. Where you get there's a batch of tasks and you try to get as many done as you can, you know, before they're all up from all the other workers in the pool doing them. And so if you've come upon one that's going to take a little bit of time, it's not as profitable for you as a worker to do it. So you skip it, you throw it back in there and you're basically just cherry picking all the quick, easy ones. Well, on some platforms there is like a rejection rate, not a rejection rate, um, Uh, uh, return rate where they take the percentage of like all the tasks that you've done against the percentage of tasks that you have just quit and said, no, I don't want to do that one and move on. There's all kinds of things. So there will be a metric set, you know, because it's not fair to the whole pool for cherry picking. You know, but there are some instances where you get something and you're like, I am not prepared for this. I can't do it. Or something in the personal life happens, you know, a phone call or your Internet goes out or something. And then you have, you know, sent it back. I mean, those things happen. So. Yeah, coming up with a thing for that. But yeah, it's a good feature to have, but then also it's something to guard against for cherry picking.

**Jesse**: So that's all the questions. from me Jesse you had another thing you wanted to discuss?

**Jesse**: You're kind of breaking up right now Jesse

**Rochelle T. | Effect AI**: Did we lose them? Oh, he'll probably pop up back up. Give him a moment here.

**Jeffrey | Effect AI**: Maybe while Jesse's fixing his connection or audio if there's anyone from the audience with like specific questions technical questions or anything about the protocol or something i'm happy to to answer them

**Jeffrey | Effect AI**: Alan asking if we're still on track. Can you give us a time when we're up and running? Yes, for sure. We're definitely on track. I think Q1 has been mentioned a couple times. I think it's always hard to give hard promises. But with how it's looking right now, I would say we estimate something to be out there, something very... something very basic at the end of this month, maybe in the middle of next month. That's kind of the next deliverable estimation basically. Yeah, don't quote me on it. It might, of course... We're solving a lot of very hard technical problems with the systems we're building. So we might hit a few delays here and there. But yeah, how it's looking right now is... positive.

**Jesse**: When you mentioned

**DJSTRIKANOVA | Effect DAO**: the minimal state

**DJSTRIKANOVA | Effect DAO**: how would that look on the task provider side? Would there be

**Jesse**: Also, like a minimal SDK.

**Jeffrey | Effect AI**: Yeah, we're trying to, well, for sure, once we hit like a beta or alpha version, there will be some sort of SDK to be able to post tasks into the network. For the first version, I'm not sure if I can comment already on what that is going to look like. Yeah, how the task will be coming into the network is still something we are figuring out for the first version at least. If that's going to be tasks provided by partners or tasks that we are going to provide in the initial beginning. So we're not sure yet if the SDK, the belonging SDK will be out there for the first version, but it will definitely, yeah, it will definitely arrive once we push a beta or alpha version.

**DJSTRIKANOVA | Effect DAO**: And as Elizabeth asked, so do you think there will be tasks to complete with this minimal launch?

**Jeffrey | Effect AI**: Yeah, there will definitely be a lot of tasks to complete. That's what we're aiming for. Yeah, we're aiming to really not only... yeah i have a like a working product but also tests really test the the the systems that we're building by basically having people doing a lot of tasks on the network and see how everything balances out and how everything is working and integrating together. There will definitely be work, enough work for our workers to do. Not everybody will be able to sign up or we're going to handpick. a few people to be able to receive tasks basically for the first versions but those that that will yeah are able to receive tasks they they will have enough work for them

**DJSTRIKANOVA | Effect DAO**: And Jesse, are you back? Is your microphone working now?

**Jesse**: I think so. Yeah, I could hear the last 30 seconds of Jeffrey talking. So I hope I'm better. Great. Then it should be good.

**Jesse**: I missed quite a bit. of the conversation. over the last few minutes.

**DJSTRIKANOVA | Effect DAO**: It was just a question on the state of the SDK for task providers in the first version, and Jeffrey mentioned that. it likely will be more... It seems like, to me, it's going to be focused more on manager nodes and worker nodes in this first version. And then... and task providers will come after. That's my interpretation.

**Jeffrey | Effect AI**: Yeah, exactly. So the first version is really to see how the protocol behaves, basically, and the manager nodes and the worker nodes, how that all balances out. And the next push will be, we'll have a heavy focus on getting like a real tasks into the network.

**Jesse**: Yeah, indeed, like the first time tasks that we're gonna support like probably we'll figure out a way to make it quite easy to to add some tasks to the network like sort of a like just a rest endpoint of a service we host so so that can be used to add tasks to the network like posting them directly to relevant managers and then that can be used by by like anyone to add tasks sort of in a controlled setting but like indeed the full like build it yourself task provider SDK will be a bit later down the line we don't think we it's not a priority right now to to get that um finished because we first want to have all the other elements there so for each types of tasks that we support we will probably write like a little server or some some system ourselves that pushes the tasks into the network and then that that will probably be exposed as like a rest endpoint like we'll we'll start off easy and and then make like in the next iteration in the next next phase where we will work on the full-fledged sdk for for task providers so that's yeah that's that's basically not part right now of the of the next of the upcoming release

**DJSTRIKANOVA | Effect DAO**: gotcha And then before you got disconnected, earlier before I started asking all the questions, you mentioned you had something else you wanted to discuss.

**Jesse**: I didn't myself have something else to discuss. I thought there was an agenda or topics like community questions. Uh, but I, maybe, maybe there isn't. So I wasn't aware. Um, I just wanted to leave some space in case there was more to discuss than the technical updates.

**Rochelle T. | Effect AI**: Well, let's see, let's open the chat. Um, Alan's typing.

**DJSTRIKANOVA | Effect DAO**: Well, aside from the technical updates, we have seen Rochelle post a lot of content on the Twitter and writing out all these blog posts, which is good.

**Rochelle T. | Effect AI**: Thank you.

**DJSTRIKANOVA | Effect DAO**: I think, I guess I do have like more other questions. So you mentioned that workers will be paid. as a proof of being available. But where does that money, where does that come from, like funding wise? Is it something manager nodes will pay? Is that something the network fees will be expected to, I guess, pay for

**Jesse**: Yeah, good question. So this iteration, it's the manager node that does that to incentivize the workers to be online. we are considering like to blend this into the tokenomics more like instead of just having it as a as a manager note provided fee it kind of is very close to like in a technical in a technical sense it's very close to how the current staking pool works that has like a base income um system as well like it has this continuous element where being being staked gives you that uh that reward rate which is nearly identical to to like being online so on the smart contract level we're reusing a lot of what's happening and we are quite tempted right now to blend partially that together so to have like these pools of of basic income for the people that contribute to the network and also take a look later on how that how we're going to reward DAO participation how we're going to reward so i think yes the the the the answer to that question directly would be that i would like to to have this part of the tokenomics where being like contributing to the network in different ways gives you this this rewards and then one of those ways is to be available which is a specific case and that those tokens would come from either like the incentive tokens like the mining incentive type tokens of the network or they could come from network fees later on But this needs to be further worked out. Like at the moment, these are just basically up to the manager to provide. And then the manager that we're going to launch, like that will be launched in the beginning, will be expected to provide. some tokens for accommodating the workers that start.

**DJSTRIKANOVA | Effect DAO**: Yeah, I think, like, just thinking about it for a bit, I feel like it has to be the manager nodes who provide this because... Otherwise, there could be an incentive, you know, just to create a manager node and then have them like do nothing and have the workers collect the fees and stuff. or not the fees, collect the, the, just the proof of existing, um, So if the, I figured the manager nodes themselves will be able to Apply their own, I guess, manager fee to tasks And that's how they can be competitive with other manager nodes Like some will be maybe slightly more expensive But you can kind of expect more quality work from them So I figured for keeping their workers happy, they could also make sure there's a decent, I guess, proof of, uh, being available, involved in there too. Kind of just a market so we can the ideal ratios can be established kind of in a freeway.

**Rochelle T. | Effect AI**: Yeah.

**Rochelle T. | Effect AI**: Okay, yeah. Um, with this, you know, a big thing, working on other platforms and stuff, you know, as a worker, when you're just waiting for tasks to appear, and you're available and stuff that's to me that is unpaid work. And when I relied solely on all these micro tasking platforms, you know, for an income being on like seven of them at one time. you know, being available, you never got compensated. And so, you know, that's a thing. You're, it that in like, I don't know, some of the, like the, the, um, gig economy stuff, they started paying people who were like in the queue and things like a little bit of a base pay. Um, and, um, That's 1 thing that's very important for me, because. you know, that's time, that's time you're putting in and being available, you should be compensated for it. I mean, even if it's not much, you still should be. And then when it comes to like, the manager node thing, you know, there's ways that that could become very, very lucrative. You know, you're talking about finding a pool of talented workers for different things and then you know, incentivizing them to do the quality work and then they'll stay on and they'll stay connected to you. and provide you quality work because you know they're they're making Making good money doing the tasks for you and So it's all about incentivization and, you know, about what you make it. And if there's some really motivated people, you know, they can make being a manager, you know, very lucrative, you know, and workers can even make a very productive. this being on our platform very lucrative for them too as long as it's you know quality stuff so This stuff, this part of it, I am just... super excited about because it's it's my jam so There's gonna be some exciting things happening once this whole thing is all completely done.

**DJSTRIKANOVA | Effect DAO**: As DuDu asked, do you intend to publish the roadmap

**Jesse**: Yeah, we intend to publish in more a. detailed roadmap on what's coming up at the moment. We just like focus on this release. We want this release out and, and have a few users using it. But once we hit that point, we will like release an accompanying roadmap that goes further out and, and we'll discuss the features and, and improvements coming, coming later. So we, yeah, we do intend to release that.

**Rochelle T. | Effect AI**: Alan is asking about the older blog posts. Uh, they want he wants them up and available.

**Jesse**: Which blog posts like...

**DJSTRIKANOVA | Effect DAO**: From the redesign the site. The prior blog posts were lost perhaps.

**Jesse**: Like on staking, right? And then some other ones, I guess, were there.

**Jeffrey | Effect AI**: I don't think we'll be putting those back. A lot of them are also kind of outdated and not really relevant anymore with our current tech and will only confuse people. So...

**Jesse**: Yeah.

**Jeffrey | Effect AI**: I don't think we're gonna bring those over, Alan. Sorry.

**Rochelle T. | Effect AI**: No, I think he's talking about like the ones since we did the migration, like the more recent ones.

**Jeffrey | Effect AI**: Those are on the website, the migration blog post, you mean?

**Rochelle T. | Effect AI**: Yeah, those are on the website. Did we add pagination? Yeah. Oh, we did. OK. Uh, Alan, wants to know if I'm getting extra help and getting this work done. Yes. Yes. Don't worry, Alan. I am good. We are all good with this. Alan, this is my dream job. This is my career. There's no way I would burn out.

**DJSTRIKANOVA | Effect DAO**: I think the only comment I'll have is, oh and Lenny's talking about Base Pay too.

**Rochelle T. | Effect AI**: Yes, Lenny, you get it. I've been there.

**DJSTRIKANOVA | Effect DAO**: The only thing, as you mentioned, using the staking system we have, though, wouldn't you want them to kind of just like, you know, like clock in and clock out, because you can't expect the person to like be available 24-7, right? They have to sleep. So you kind of like want some sort of turn off and turn on your availability.

**Jesse**: Yeah. definitely need to be able like because because we're human right and we don't want to like if you're online and you forget to sort of clock out or like say you're not available and like you don't want to get punished for for that normal behavior so there needs to be the rules need to be flexible enough to to allow these these common mistakes but also discourage people to just farm the basic rewards so that there's there's going to be like i guess that's what you meant did you but there's a balance to be found there.

**DJSTRIKANOVA | Effect DAO**: Oh yeah, yeah, I just... Because I was just thinking the current staking system, like you can... it's 24-7 right you accumulate rewards but with with clocking in and clocking out, there's always going to be a time period In fact, it'll probably be suspicious if a person, you know, is always available, right? Because, uh...

**Jeffrey | Effect AI**: Right. Yeah, that's why we kind of what Jesse mentioned earlier, right with the challenge system. So every now and again, a worker will receive a challenge from a manager. It's basically a heartbeat or whatever you want to call it. If the worker fails to complete the challenge or doesn't hand in the challenge, you will just get kicked out of the pool. I think that's the most... yeah obvious approach for now you will not get any punishment you will just not receive your last uh... Yeah, X amount of minutes for the base pay.

**Rochelle T. | Effect AI**: There's no way you can use like a mouse wiggler for this.

**Jeffrey | Effect AI**: No, no, it will not be solvable by a bot. That's the whole idea of the. challenges yeah

**DJSTRIKANOVA | Effect DAO**: Oh, and I guess my last... Another question is... So, because you... We really want the workers to be able to respond quickly. how would that work in practice? Like, will they be having a browser-like app ready to give them notifications when there is a task available. Or is it on the phone, like a mobile app, What's, the vision here?

**Jesse**: Depending on the platform used first thing that's coming out is the web based one and I assume that there has to be a notification, right? So I assume we can use the, like these, the, the, the notification web technology to, to basically allow that to happen. Also, I strongly believe that mobile is an important platform for notifications for these types of things, as it's quite important that you respond to these certain challenges that you get from time to time. But I think Jeffrey might have better ideas on this, but I think that the version already has a notification method where when you get the task, like if you have your tab open anywhere on your computer and you get a task, then you would get a notification pop up. I'm not too good in the web technology stack, but I think that's what we can put in place already.

**Jeffrey | Effect AI**: Yeah, that's not too much of a... Yeah, too difficult to implement. The only thing is that... You have to request permission from the user to be able to send notifications through the browser. will probably have to make people enable the notifications in their browser. And then whenever you get a task, you will hear a sound to alert you.

**DJSTRIKANOVA | Effect DAO**: And the workers have the incentive to enable the notification

**Jeffrey | Effect AI**: yeah exactly exactly so um i think i think that part will be uh yeah will not be too difficult

**Rochelle T. | Effect AI**: Either a bell or I say a screaming goat. We need that notification.

**Jesse**: Yeah. We were also experimenting a bit with like um browser plugins it's kind of cool it's it's it's it has a purpose for specific types of tasks that are more related to scraping data i think the browser plugin would be a good platform but we were experimenting a little bit with that as well and i don't think that's going to be like the the way we go with especially at the start because of security reasons and and plenty of other things that are like people don't really like to have too many browser plugins installed so so but that's also an option to notify like there's different ways we we could potentially uh accommodate but the basic one it will be like once we release will be like the the web notification thingy that you have to approve

**Rochelle T. | Effect AI**: you know, want to try to avoid, you know, with our platform is, uh, like take for instance mturk, You know, there is no support for workers. Workers had to band together and make their own, you know, browser extensions and tooling and scripts and stuff, you know, to help them find work, to be notified when work, you know, was up and new things. And so that's stuff that, you know, we're taking into account with the platform, you know, as we build it out is, you know, it shouldn't be that way. um everything should be all inclusive for a worker you know to make the best of their experience on the platform so um yeah those are those are things that you know we're also cognizant about as we're building

**DJSTRIKANOVA | Effect DAO**: So then For Q1, what do you envision happening Not 100%, but that's mid-April. is this phase where we're gonna test manager nodes and worker nodes interacting with each other. And then what follows after that, I guess, for the next quarter. would be the task provider system with the SDK and all that?

**Jesse**: Yeah, that sounds right. That sounds right. We're not like we decided to not commit now 100% to when this is going to come out, but we're we are very close. And this first version is going to come out pretty soon. And then it will have a small user base and we'll be able to we want to make also alongside like some kind of Explorer or dashboard where you can see what's happening. So these are things that we're going to see soon. also going to publish a lot about the architecture and and like really make sure that the documentation on how things work and how to use them is is very um it's just available so it gives it gives a lot more substance but and then like you said dj then we will work on the sdk for for making tasks providing tasks very very easy so that's that will come after that along with like another we will like work on a roadmap as well so so we can Look like plenty of milestones ahead that are important to hit along the year. But the things you mentioned, yeah, those are correct.

**DJSTRIKANOVA | Effect DAO**: Yeah, I asked about the SDK because, like, Like, are you familiar with the term vibe coding? It's getting pretty good now that I already built my own transcription app for these DAO calls and it divides up. into various chunks, small little, you know, between every pause like content. which then I can process with Whisper locally. and really the only step left is just having a the workers complete a review of this because there's, you know, a bunch of micro speeches I don't want to review personally. So yeah, I figure like once, with the way Vibe coding and, you know, code generators like Cursor, you know, If you have a good documentation for the SDK, and people can just like, you know, copy some template and use it as an example and then just use that to generate more templates, generate you know, the all they need to quickly, you know, build stuff up, I think, We're in a much better advantage compared to EOS days Because back then you needed pretty good technical knowledge To build the templates and build a DApp But I think we're going to get to a point, right, when this is launching that it's a lot easier for the lay person to build something that they envision. And so hopefully we can get to that state.

**Rochelle T. | Effect AI**: Yeah, I agree. I think so. A big part of, you know, what we need to have is usability. So great documentation that's very clear, not only for a technical person, but someone who's just new, you know, trying to do it, who's maybe not technical, you know, we need just tons of tutorials, tons of documentation, you know, videos, Um, how to stuff that is, that is all in the works because you can have a great product, but if nobody knows. First of all, what it is, what they can do with it, and then how they can use it. It's not going to go anywhere. So...

**DJSTRIKANOVA | Effect DAO**: Yeah, primarily it should be text-based. Because that's the easiest to just copy something and then paste it in chat GPT or Claude and be like, so this is this. by effect AI, now build me, you know, a template for this. And I mean, like, it pretty much gets it right. Um, So that'll make things very easy compared to in the past.

**Rochelle T. | Effect AI**: And we have to have the stuff out there so all the AIs can scrape it and then know what to do with it and teach people. So.

**DJSTRIKANOVA | Effect DAO**: Yeah, like, the only question will be, like, um, The heartbeat will definitely need to be a good anti-AI agent check because AI agents may be competitive with some workers in the past. So the quality of work will need to be higher. because AI agents too are getting very good.

**Rochelle T. | Effect AI**: Yeah, it helps build them to be very good too.

**Rochelle T. | Effect AI**: whole circle.

**Jeffrey | Effect AI**: Alright, I have to run soon guys, so I want to thank you all for coming. today and I hope you guys like the updates. I have to go you guys can continue on of course.

**DJSTRIKANOVA | Effect DAO**: Bye, Jeffrey.

**Jeffrey | Effect AI**: Bye-bye.

**Rochelle T. | Effect AI**: Yeah, we covered a whole hour now.

**DJSTRIKANOVA | Effect DAO**: Yeah, aside from, as Rochelle and Chariff, you talked about the marketing, I did mentioned to you too, for some reason SolScan took off the icon for the effect AI token and they still have yet to update, like, the social links, and so... I can't really communicate with them. They're like, you don't have an Effect.ai email domain, so screw off. That's basically what they told me. So someone needs to, like, I'm not sure if you can just do that for support or something else needs to be done.

**Rochelle T. | Effect AI**: I did their little support thing, you know, submission and I still haven't heard back from them yet. I don't know. They're these places they just I think just take forever to get stuff done with, but I am working on that one.

**DJSTRIKANOVA | Effect DAO**: Its good to have that in the pipeline.

**Rochelle T. | Effect AI**: Yeah.

**Jesse**: Its strange that they suddenly dropped that. I was looking into it. I'm going to pick this up as well again. I haven't found out yet. what happened so yeah but good one we'll get that sorted well it's on the list uh within the team and someone will pick it up and chase it because uh yeah i understand you you if you don't have an official email or something they often don't to your requests.

**DJSTRIKANOVA | Effect DAO**: yeah, aside from that there's not much we can do on marketing because the environment is just very um i don't know Fearish, is that a word? Scared? for things we cannot control but I think the timing is good for the development, cause, uh, I think things will get better later this year

**Jesse**: Yeah, crazy time. so much happening in the in the space right now and but I absolutely agree I think time now is as good as ever uh to to get the product out there and I also think there's a lot more coming this year like probably up and down and uh we'll see but uh I'm pretty optimistic on the on the long run of web3 as always so

**DJSTRIKANOVA | Effect DAO**: Yeah, I think it's a perfect opportunity to help build up data sets. Because even like with this transcription stuff I've been doing, like Whisper and These transcriptions, they're only like 90... 85% accurate so it's kind of surprising how good the text applications are, but then with, uh, voice like processing is actually not that great still it's still like kind of janky So I figure it's just the variability of the human voice is much greater than the text. And so I think that can definitely help create more datasets.

**Jesse**: Yeah, absolutely. Absolutely.

**DJSTRIKANOVA | Effect DAO**: Alright, I think so as you mentioned, it's been an hour. Is there anything else we'd like to cover?

**Jesse**: I think we covered it all. That's where the updates for now and it's indeed been an hour that went faster than I thought. But thanks everyone for listening in. Thanks DJ for being here as always. From my end, I think there are no more updates. Any closing remarks?

**DJSTRIKANOVA | Effect DAO**: Well, we're definitely going to get... a big, shift in things because I think chat GPT just released a $2,000 like AI agent plan And I assume they would only do that if it's actually good. So... the amount of data that will be needed for these agents. Like I think, uh, They're not here, but they're saying like things such as, uh, like you know interacting with the browser right like i've I've been seeing a few applications where AI agents like, basically just mimics being a person you know clicking on things on the browser to do some sort of problem solving but that stuff is really complex like for example I've been playing around with trying to create an AI agent that can play games. And like a lot of games have like user interfaces that I'm sure you can just build a data set like, probably far future. Like this is probably something that couldn't even, won't be done for a long time, but I'd love for like, Some training Like if you could Kind of combine Nosana and effect So that you can Build like a your own model by like, you know, commissioning data sets and then having that be, you know, trained on Nosana GPUs. So that way you can like create your own specialized model for whatever, like niche you need filled i mean i think that would be incredible incredible offer to many people.

**Jesse**: Yeah, indeed. Did you say $2,000 a month, like agent plan for OpenAI?

**DJSTRIKANOVA | Effect DAO**: Yeah, like I saw on Twitter, yeah, it's like $2,000 a month for their AI agent plan.

**Jesse**: Interesting. Yeah, yeah, the space is just it's definitely going, growing and going to new places. So that that time and place for practice now. Like there's so much that we can integrate with.

**Rochelle T. | Effect AI**: It's never going to take over human stuff. There's always going to be human insight in. and intellect needed for these things. I mean, they may make our lives easier, but nothing will ever replace us. That's a thing.

**DJSTRIKANOVA | Effect DAO**: Maybe. Maybe. I'm on the fence on that one. because I mean my my my skill set has been completely automated away but so I gotta figure out other ways to do things

**Rochelle T. | Effect AI**: Join the dark side because they got cookies. Okay. Well, I think we had a really good chat. If there's anything else, we can always, you know, continue it on in the chat and Discord and Telegram. Lenny's typing one more thing, but I don't have anything further to add.

**DJSTRIKANOVA | Effect DAO**: Yeah, great call. Great call today.

**Rochelle T. | Effect AI**: great call today awesome to see so many OGs joining back in

**Jesse**: Yes, amazing. Thanks, guys.

**DJSTRIKANOVA | Effect DAO**: everyone have a good one and hyped to see the the v0 release in the next month. Or so.

**Jesse**: Yes, same here. Till next time. Till next time.&#x20;

