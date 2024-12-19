---
description: >-
  *Assembly AI generated transcripts may not be 100% accurate, listen to video
  for original audio.
---

# May 31st DAO Call

{% embed url="https://www.youtube.com/watch?v=QfwwkmQiHJY" %}

## DJSTRIKANOVA's General Summary

* Discussed creating an EFX AI fund to help subsidize tasks building AI related datasets. Such as helping LAION with their OCR project and doing labeling for bounding box tasks.
* AI Fund for open-source datasets, potentially can help with public recognition that Effect is an AI focused project.
* Discussed revamping how EFX is distributed to DAO smart contract. Rather than every cycle, have it be distributed every second. Get rid of the 30% of "unused fund" allocation, and replace it with a flat EFX distribution done through a proposal every cycle.
* Hackathon planned for August. Team is working on getting partners for the event, 2nd is secured, talking with a potential 3rd. Prize pool to be on the lower end, and be in stablecoins / FIAT.\


## Assembly AI Generated Transcript

{% embed url="https://www.assemblyai.com/playground/transcript/6spngkhypf-2d0f-4d16-ba71-72379e6198f5" %}

#### Jesse Eisses

On the docker for sure. Yeah, I guess it's just us. Are we expecting more people to jump in?

#### DJSTRIKANOVA

I don't know about expecting. I mean, maybe someone can jump in.

#### Jesse Eisses

All right. Do you have any agenda for this one? I haven't checked, but I don't know. Rochelle, do you see if we have any items no.

#### Rochelle

Pulling it up here? No, I still have old stuff on here. I got to move to the previous ones. But no, I don't see anything new.

#### Jesse Eisses

All right. I think it's better now we know we can speak and click on it instead of the other way around. I guess this will just be more of a regular update. We can chat a bit about the Dow and things coming up. I guess we don't have an agenda set. There's a lot brewing still and we're still waiting for the updates to come out. I think a few topics we can cover in this call, just from the top of my head, but we can do a development update, share the progress there and sort of the short term roadmap of what we want to release.

#### David Britt

Then we can also talk about the hackathon.

#### Jesse Eisses

Right. Another item would be Hackathon as well. We have some updates on the hackathon. I think we made quite some progress with planning and partnerships over the last few weeks. Mainly, Gabby has been in contact with some parties, so it's good to do an update there. I think it's just good to keep. If we're all in the loop of updates and even potential partnerships, it's just good to know. And then proposal wise, we don't have any proposals out there at the moment, but if there's any ideas for proposals, I think they would be great to just have a quick chat about as well. And yeah. If anyone else has other topics that we want to put sort of on our ad hoc agenda, then please share.

#### David Britt

Definitely a layon. And the label studio project, which is an AI tutor.

#### Jesse Eisses

Yeah, good one.

#### DJSTRIKANOVA

That Label Studio. It's a pretty interesting tool and could use. I was wondering if you could if it's possible to integrate it with Effect Force Online to check.

#### David Britt

Yeah, it is. I've been playing around with it a little bit. I've managed to get a simple prototype to render. The difficulty that I'm having at the moment still is inputting values into it and getting values out of it, but I can't get it render, so I think it should be relatively easily easy to incorporate it into the force, so I'm not too worried about that. But yeah, thanks for the hookup with LAION, and I do think this is important and I'm trying to look at it and try to get something out the door, a little prototype so that I can showcase it to Chris and hopefully get his feedback on it so we can start putting tasks on the force.

#### Jesse Eisses

Yeah, so LAION is like a connection from DJ and they want to do an annotation data set on Effect Force. And they want to start with like a trial using the label books. Maybe you can maybe give a high level overview of what their request is.

#### David Britt

Like the topic and the yeah, LAION is their whole mission is they're an open source data set provider, so they provide data that can be used to train AI models. They're trying to be a nonprofit organization that helps stimulate the open source development of all of these AI models. And they need help with data annotation at the moment for an up and coming model that they're working on, one of them being OCR, so just optical recognition of text. And they need humans to actually help them go through that process of annotating the data in order for them to be able to use it. And they want to use some tool called Label Studio that apparently is quite commonly used within the space to do these kinds of tasks.

#### Jesse Eisses

Nice. It will be really good if these types of companies, if we can work with them, like, they're all about open and democratic sort of data sets, which is also where we came from. And I'm excited to get these leads. They've mainly coming from DJ side, so thanks like a ton. I think it's amazing that you create these opportunities. So we'll definitely try everything to integrate and to perform well on this first demo data set.

#### DJSTRIKANOVA

Yeah.

#### David Britt

What are we trying to do?

#### Jesse Eisses

Yeah, because I think we can perform really well. We have quite a few workers. Like, a lot of them of the workforce we had before are sort of slumbering or they're taking a look every now and then, but we actually have like 2030 workers that are really on top of the platform still. And when tasks go on, they they deliver high quality work. So we really have that going. So if we kind of come up with high quality requesters as well, that really gives us the space to grow. Because currently main data sets are social media related. Sometimes we have a questionnaire, sometimes we have some other data, but if we have a consistent data set, especially around AI where data sets are often large and keep going and coming in, that can give a really good foundation for the platform to grow. So, yeah, there's still a potential we need to get do well on the test. We need to integrate with the label box, which on technical level, we've made that. We've made a lot of progress. So I will help you look a bit into the back end and how we can connect it, like make sure that the results come to the right place and that we get the right data in it. But it looks very doable, so yeah. Excited for this one.

#### DJSTRIKANOVA

Yeah. In regards to what you mentioned for proposals, I think this is something that we should, or rather, I would endorse kind of funding the creation of these data sets because LAION is like, there's little funding. A lot of it is just people provide their own time to do things. And so I think it can be a great way for us to get recognition if we show ourselves as contributing a lot to open source data.

#### Jesse Eisses

Yeah, absolutely.

#### David Britt

I like the idea EFX providing utility and actually creating value somewhere. And later on we can think about how moving our staging environment that will affect affect network. But during the meantime, we should invest in actually creating a product that is creating value somewhere.

#### DJSTRIKANOVA

And with Label Studio, I think it's clear that it's open source because people want to do it themselves, because they probably can't afford the big expense of putting it all on, say, Amazon, Turk or something like that. Right? Yeah, I wonder. It's something to look out for, I guess. I'll have to look myself, maybe. But yeah, Label Studio, I think integration with that and then also helping them build these data sets, I think can get us a lot of good news and kind of confirm that we're an AI project in the crypto space.

#### David Britt

Yeah, good point. Yeah. Maybe we should think about incorporating it a bit deeper into the force instead of having a layer on top of that is put then into the template engine where other people can actually use these existing tools already in order to build out their templates instead of this kind of being porked into it. But for now, I think this first prototype will just try to do it as quickly as possible to onboard these first couple of tasks.

#### Jesse Eisses

Yeah, I think for now this will work and the tool suits our platform well enough. We just need to substitute the feeding and the feeding of task and extracting of results. We need to make sure we connect it in the right way. But later on, I think for a lot of tasks, and that's looking at if things scale up a lot, I think we need more way, more convenient and specialized interfaces to interact with tasks like mobile apps for things. That you want to do on the go and like integrating the SDK inside of mobile box in the more native setup that could really improve things where you don't bring your interface to effect force but effect force goes inside your interface basically in the long run for long bigger projects that would be the way to go. But I think for now, we have so much flexibility with the template engine that we can make almost anything work. And the workforce is on there anyway. So I think this is kind of perfect for right now to work this way.

#### David Britt

Okay.

#### Jesse Eisses

All right, so that's LAION good potential requester. Let's hope it goes well and let's find more of these. It would be great if we can attract people to use Effect Force, that would be great. I helped a friend run some questionnaires also on Effect Force this week and at Westlay. The results were really good, was a lot of responses coming in. The quality was great. It happened like within hours. The people that the platform is working and people are happy with it. So I think we can really look for more use cases and like the Vita to have a real value, to bring real value to companies. That's where the opportunity is. Because when people really value the work, they will keep using it and it will keep growing. So that should definitely be what we focus on. Maybe we can go on to chat a little bit about proposals that we would like to see coming up, because DJ just mentioned that you would endorse something like this. And I think I agree. I was thinking I can volunteer for creating that proposal, but to create a little budget of EFX to subsidize tasks for, I don't know if we have to say specific requester like layon or just we say like want to reverse reserve this budget of subsidizing tasks for AI related projects. And we can give that basically as a way to ensure high worker payout because that's sort of mandatory for the quality side, but also to give to requesters a really cheap access on the short term for labeling their data. I think that's sort of necessary. So making a proposal for that, first of all, it puts a light on the topic. It frees up tokens for doing this, but it also makes it a topic of attention. So I do like the suggestion that DJ said. I don't know if that was exactly what you meant by it.

#### DJSTRIKANOVA

Yeah, creating a fund sounds good. Just like the bounty fund. You can just allocate some EFX for a fund to help. Also, quick question, is it LAION or LAION? How do you pronounce it?

#### David Britt

I assume there was LAION because L-A-I AI.

#### Jesse Eisses

Right, so AI.

#### David Britt

Yeah, good question. It's definitely one of those things. Sounds about right.

#### DJSTRIKANOVA

Okay, because that's what I assume too. Yeah, that would just make what you suggested just you would just make things faster. Because I agree, at some point, once your prototype is ready and you want to move on to having tens of thousands of tasks, I think well, he said in the chat he threw out a number like we need like 16 million at some point. So I think if we're self funding, there's probably a lot of tasks they need done. And as long as we can get recognition for it and gratitude, I think it could go on for a long time. So I think a fund for it would be great. And yeah, right now we're still I guess we'll be looking for it. But yeah, I think if we can help LAION first, then maybe other projects will be easier to find. As well. And we could help them. At the very least, I think it'll help us just show what effect network is all about. Because I know I still am salty about Coin Gecko getting rid of our label that we're not an AI associated project. This will only just underline it for everyone.

#### Jesse Eisses

Yeah, true. Yeah, I like that. And also for the funds, maybe we could even label this as we have our Deaf fund. Right, maybe you can touch on the Deaf fund in a little bit because I would like to discuss that a little bit as well. But if we have like our we could even call it the AI fund and we give it like a purpose to fund the development of open AI data sets. And we give some specification requirements for projects that can use it. Maybe we can source some funds to that over the coming cycles or start small and then see how it goes. But we could sort of create a page for that and we could say there's this much available for projects that want to source high quality data sets. And we can send a message to LAION, we can send a message to Hive Bright to the project. What's it called?

#### David Britt

Hive Mapper.

#### Jesse Eisses

Hive Mapper, sorry, I tried this another project on Hive Mapper to tell and look, this is available for creation of data sets and they might want to tap into that for some trials or for some other reasons. We can maybe market this in several communities. Like there's a lot of happening around LLMs and Loras and people that are sort of sourcing that require data sets to fine tune their loras are like small fine tunings of models. There's a whole community around it. So perhaps that can bring some attention to our platform for sourcing data. If we make that more like a general pool, I think that they provide.

#### DJSTRIKANOVA

Recognition for helping them build a data set. I think it's worth paying for ourselves.

#### David Britt

Yeah, indeed.

#### Jesse Eisses

We could call it AI pool now. AI we have the developer pool that we call it Fund. AI fund. AI fund, yeah, I like that.

#### David Britt

Something in that direction. Indeed. That's something that we've identified as a problem that just there aren't enough tasks being put on the platform. And if we can have a steady stream of tasks and we can pay for it for the coming short to midterm, that should really help drive attention to us in one form or another. And hopefully that can lead to something much more fruitful where we can get requesters.

#### Jesse Eisses

Yeah, and the AI fund can really put the spotlight a bit back on the AI like on the AI origin and the AI essence that we have as a project because that's indeed being overlooked and we need to make sure we can restore the kernel, the core of the project, so this can really help there. And also of course more tasks is always should be the top agenda. I've been taking a close look lately on the collected fees in the platform, you can see it, and in the new dashboard, it will be more visualized, so you can see how many fees have been collected, which are 10% of tasks paid during a cycle. And we have this baseline of fees being collected and it's going up slowly, but it keeps getting more and more. So it's nothing to get really excited about yet, but it is like, growing. And every time we get something on board that does a few tasks, you can see the collected fees going up. And it's kind of motivating to see because if we keep up growth, and I can really see how one or two bigger requesters that are bigger, like even medium sized or trials that we do, they really boost that number. And I think putting that number on the front page and making sure we pay attention to it, and we show the track from setting up a template, posting tasks, creating a data set, if a few people get the hang of it, it really illustrates how this product functions. I think we've started a lot with showing and telling and understanding how it works, but it's becoming more and more clear now. So when we talk with people and when we show projects how it works, especially in the web three space, this can, I think, really make the difference to get that number out there. And it's also motivating, of course, for the dial, because I think we can really, if we scale up tasks, we will soon get to a point where task rewards can be close to maybe half of what we're currently from rewards we're getting from recycles. At the moment, we recycle nearly the maximum amount we can recycle most of the time. What is it, like 30% or something of the leftovers that go back to the fees? Sort of. We're maximizing that amount in most cycles. I think we can get to that number at some point soon. If we scale up tasks, we can get to that number just with general task rewards, and that's sort of a main goal. Of course, if we get there, we can really start thinking about scaling down at 30% and making task rewards just if it scales up. And once that start rolling, if you get a little bit of taste for it, it's quite easy to imagine that getting larger. It would be amazing if we can make that like the substantial amount of EFX and not needing that 30% anymore. But anyways, there was just a little terring of thought on getting more tax on there and sort of seeing a little positive side in even though things have been low, we have that consistency and there are fees coming in, so it's just a matter of scaling it up.

#### David Britt

Yeah, basically.

#### Jesse Eisses

So one proposal. All right, I think we can share a draft pretty soon, like today, tomorrow about setting up this AI fund. Technically, I think we should just make it similar to the Deaf fund is that we share the keys between few key people in the Dow and clearly state the intention of that pool. And I think then if anyone has concerns or is against it, we don't have many people here. Ace and home, if you want to speak, feel free to raise the hand or Rachel, what are your thoughts, Rachel, on this idea?

#### Rochelle

I'm all for it. That's exactly what we need. And I like how you touched on before that we should have Effect Network be like, able to be embedded within other people's projects. They don't have to specifically use us. They can make us part of their whole system. Like, internally. That's just the best way, I think, for us.

#### @ce

Hi, guys. I really appreciate what you said the last 15 minutes on my agenda. I personally have two keynotes for a couple of weeks now. And there's the Human Judgments Data and Crafted Examples data, which is human feedback on AI behavior, which is exactly what you said. A database for the promising AI tools in the future. So I'm really looking forward if X, formerly known as Effect AI, is capable of bringing some data to the AI masses. And yeah, I really appreciate and I'm really 100% pro this constitution of this line of going.

#### David Britt

Yeah, we should think about like, how do community outreach. I think it could be a good marketing point as well and try to.

#### Jesse Eisses

Get the word out there.

#### DJSTRIKANOVA

Sorry, Dave.

#### Jesse Eisses

Yeah, that's a good point.

#### David Britt

If we can impress LAION, I think we can impress a lot of other people as well.

#### DJSTRIKANOVA

That's real big. Or rather, they are recognized, like the people know of them in the AI space, actually. In fact, when I was doing my NFT project, the other model I used is a Layon model instead of OpenAI it's a Layon image recognition model. They're pretty big. So if we can be recognized as helping them build out models and stuff like that, I think that will be a big deal.

#### Jesse Eisses

Yeah, that's cool. Yeah. No, definitely. I know them as well.

#### David Britt

I know them.

#### Jesse Eisses

Their name is it's quite well known. I'm, of course, also in the space, but it's a pretty prestigious and good company to work with. Nice. All right. I like that one. That's a great one.

#### DJSTRIKANOVA

Budget wise, I think we'll have to see how much budget it will take because I think throwing numbers off top of my head, I don't think people will mind 100,000 EFX every cycle. But if, for example, we need much more than that and we may need it to for example, I think the initial set he wanted was like, I.

#### David Britt

Need to check it like being 1500 for the first for the first go.

#### DJSTRIKANOVA

Yeah.

#### David Britt

And if it goes well, he said thousand yeah, 100,000.

#### DJSTRIKANOVA

Well, 1500 is no problem at all. 100,000, let's say it takes like five repetitions. Is that good for one?

#### Jesse Eisses

Yeah, this is a tricky part, we need to engineer it and test it out. But I feel more like, I feel you get more value at doing low repetitions, but making sure people are well trained and supervised than doing a lot of repetitions because Rochelle is the professional in this thing. But I think especially if it's more of a precision task where it won't be extremely easy to compare results or something, I feel training and training and supervising and doing maybe two repetitions is sort of the optimum, budget wise way to do it. It really depends on the test of engineering and Rochelle's input after she's seen the task. I don't think she's seen them yet, but if she takes a look but anyways, for the budget, it's important, we need to figure out if you go for five repetitions, these numbers go up quite quickly on how much it costs.

#### DJSTRIKANOVA

Yeah, I don't know how the task itself will cost either. I'm just ballparking one EFX for simplicity. But if it's like half a million for the 100,000 set, I think that's totally doable. Though. The problem is once we get past half a million, because the way the treasury works, any EFX we introduce is basically inflationary, right? I guess because we limit ourselves to 300 per cycle anyway. I think as long as we keep it to that limit, it's not a big deal. Hopefully the 100,000 set is good enough to get us traction so we can go towards working on the 16 million, but we wouldn't be able to do the 16 million right away, if you get what I'm saying.

#### David Britt

Yeah, absolutely, indeed. I don't think we've ever dealt with these kinds of scales before and like having to deal with the economics of dealing with such a scale. And so, yeah, it'll be interesting, like we'll probably have to think about other solutions, probably being much more strict about task validation instead of using repetitions in order to clear out people who are trying to spam the tasks. But yeah, it'll be an interesting problem and when we get to that point.

#### Jesse Eisses

But 100,000 tasks we can do, like, we've done that scale and we know sort of there's complications, but we can handle that. And doing millions of tasks does mean we would need and also depends if we had a speed on that 100,000, but if we might need really good coordination between workers to have that on a higher scale. But yeah, I think not too worried about achieving those results. I think we can do it.

#### Rochelle

Yeah, I think we can do it. How I would approach it would be like multi tiered. So first I would need to have a smaller sample of the data set just to look, to see what it is, the results we're wanting, figure out the best way to design the tasks just for the beginning. And then it would take a little bit of time looking at the initial results to identify some higher level quality workers. Because you could start out in the beginning with some repetitions, but then once you identify workers who are really uniquely skilled for it, then your repetitions can go down and it's just constantly watching the workforce to identify the better workers for it and then giving more tasks towards them. Still having a pool open for the entry workers, but your repetitions can go down and you can get more precise. So it's not just about repetitions for validation. I mean, if you had unlimited budget, you could set three reps to one task and then just only take what there's a consensus for. But even then you still have to monitor it a little bit, but if you kind of roll it out in different tiers and stuff, that's what goes into managing a custom workforce and that is where you can really stretch your funds. So little prep work, but we can definitely do it quickly.

#### DJSTRIKANOVA

Yeah, that's what that guy was talking about. I think he wanted that initial set pretty soon. Yeah, I think I'm just kind of repeating myself. Hopefully we can make that guy happy with LAION.

#### Rochelle

Oh, we definitely can. We definitely can.

#### DJSTRIKANOVA

And I think in the next quarter or two, we'll need to see if we want to renew the liquidity pool bonus. So yeah, we'll see how things are going because that's in November when the year ends, so we'll see how things are going budget wise. But yeah, I think the AI budget is important for just public recognition of our project and what it's doing.

#### Rochelle

We couldn't hear.

#### DJSTRIKANOVA

Do you hear me?

#### Rochelle

Yes, now I do. What just happened? Okay, I'm good. I'm not lost anymore. It just got super quiet all of a sudden.

#### DJSTRIKANOVA

Yeah, same here. What about you, David and Jesse?

#### Rochelle

I wonder if they're having audio problems. They'll pop back up there.

#### Jesse Eisses

Yeah.

#### David Britt

How about now?

#### DJSTRIKANOVA

Yeah, we hear you.

#### David Britt

Okay, great. Yeah, indeed. We've been having issues as well.

#### Jesse Eisses

Just like you, we couldn't hear anyone and then we couldn't hear Rochelle speaking, and then we were talking loads, but.

#### David Britt

No one could hear us.

#### Jesse Eisses

Feel stupid now. Good. Are we back? I can hear you guys. You can hear us?

#### DJSTRIKANOVA

Yeah.

#### Jesse Eisses

All right.

#### David Britt

I guess if there aren't any other proposals in mind that we can talk about, one interesting one would be then the hackathon update.

#### Jesse Eisses

I had one other proposal that I wanted to discuss maybe quickly. We covered it in the last one. I would like to switch from to propose to switch from cycle budgets to like having every second some e fix being sent to the Dow. If this will make it easier, like I said before, to make it easier to do the cycle changes. But also I think it just makes more sense, it will give a more clear picture of how much EFX is being released and it will enable us to do some other cool things later on. But it will basically mean that from the treasury we will have every second a little bit of EFX streaming to the Dow account that we can use. And there's basically two complications. One is that we need to figure out a new way to send the 30% to the Dow fee pool. There's a few ideas for that and the second complication is that we will no longer have any unused funding to send back to the treasury. It's a sort of simple change. We actually remove some of this cycle budget logic from the smart contract and we add a little I've already worked on this to add a little token streaming smart contract that just streams certain amount of tokens per second to the Dow. And yeah, for the second point that we no longer recycle things back to the treasury. I think the best way to sort of deal with it is and I think it makes more sense and it's more clean and beautiful to do it this way when we just burn a certain amount of tokens every now and then when we feel there's a lot in the budget. We once had a proposal to burn certain amount of tokens but if there's like if the Dow has a lot of tokens in circulation and we have so much in the wallet, there's not much happening. Having someone propose to burn a certain amount would basically achieve the same or instead of burning we could decide to send them back to the treasury, meaning out of circulation, which almost is like burning but they could be reused later and then for sending it to the people. That's a discussion worth having as well. How do we keep adding tokens to the people? We can definitely just mimic what we're doing now by sending an amount to the people every cycle in a transaction that constitutes to the amount we would expect now but we will be way more flexible in choosing different schemes later on.

#### DJSTRIKANOVA

Okay, yeah, that's what I was thinking. Strictly speaking, couldn't you do the 30%? Could be done actually no. Yeah, I was thinking just the constant amount and we could judge based on just be like an ATP that sends it to the people.

#### Jesse Eisses

Yeah, we cannot just have an ATP sending it to the fee pool every cycle. Like we have this process, like when a new cycle starts we can just transfer an amount, we can even do a fixed amount which I think is simpler and nicer. Maybe just to send a fixed amount isn't alternative. Like there's a few alternatives to how to send them instead of the 30%, which I feel is a slightly awkward measure.

#### DJSTRIKANOVA

Well, yeah, the 30% I think wasn't it the first proposal?

#### Jesse Eisses

It was the very first one.

#### DJSTRIKANOVA

So yeah. It's definitely kind of old. I think people do want to be compensated for the work they put in evaluating proposals. So definitely, I think, as you said, eventually we may get to a point where we don't need in some ways it's like a subsidy to encourage the work done and the valuing proposals that won't be necessary once we have more fees coming in. So yeah, I think with this method we can eventually judge ourselves to the point where we're thinking we don't even need to do this.

#### David Britt

Yeah, but I'm guessing this is also part of the push to help with the automation of the cycle cycles, that it requires less manual actions in order to get every cycle started again.

#### Jesse Eisses

Yeah, there's more reasons to it, but one of them is that yeah, having that budget come up every two weeks is slightly yeah, it's a manual thing that has to happen. That has been happening for two years now. Over two years. And it's just not pretty. It doesn't really fit. It doesn't feel right. Having token stream every second means that we don't have to wait. The Dow should just have its wallet that it can spend and it should be able to work with it. I think that emptying it completely again every cycle and then waiting for a new cycle to come in again, it just feels like and there's so much the mental model of understanding what's happening is just more complicated when you just come in. Even I sometimes wrapping my head around it. After doing this for over two years, I think we need a way more clean model and just seeing every second some tokens chipping into the Dow's wallet. That's the wallet of the Dow. That's what we can use in proposals to spend. It should be related to every two weeks. The two weeks is to have the proposals and to give us time to vote. So I think that should stay. But this funding coming free every two weeks, I feel it makes way more sense to just see that wallet there, we have this much left, make decisions based on that and it just goes up every second as it's basically slowly coming into circulation. It will also help with fixing our total supply on token sites like going Gecko and coin market cap as we can have that fixed release rate.

#### David Britt

How will it affect funding available for the proposals?

#### Jesse Eisses

Well, there will be situations where there's way more funding available than 326,000 EFX. Because if we don't spend anything for two cycles and we don't put any proposals out there to burn or to burn any tokens, then basically the funding will add up.

#### David Britt

Okay.

#### DJSTRIKANOVA

Like for example, this cycle we had no proposals, but we would accumulate how much was it? 300,000 EFX?

#### Jesse Eisses

Yeah. 26,000 would have been accumulated this cycle as funding for the Dow. I do suggest, because it will add up now that we lower the release rate. So we don't say that a full seiko adds up to 326,000. Because I think we have some graphs on like initially we would have 15 years I think of I may be saying this wrong, I need to look at the graphs again. But we had some graphs predicting how long we can last with the tokens at this release rate per cycle. We could lower that as right now tokens will stack up and we only recycle by an ATP if necessary. So I think we should lower it. What do you think? If we would like lower it to say to two thirds of the current rate or something?

#### DJSTRIKANOVA

I don't know if it really matters if it's lowered or not because we can just change it anytime, right?

#### Jesse Eisses

Yeah, that's true.

#### DJSTRIKANOVA

So it's not like it's contractually set. Honestly. I just prefer like maybe a flat number instead of trying to number specifically 326, just make it 300,000 flat.

#### Jesse Eisses

Yeah. And this will be a number not per second but we can calculate that.

#### DJSTRIKANOVA

I estimate 300,000 per two weeks cycle. So whatever that is in the seconds.

#### David Britt

Sure.

#### Jesse Eisses

Yeah.

#### David Britt

Is there a specific reason why it should be 300,000.

#### DJSTRIKANOVA

Only? Because it's just what we've been using this whole time. We may have like big projects in the future where we need to allocate a big amount of EFX. For example, we have that liquidity pool stuff which is worth like one point something million. How much was it?

#### Jesse Eisses

Yeah.

#### DJSTRIKANOVA

And I don't know. There will probably be debate if we want to do another year of it. But basically the way I see it is the Dow is not very spend 50 from what I experience. So I'm not too worried if a lot of EFX is accumulated into the Dow account. For me, I think we only will spend it if we think it's valuable to spend it. So I guess I don't see a reason to kind of limit it because I believe the Dow is responsible enough not to be frivolous with it.

#### Jesse Eisses

I agree.

#### David Britt

I also like the idea of trying to burn the excessive tokens. I do think that there might be a good strategy for now until we decide maybe like we should consider something else.

#### Jesse Eisses

Yeah, I think it's way more clear. The burning DJ proposed it a while back, like a long time ago. Burning makes more like what we're doing with sending tokens back to treasury, taking them out of circulation just in the web three space in the crypto world to take tokens out of circulation, you burn them. That's the mechanic to do that. I don't see why we wouldn't use that. And it makes people better, understand it better. It is the purpose of take. If we feel like there's too much liquid tokens in there to burn them it feels just a nice it just makes sense. That's why you do it. So it's the right mechanic, like the right tool for the job. But anyways, this won't be like, I don't want to make it too radical of a proposal. So I will try to keep things sort of the same in this proposal, except for tokens being released gradually and no longer sending them back automatically to the cycle. And then from there we can take it step by step and this will just be a proposal. So if there's people wanting to have more discussions about it, then we can always take a bit longer for it or not even change. Right. It's a proposal, it's what it's for. So I just wanted to throw it out there and I'll write up my thoughts and I think that we'll get it rolling.

#### DJSTRIKANOVA

Yeah. The only thing that people should be aware of that will change is that we'll have to explicitly pay ourselves for the work we do, evaluating proposals. Yeah, but it was originally done explicitly with the first proposal. Right. So I think it's just clear and it makes it easy to change in the future once ideally there's more throughput on the network.

#### Jesse Eisses

Yeah. Another thing we could implement, which on one side, I don't like it because it might sound complicated, but if we would say the minimum fee every cycle to guardians is 120,000 EFX. I'm just saying something. We just ensure that it's the minimum, but then we look at how much came in from tasks because now we have that visualized, we know what's coming in, so we sort of subtract what came in from tasks and then whatever is missing gets added to the people. Yeah, I was thinking about that model for a bit because I think it makes sense as we just put it on a minimum. But I'm confident that at some point soon we already like, these tasks will start what we get from tasks will start growing. So it just means that that amount will go less and less and disappear, because when the tasks weigh more than 120,000 a cycle, we don't need to subsidize that minimum guardian distribution anymore for performing our duties to vote and consider and be here.

#### David Britt

Right?

#### DJSTRIKANOVA

Yeah, I think that sounds good though. Maybe tedious, unless you can automate that.

#### Jesse Eisses

Yeah, that means we need to write a script to do that. But it's the same Tedious as it's Tedious now, so in that sense, and it might be a nicer step to.

#### David Britt

The right direction yeah, in some sense indeed. Like it's already tedious, like we are kind of already you're already taking meeting notes, Alex. So in that sense, we do kind of have a process and we can rely on that process in order to look back on it and see okay, who have been fulfilling their duties, who haven't, and then based off of that data, we can decide, okay, maybe for example, this guardian shouldn't be allowed anymore. But yeah, I do think that's an interesting idea, but I do think it also requires more consideration as well. But yeah, I do like the idea in the sense of it does stimulate you to take your tasks as high guard more seriously.

#### Jesse Eisses

Do you guys think I should put this out in a proposal for this cycle and we can read on it and push it forward? Or would it be better to just share like a written text in discord so we can have one more cycle to consider and then post a proposal whether you feel is the best process.

#### DJSTRIKANOVA

Well, when will you be working on it?

#### Jesse Eisses

Like the implementation wise? That would be if I would write a proposal tomorrow, it would be in the next cycle and then by the end of that cycle this would be published.

#### DJSTRIKANOVA

I think you should go ahead and do it. As long as we don't really change functionally. How much is distributed every cycle? Too much, I don't think people have an issue with it.

#### David Britt

Yeah, I'm feeling more for waiting one cycle, but I also like the idea of being a bit more, having a bit more velocity and pivoting a bit more and like trying something new instead of waiting one more cycle in order to implement something. And this could get ball rolling. Let's go for it.

#### Jesse Eisses

All right, I'll light it up and if I feel confident tomorrow, then I'll publish it in the cycle. I think to push it sometimes it's good because when we're coming out with the dashboard update, it's nice if this is embedded there and we can already know with a bit certainty that it's going to work in that way.

#### Rochelle

Yeah, I'd like that to be live before the dashboard update. That way we show it constantly coming in. We don't have to mess with the dashboard again.

#### Jesse Eisses

Because it's going to be a new feeling for people when they use the new dashboard. If this mechanic is in there, then it will just feel less like it will just feel it. The dashboard has been there for so long, if you change it now and it's going to be a bit different, it's nice if the new mechanic is there. So it's actually part of that new experience, David, to understand the new mechanic, the time. Yeah, well, yeah, I think this can be done.

#### DJSTRIKANOVA

No, I mean, like right now, because I remember you want to talk about the hackathon, but it's eleven, hopefully.

#### Jesse Eisses

Yeah, the time flew by, we don't have time. Maybe we have to keep it really quick, the hackathon update and then we have to jump off.

#### David Britt

Yeah, indeed. We can just keep it brief then so quickly about the hackathon. We have a third partner that also wants to join us. The second partner that will be joining us will be made a launch. They will be evaluating the business cases of the hackathon proposals as well and they will also be contributing to the price pool for the hackathon. But yeah, we're excited to announce the third participant soon.

#### Jesse Eisses

It's not yet solid enough to discuss.

#### David Britt

No, not yet. There's still some details that need to be fleshed out and we're aiming to do this hackathon then at the beginning of August. Okay, but yeah, those are the major updates and we still need to do some work then on the SDK. Jesse has implemented a couple of new features for the smart contract in order to optimize the whole reservation flow and that needs to be reflected back into the SDK. Some of the documentation needs to be rewritten and then I think we'll be ready for the hackathon.

#### DJSTRIKANOVA

Sounds great.

#### David Britt

Yeah. So we'll be doing it on Dora hacks but yeah, indeed we still need to finalize how much the price pool will be this time around as well. We're not sure yet how big that's going to be.

#### Jesse Eisses

Yeah, the price pool is one. We want to give an indication of that soon. And if we have that on paper, we will share that document with everyone in the Dow. So we can make this more of a collaborative part. But we're hoping the two parts can contribute a part to the price pool. And, yeah, we need to set to make the price pool. Right. What's the goal of the hackathon? What do we want to achieve? Looking ahead, if we're going to make this a recurring hackathon we need to make it sustainable. So we need to make sure participants are there, the prices are high enough that they're really motivated to work hard and to make cool products. We also need to make sure it's sustainable for later on and that the price pool is comfortable for partners to join in as well. So yeah, we're thinking about a price pool of like significantly less than the last one because the last one I think was really big. Maybe we got a lot out of it. Right. It's hard to really know what would have happened with smaller price pools but if we're going to do a few a year, I think that's not sustainable to have a price pool like we had last time. So it would probably be a few thousand dollars each that we put in. Maybe the exact number we don't know yet but we're just talking with the partners and seeing what are they going to put in. I'm really feeling strongly to not put in any EFX tokens to make it just pure fiat based or like stable coin based because the last time the EFX tokens it didn't really work as a motivator for participants to put on tasks. It actually was quite the tokens were sold out quite quickly. I feel like participants were just looking for USDC and they weren't too interested in the token which in the end then that's good for no one if it doesn't end up being used for something like that. So we have a few bullse points still on the table but that's just sort of the work in progress part. Once it finalizes and we know more about that third partner or the second partner, then we'll share the document with everyone.

#### DJSTRIKANOVA

Yeah, sounds good. Yeah, we'll see how much I guess the closer we'll get, the more we'll figure out the price pool. It's to be expected that some EFX will be sold by the winners. So we don't want to make it too much. Otherwise it will be like a very for the Dows, particularly all EFX we allocate from the treasury is inflationary. So we don't want to make it too much. But we can still do some a little bit to it because it's kind of like government spending. You can print a little bit of money to build roads, infrastructure, that stuff is really useful and there's a benefit to it. But you don't want to just give everyone money that just makes everything more expensive and lowers your value.

#### Jesse Eisses

Yeah. And last time I want the effects to be sort of like if we give people effects that they at least value some of the utility of it instead of if they just want USDC and not a FX, they will just sell it for USDC and then it doesn't make sense to give them utility if that's there. But maybe we can think of a way where we really make I think what would be great if we can give them a budget to spend on the platform to do tasks we can give them a budget for and that would be a great case. I would love to give them, say, a bunch of EFX that they can do quite a large data set freely on the platform because they have that on there. Right. They can extract value for the Dow. It makes sense because it's in the ecosystem and it's being utilized. The token is being utilized for what it's made for. So that would be great. So maybe we can think of a way where it's EFX. Like they get to use DC prize money. It's in their wallet and apparently looking at last time, that's what everyone was looking for. But then the EFX is really to utilize the platform more. I think that would make sense. So maybe there's a way to do it, I just haven't really found it yet.

#### David Britt

Yeah, if we actually controlled EFX, it would be easy to use some kind of credit system. But indeed, if we just give them virtual EFX, they could still very easily just pull it out.

#### Jesse Eisses

But we could make sort of a proxy contract where they have that fee effects, but it can only be used for publishing batches. Like on a smart contract that's sort of not too hard to accomplish. Maybe that's worth setting up. We could give even for stuff like an AI fund or something, we could have funds that are only available for publishing batches. That's sort of cool. I'm going to write this down, maybe that's going to work.

#### David Britt

So part of the price pool would be USDC and then EFX that can be used on create campaigns and create batches. Yeah, cool.

#### Jesse Eisses

Yeah, that works, right? Literally. It just came to mind now that we could actually make that maybe like to give people platform allowance, which means they get an EFX allocation that can only be used for publishing batches.

#### David Britt

Yeah, absolutely.

#### Jesse Eisses

We do have to run. Yeah, it's almost ten plus.

#### DJSTRIKANOVA

Yeah. The only other thing I could offer is if the Dow wanted to fundraise as well. I wonder if through ATP a small amount can be used to exchange for EOS every cycle. Like something not big enough to make an impact, but slowly, like every cycle it will accumulate a fund.

#### David Britt

Yeah, I like that. Or even us a stable coin.

#### Jesse Eisses

Yeah, us. Yeah.

#### David Britt

I'm all for having the Dow hold stablecoin instead of only EFX, we could.

#### Jesse Eisses

Do this with an ATP, right. Someone would have to provide that liquidity. So someone would basically create an ATP and buy a certain amount. Or we could actually do it.

#### DJSTRIKANOVA

Because we execute it at an arbitrary time. Right? The ATP.

#### Jesse Eisses

Yeah.

#### DJSTRIKANOVA

So we don't have to worry about being front run. So if we just set like exchange X amount of EFX for a small amount, say 250 EOS every cycle, that will be enough that it won't significantly impact anything too much, but also help build up an EOS and then later on we can do the same for the EOS to USDT which has millions like in liquidity. So I don't think we can even be front run there. So that would be like the suggestion.

#### Jesse Eisses

It's only that D five box isn't open source so I wouldn't even know how to interact with their contract. I will ask them, I'm in a group with them. I'll just ask if that's something we can do. But not being open source with uniswap or something, I know we could do it with D five box. I'm just not sure how that would work. So I will ask them in telegram.

#### DJSTRIKANOVA

I think it's possible. It's just like you have to put it in the notes, I mean, in the memo.

#### David Britt

Also think it's just a transaction that.

#### Jesse Eisses

You have to make. Do they send tokens? That's it. You cannot give limits or you cannot give slippage or anything.

#### David Britt

Not sure about the details, but I'll take a look. I feel more for like setting up a proposal that sets up a budget. I'm saying that we want, for example, $5,000 in stable coins or EOS and then try to build that up slowly then over the coming periods instead of doing that indefinitely for the coming cycles.

#### Jesse Eisses

I feel a lot for having ATPs where individuals basically provide liquidity in the form of EOS, buying up tokens and you take a risk because you have to cycle there. So you take some risk on basically the price level. So you need to get like, a better price than market price just to comfort the risk. I think that can be a nice economic model there.

#### David Britt

It would be like a futures.

#### Jesse Eisses

Yeah, there's some like it's a little DeFi risk involved. So you would be able to make and then now can judge if it's worth it or not. Maybe it's not. We do have to run. I'm sorry, but we have to go.

#### DJSTRIKANOVA

This next dow call because it's just an idea I had to accumulate other coins that we can use for price pools.

#### Jesse Eisses

Yeah, it's a great idea. I like it. I would love to talk more about this topic. Definitely. We put it on the agenda for the next one. I got some ideas about it, but we're running out of time and let's pick it up next step.

#### DJSTRIKANOVA

Bye, David. Bye, Jesse.

#### Jesse Eisses

Hey, thanks. Yeah. Thank you very much, everybody. Bye bye.

#### DJSTRIKANOVA

All right, so I think we covered everything. So I'm going to end the video.
