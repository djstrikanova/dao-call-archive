---
description: >-
  *Assembly AI generated transcripts may not be 100% accurate, listen to video
  for original audio.
---

# June 28th 2023 DAO Call

{% embed url="https://www.youtube.com/watch?v=m3S-sXjVnMM" %}

## Short Summary by DJSTRIKANOVA

* Discussed failed proposal and better ways to incentivize BSC worker migration to EOS.
* Discussed new Dashboard UI, Demo available https://shark-app-rb82w.ondigitalocean.app/
* Jesse talked about his upcoming Space with Ocean Protocol discussing datasets. Jesse has a lot of interest in integrating Effect Network dataset generation with Ocean Protocol, as it would be a very good synergy.
* Discussion about the topics for the Hackathon, going to be a focus on generating and building datasets.
* Rochelle's update on LAION OCR dataset generation, making good progress. Goal is for process to scale to potentially hundred of thousand tasks down the line.
* Jesse/David discuss ongoing AI trends and how Effect Network can fill a niche with dataset generation
* Building an atomicswap bridge would be too much a complex distraction, discussion over helping incentivize workers to migrate to EOS. For example, allow workers to use their earned EFX to create an EOS wallet for them. For now people have to deal with pTokens bridge fee.
* Last day to donate to DJSTRIKANOVA's Pomelo Grant https://pomelo.io/grants/nftindexer

## Assembly AI Generated Transcript

{% embed url="https://www.assemblyai.com/playground/transcript/6xmsvhj2d8-3c91-46f2-a79e-8a0c7970f2a1" %}

#### Jesse Eisses

Perfect. I do not think we have like a packed agenda, but if anyone can see if there's items that are listed for us to discuss, that would be good. How does the agenda work? They pop in here when people fill.

#### David Britt

In the form or.

#### Jesse Eisses

It'S empty, right?

#### David Britt

Yeah, we don't have any agenda today. We do have the proposals that we.

#### Jesse Eisses

Can talk about.

#### David Britt

Specifically the BSE transaction fee adjustment. That one didn't result well. It didn't pass.

#### Jesse Eisses

I think it was a good proposal. It attends to a topic that's important. We discussed it in the last alcohol a little bit and I think we came up with a few possible improvements to do. So I guess that's why it didn't pass. Like there's there's a few things like the fee is there's a few things that could be done better? But I do think it was a good trial just to see how people feel about it. But I think an iteration of it would be needed for it to pass.

#### David Britt

And I also thought your comment Alex, was on point as well.

#### DJSTRIKANOVA

Yeah, that's the primary reason I voted no. I believe it's a good idea to create fees that incentivize migration to EOS over time because currently the way things work, I've noticed that workers using EOS occasionally you notice the workers having problems and usually it's like not having enough Ram. Right. And we give them some support, but they have to pay for the ceram themselves and it cuts into their wages basically from doing the tests. In some ways it will be helpful that the full cost is factored into the buy net smart chain wallet users as well.

#### Jesse Eisses

Yeah, I agree. I think last time we discussed a possible solution where there's going to be an additional fee on the payout that's incurred to the worker side. I think that would work better to reach the same goal that's described here. So I think something will be possible there if we work out a little bit better. But I agree with DJ that it shouldn't be on the side of the requester right now.

#### David Britt

Yeah, specifically as well. Indeed, the amount that I stated was maybe a bit too much as well.

#### Jesse Eisses

It will be configurable, I guess all these amounts, even the fees, they can be adjusted with ATP, so this would also be a configurable amount, but for the initial value we would have to I think it's better to start a bit lower to make sure it's aligned with the network goals and functions.

#### David Britt

Yeah, agreed. But it was also nice to see that people actually voting no. There was a while everybody was just voting yes all of the time and I was worried that people were just kind of not even reading the proposals properly and just voting yes in order to kind of mine EFX or just claim the fees same way.

#### Jesse Eisses

I was kind of happy to see people who are critical because we have like every proposal passed in the last few months. I think that's a nice change of color.

#### David Britt

Okay.

#### DJSTRIKANOVA

It also shows how the comma feature is actually pretty useful because I can explain why I voted no.

#### Jesse Eisses

Yeah, it is. And I like how I think MCBAH made this that it renders above the list, which is nice, so you don't have to click on anything and it's like it's really clear. It helps a lot with considering the implications as we all right, nice. We're actually right now, David and me are using a new version of the dashboard. We've been slowly, like, polishing and adding features and making it nicer. So maybe this link has already been shared before. Maybe we can just share it in this call because we're kind of happy with it now. This is just a sort of alternative version of the current dashboard with different layout, bit of a different navigation is important because I ended up missing the call a few times and just I mean, we've been doing this for a long time, but it's nice to have like at the top of the page. Just clearly state at what time does it start and how do you add an item to the agenda. I think it will give people an easier entrance to see more inviting to them to join this call. It's minor updates, but it's nice to share. So if you're looking at a dashboard, you can use this alternative link. I think this is ready to be Merck, so I think we'll just go for it pretty soon.

#### David Britt

If anybody has any comments or suggestions, we're also open to hearing about them and incorporating them. We've also added the ability to add an NFD as your profile picture.

#### Jesse Eisses

Yeah, so if you go to the members page, then you will see like the High Guard members and also other members. But the High Guard, some of them have an NFD profile picture. So it gives just a little you can see you can use, for example, your Pomelo avatar there.

#### DJSTRIKANOVA

I see that's nifty. I see you moved the socials page to the resources.

#### Jesse Eisses

Yeah, we've been revamping the menu a little bit. The main problem was that it was just too many buttons there and we felt like it was nicer there. If you look at the page layout, it's totally open for like of course it's open source and it's open for feedback. I know the resources were added by merch because later but we wanted to have last steps. Actually we're still considering to sort of merge maybe staking and members because in the top of members you have your vote power. So at least I would be in favor of merging that somehow to have less pages. I want people that come in to don't give them too many things to click, but just make sure it's very condensed into what's important. But we're completely open for feedback. Emerging that socials and resources, I think makes sense. We can discuss what should be on top as well.

#### DJSTRIKANOVA

The only thing just coming spontaneously is it's a very minor thing, but maybe the boxes need their headers to be folded so they're a bit more prominent.

#### Jesse Eisses

All right, I agree. On the resources page, right? Token map stats resources. Yeah, absolutely.

#### DJSTRIKANOVA

And maybe like on the website you have the totals right for.

#### David Britt

The distribution of EFX.

#### DJSTRIKANOVA

Yeah. There's circulating and not circulating.

#### David Britt

That would also make sense to put it here.

#### DJSTRIKANOVA

Yeah, I'll play around with the NFT stuff later today.

#### David Britt

One other idea that was thrown around was to incorporate your calculator, DJ.

#### Jesse Eisses

It's not resources, isn't it? Or it's not in resources.

#### DJSTRIKANOVA

Oh, did you do that or is that just an idea?

#### David Britt

Yeah, it's an idea that we had that it would be useful to actually incorporate it into the dashboard itself instead of having it be update somewhere else.

#### DJSTRIKANOVA

Yeah, you could integrate it. The only thing is I haven't updated it in a while. It still needs one last update and that I made it before the fee pool was actually like that. We had the fee sent to the fee pool, so I didn't have that set up to calculate that. So we'll need a little bit of update. So I think it's really like anish thing.

#### Jesse Eisses

Okay. I think at the very least we put it in the resources. But it would be nice if we can have it on the Staking page somehow embedded. But we were linked to it because it's very useful and nice to highlight and incorporate maybe in the code base itself, if that someone suggested this, I think was on GitHub. Oh, we got it. Yeah. So that's the Dow refresh of the current layout. Next topic may be nice to highlight is that we will be doing a Twitter spaces with Ocean Protocol tomorrow. So that's a nice one. I think they're data like marketplace decentralized. They have a really big community as well. They're really cool people and their product is very, I think, related to what we're doing. So it will be very interesting space about data creating high quality data sets for AI and I still really believe that it will be a good fit. Where Dju even I think proposed this once but we've discussed this a few times over. But where we create a connection between creating a data set on a Fact network and publishing that on Ocean Protocol. I think that we're at a place where that could really be a very nicely integrated solution for building data sets and then monetizing on data sets. So I'm really excited for the spaces together with them. We'll definitely touch on these subjects and yeah, I'm just thinking about it. I would get inspired for possible ways to create a direct connection between Ocean Protocol and Effect Network. For example, if we're building a data set with a certain use case and then to monetize that data set on another platform and to actually using the data to train AI on the platform. I think that's sort of the ecosystem of Web three based solutions for training and using an AI. It's just very close to home for us. And definitely tune in on the Twitter tomorrow because it's going to be a nice one. I think.

#### DJSTRIKANOVA

You got it. I'm looking forward to it. I completely agree on Ocean Protocol integration. I think being able to build the data sets and just plop it right on there for monetization or just distribution I think would be great.

#### David Britt

Yeah, that you're mentioning it. Like, I'll do this for Chat out as well, too. Yeah, also join it from our side.

#### Jesse Eisses

Yeah. Ocean park has a big community as well, so it's a nice way also to explain what we're doing and get more attention to Effect Network. And it's just a really good fit. So I'm happy we get the opportunity now to get more eyes on it and to start working on this idea. This is the direction where we're going, so data sets are the most important part to make good AI. Right. We're getting right now, even in a place where AI is being trained too much on AI data, which I think these are, you shared, again some really nice articles that's like the collapse of AI, where it sort of becomes an echo chamber of trading on itself, which doesn't give new and desirable outputs. So human data is really important, and we're exactly in that spot. And being able to create data sets, high quality data sets, human power quickly, and being able to put that in a marketplace and being able, for example, to train lora. So you can actually take your base model like Llama and then put a lora on it that sort of makes it really specific and maybe even personalized weight diffs on these models to get custom versions of that. I think Effect Network is at the right place. We're covering all of that. Even going from a data set to a weight lora, for example, is something we should be looking at. And looking at how to monetize some data sets is something that should be part of Effect Network, and we need to make this as easy as it can for any AI researcher or developer to make these to enhance, to get better experiences and better results by using human data. I think this is where we need to zoom into the next avenue. Like, what we're going to develop will be definitely around these topics to make sure it's going to be a breeze to use human quality data to enhance AI experiences. I think the sweet spot, that's where the puck is going. That's where the market is going. And I feel that's where we're positioning right now to be.

#### DJSTRIKANOVA

Yeah, I absolutely agree. That article really underlines that with Chat GPT, it had kind of like the advantage where it could assume most content on the Internet was not AI generated. But as soon as they published Chat GPT, like, the first thing I saw was people making these spam blogs with just AI generated content trying to get ad revenue clicks. Right. And so that's still happening. Like, right now, the amount of information on the Internet is probably going to just skyrocket even further now because it's so easy to generate content and try to trick people into thinking it's good content, which, I mean, some of it definitely will be, but a lot of it will just be like kind of like spam will become better.

#### Jesse Eisses

Yeah.

#### DJSTRIKANOVA

It will be harder to just scrape the data you want from the Internet. Along with that, a lot of sites that have other sources, like, I think Reddit, for example, is now charging for API. Right?

#### Jesse Eisses

Yeah.

#### DJSTRIKANOVA

And I'm pretty confident it's because they don't want to just have the AI scrapers take their data.

#### Jesse Eisses

Yeah, definitely. And we're going to a place where the majority of Internet content is going to be AI generated. I think pretty soon the shift is going really quick and soon the majority of content will be AI generated and it will be very hard to tell if it is or not if it hasn't been AI generated. So for training new models, scraping the Internet isn't going to be your go to. It's not going to work well. So if we have proven quality human generated data set, which is what we do on chain, we can show the origin and the trace of the data set and prove that at least this amount has been human generated and maybe even combine it with AI generated content in a way that is the most efficient to train your models. Yeah, I think it will be a very viable commodity to have human generated quality data and there will be a real need for it. So if we can prove these things, I think that there's definitely going to be a big demand for these data sets.

#### David Britt

One problem I do foresee is that people will be using AI models in order to generate their answers. Like, that's already a problem that Amazon Mechanical Turk is bumping into right now. Apparently around 40% their submissions they suspect to be generated with AI to us established somewhere.

#### Jesse Eisses

Or did I mention this? Yeah, I would like to read that.

#### David Britt

Okay. Yeah, I'll share a link in the discord, but yeah, so that will be a hurdle, I think, for us as well. So we'll have to figure out a way of how we create the tools necessary in order to prove that indeed everything is human generated instead of also generated with the help of AI tools. I think a large part of that.

#### Jesse Eisses

Will also be like community and being able to show that we work with people. Right. And if we have unchained audit trails of where data originates from, we will be able to detect the percentage of bots. And being able to attest that you're human is going to be an important part. And there's a lot of protocols and things working on identification of people like World Coin. I don't know if you're actually the founder of OpenAI from Sam Eldman and it does iris scans to verify humans, but there's people working on it. And I think having a blockchain to show that someone is human, to have that sort of degree of certainty about it and being able to reflect on chain how much of a data set was generated by humans is going to give that sort of trust and going to be able to solve that problem. As opposed to where? If it's Amazon Mechanical Direct, they don't have that degree of transparency. So you do not know, really. You cannot really prove these things at you. I think it's something we're trying to solve. It's definitely going to be a hard thing to detect bugs, but I think transparency is the solution for it in the end.

#### David Britt

Okay.

#### Jesse Eisses

But if you can share the article, that would be nice. Yeah.

#### DJSTRIKANOVA

I'm thinking that AI in a sense is going to be a supplementary tool. It's almost going to be the equivalent of just of workers doing like a Google search. Right? So really, it's not that we want workers to use AI, we just still want them to use their brain to contribute to the answer. Right. We don't want them just mindlessly inputting it. We don't want them to treat it like they're just a manual API. Right? We want to use their brain.

#### Jesse Eisses

Yes.

#### David Britt

At least refine the answer to a point where it is usable, or they can work out the pinks of the output that they're getting from their Google search or using the GPT tool that they're using.

#### DJSTRIKANOVA

Yeah, so with that, I think we talked about this before, a rotation system I think would help with that because really what people want is the good results. And so if a worker can deliver the results, it's all right if they use AI as a supplement, but they also have to validate the results themselves. It's like similar in programming where you don't want a programmer who only uses chat GPT, but if they use it to generate some quick stuff that's tedious and they just kind of code review it, that's faster and better.

#### David Britt

Yeah, for sure.

#### DJSTRIKANOVA

True.

#### David Britt

For the hackathon. How are we going to then pitch this angle? Are we going to because I think the hackathon might be a good moment to try to start incorporating some of these tools as well, or try to inspire other people as well to start building these kinds of tools that use Effect Network and other AI technologies or Ocean Protocol. We haven't specifically talked about yet the categories that we want for the hackathon, but that might be a way of trying to inspire the participants to also go a little bit into this direction that we're talking about right now.

#### Jesse Eisses

Yeah, maybe we can move on to the hackathon yet. We haven't pinned down. We have a draft proposal and I think we're going in the right direction. We have a few potential partners. Gabby isn't here but she will give us an update soon on the exact status. But I think it would be a great like creating a data set. That's sort of the angle I'm leaning towards as a topic, like to create a data set. And we can put some restrictions around what the data set like should in golf or how big it should be, but just structuring a data set using a fact network that might be and even looking at tooling to interoperate that with existing platforms or toolings like social protocol or any other AI platform I think would be a great angle. It can either be one of the topics or it could be like the topic to create a data set with maybe AI related, maybe Jet GPT related, maybe, but some data set that's going to add stuff to a certain model and use effect network to build it. And we can give maybe people even some budget, some EFX budget from our AI fund or from another funding source, but to give them some budget to run tests on the platform to create their data sets. That's sort of where I was leading towards, but that might be a nice topic.

#### David Britt

Yeah, I'm also thinking that might potentially be a bit overarching topic as well. There's a lot of hype happening around it at the moment. I'm a little bit afraid that there's going to be a lot of competition in the hackathon market at the moment. Hackathons vying for attention of other developers, that there won't be a lot of attention on our hackathon. But that might be a good angle then to just really focus on that specific topic instead of breaking it down into smaller topics that people can build something on top of.

#### Jesse Eisses

Yeah. And for this hackathon, I think this is also DJ mentioned it before and I think it really resonates and it's important that it shouldn't be like a one off. So I don't think even if there's a lot of competition, we might have some trouble there, we might get little submissions because of that. But I think we need to aim for doing like three hackathons sort of spaced in a way that makes sense and we can learn from the mistakes in other hackathons and maybe pick a topic that's more inviting or that's more current. But also it would mean that if we happen to have a lot of competition in one hackathon, then in the next one we would like. If you do more hackathons, you will have less of the timing issues when it comes to competition.

#### DJSTRIKANOVA

Okay, yeah, absolutely. It's something I've been pushing since I joined the Dow, right?

#### Jesse Eisses

Yes.

#### DJSTRIKANOVA

I think having them semi frequently and then the price pool, we can keep it. I don't think it needs to be big enough that it attracts interest but we don't need it to be super big because the timing is we can't know what other hackathons would be happening at the same time. And so it's like when movies release, right? Sometimes you just publish a movie right when a big blockbuster hit is out and then that just impacts your profits. So you can't really control that. The more you release, the more it averages in participation, I guess.

#### David Britt

Yeah, good point. Exactly. So we'll have to keep an eye out on Dora hacks to see which hackathons are happening that specific week that we are also filing for submissions.

#### DJSTRIKANOVA

And I agree with the category. I think building data sets, I think the main effect that we can have now while workers can be done for other human tasks like the socials and stuff, for example those catalog which is now Quickcat project in a sense got depreciated because the categorization now can be done much better basically with Chat GPT, I'm pretty sure.

#### Jesse Eisses

Yeah.

#### DJSTRIKANOVA

So there's kind of a risk in trying to make a human focused tool because there's already new models keep pumping in every time I check the models are even better. And there's now sites where you can buy cards not buy, but you can download personality cards of various characters historical or fictional and then you can import them silly tavern and have a talk with them. There's so much innovation going on that I think the solid bet is just building data sets now.

#### Jesse Eisses

Yeah, I think so too. I think that's definitely and that's great as a topic for the hackathon. Where I think we're going is what I think would be currently the killer feature for Effect Network is if you could just pick a base model maybe you pick like llama the base model away and you basically define a task. It's a text model. So you define some text based task and you should be able to end up with like a lora that specializes that model to a specific topic. And I think we need to make it sort of we need to integrate with a lot of tools and make sure that the export from our platform matches with the imports of the other platform. So you get sort of quite easily from to a specialized model and there's so many open source tooling DJ you've shared quite a bit and there's all these tools popping up these frameworks and like the Silly tavern where you can easily try out and play with models. It needs to fit in there. We need to get people that user interface to get quality fresh human data that they can use to tune their models. I think that if we fill that spot, I think it's where all the attention now is going. And I think if we make the hackathon revolve around data flows and data sets, that's where we're going to get some traction for also the future, because it requires experimentation and it requires people to try new things. And I think that's exactly where the hackathons are for. So people can experiment. They will come up with some ways to create data sets. They will come up with some ways to integrate it into these platforms.

#### David Britt

I do think data sets are necessarily sexy. So we do need to kind of convey the importance of data sets and how important they are in training in AI models and how it's a piece of the pipeline that we're trying to I don't know.

#### Jesse Eisses

I think loras are really sexy. I think there's these websites, they're booming, they're selling, like, these specialized these weight tips on existing models that can for example, when it comes to computer vision, they can do a really specific type of visual and you put it on top of your model and it creates all these outputs. And they're also there. Now for text, look at maybe a specific accent or like a fairly specific one.

#### DJSTRIKANOVA

Continue. How is the lay on volunteer? We're going those OCR recognition tasks?

#### Jesse Eisses

Yeah, we bumped into issues there. We did a few rounds of the annotations. We bumped into issues. We get quite a few updates. The template has gotten pretty advanced, but it's getting better and better. At the moment, we're still working on the validation interface. So Rochelle is actually leading this campaign. So she's been managing the results, but she ran into some issues where she couldn't inspect the results properly and she needed some more UI elements. And I have not seen like, we I think we ran the last data set we ran I have not seen the results. I don't know if you can comment on them, Rochelle, but we need a few more improvements. It's working like it's progressing, and we're getting there.

#### DJSTRIKANOVA

I think following up with Leon and being active volunteers, building these data sets, I think will be very important to establishing this image that basically all these communities, we need to be a part of them and contribute to. Them not only just for the interest of effect network, but I think just in general. In AI, we are part of the open source movement.

#### Jesse Eisses

Right.

#### DJSTRIKANOVA

Everything Effect Network has done is open source. And I think so the data states, we built data sets, we build, and they will help just kind of advertise that we exist and we do this.

#### Rochelle Trevarrow

I can give a short update to elaborate on what Jesse said about the OCR tasks. The task template that he built out.

#### DJSTRIKANOVA

It was hold on, David. You're my kind of echoes, Rochelle.

#### Rochelle Trevarrow

That's what that is.

#### Jesse Eisses

Go ahead.

#### Rochelle Trevarrow

Okay. Is that better?

#### DJSTRIKANOVA

Yeah.

#### Rochelle Trevarrow

Okay. I ran a few campaigns of tasks with a small pool of trusted workers, and I had considerable chats with a few of them about the task itself. As far as was it easy to complete the instructions? Was it easy to navigate and actually do the work? And those results were very successful. So the worker experience is good, the task window and the task itself works well. The part that we're at now is getting the validation part right to make sure that we can get the quality of results that they're looking for. So like Jesse said, we need a few UI updates for me for the validation part and then I think we'll have a lot of traction to move forward. That was my update about them.

#### DJSTRIKANOVA

Sounds good because it sounds like once you get all these things worked out, you can scale it up for even bigger.

#### Rochelle Trevarrow

Yeah, exactly. It's just getting it right from the beginning just to make sure there's no crazy bugs that we'll uncover later that will completely derail it. So, yeah, it's going good.

#### DJSTRIKANOVA

Great. And I think this AI fund I think will be very good for this. I've noticed in the lay on they have other occasional requests for help doing stuff. So once this is ironed out, I think we can also participate in other ways and hopefully all of this establishes kind of a relationship that's very positive.

#### Jesse Eisses

Yeah, definitely. That's why it's an important trial, what we're doing now, and also to showcase that the AI fund works and we can prove that it skills. So we'll make sure that this trial gets we really give it a shot and come up with good results and we learn from all the things, little problems we had or quality issues. We need to make sure we identify what they are and how we can avoid them in the future so then this will be quite scalable. And of course it's the core product, right? It's creating data sets for AI. So we need to make sure that it becomes really easy and clear for people to run campaigns and get the proper data back in their system.

#### DJSTRIKANOVA

Yeah. You mentioned loras. I only have a surface level because I know I can use loras when I play around with stable diffusion. And I can use it's like you have this general model and then the loras is like more specific stuff that allows you to get more what you want.

#### Jesse Eisses

Yeah, exactly. They're specifically for these models, but they're basically very small weight diffs on top of existing models that if you desired outputs and you can stack them together so you can add multiple oras they're really cool. They came out of this open source community like from hugging face. And there are some markets on there that I've been browsing a bit and there's really big markets for people creating loras for specific things. And they run on human data. Right. Alora has this like to train it, you need to give a data set and then it creates this. Yeah, they train pretty fast and they give you basically a weight diff that you can stack on top of these base models. It's a pretty cool concept that I think. I don't know if it's the final it's really new so I don't know if it's the final part of training AI or if there's a new thing going to pop up. But I do know that I do believe that human data is that essence that fuels these personalizations that people really love to play around with at the moment. So we could definitely make Effect Network part of it.

#### DJSTRIKANOVA

Yeah, I think it would be great if you could just self serve yourself something like you want Aloris for something and then the workers just build it for you though. I don't know, that probably has a lot of complexity involved since I assume you also have to do the compute, which I think would be the tricky part. But the data definitely can be generated by Effect Network.

#### Jesse Eisses

Yeah, and there's all these tools for doing the compute. So of course you need a GPU or you need to tap into a cloud provider for your GPU power. But there's these platforms now for training these. So you put in the base model, you put in the data and it comes up with a new model. Like there's these really nice open source solutions for it. So my next hunch would be to look at those platforms and see if Effect Network could just be a data source basically for that training. And of course there would still need to be compute and there's more elements in the spec, but feeding the data would be exactly where we fit right now. Maybe we can even do more parts of that but for now, feeding human data would be great.

#### DJSTRIKANOVA

Yeah, as you said, I think exportability is the most important because there are all these open source tools and they're not going to want to use just Effect Network by itself. But if it could be a tool to generate the data and they can just import it into their favorite tool, that makes things much easier for them. All this sounds.

#### David Britt

That'S also a place I think where you can potentially start thinking about having it as a paid feature, having that compatibility with other providers and then having people who want to export and import that data into those specific tools pay then for that specific feature.

#### DJSTRIKANOVA

Maybe down the line it always starts free. All the best tools, they always start free until they have a bunch of users, then they increase the prices.

#### David Britt

Yeah, that's a good point. It's surprising how Big hugging face has become starting off as a free tool. Anybody can use.

#### Jesse Eisses

And workers need to get paid. But right now we can use the AI fund to really bootstrap and start off. Experimentation is key. I think we shouldn't be afraid and we should really try to do as many types of data sets and to explore because if we need to find that need, where people need data, that's where we need to find our spot. So I think we don't have to worry too much about the cost of it because with AI fund we can bootstrap it. And of course, workers need to get paid to get quality data. But right now we need to make sure we find the people that really need it and that we make it so convenient for them that they don't think twice about using effect network and buying some data there and then the convenience of the purchase. In the end, it just goes to the workers. Right, and a little bit of the.

#### DJSTRIKANOVA

Fee goes to the Dow down the line. If you build like an app for this you could just abstract away even the tokens. Kind of like with Quickcat where you just used just an API where they just paid money really and then it was used to buy EFX in the back end and so that way they don't even have to deal with the crypto part.

#### Jesse Eisses

Yeah, I think that part will be quite doable like where people can pay in euros and the payment processor will get a little bit of fee in that thing but then it will just get converted to EFX and you don't have to worry about the crypto site as a client. I think we're getting there. I think that will be definitely doable.

#### Bree

How close are you to that?

#### Jesse Eisses

I mean, if you want to do like right now, any person could help out. If someone would come to me and say, hey, I have 500 and I would like to do a data annotation, I think any person could sort of help out to convert that. If you're looking at massive data sets that wants to scale, you can still EFX is quite a bit of liquidity. So I don't think there is some human effort involved and some trust involved to convert from fiat to EFX. But I think any service provider could basically do that because it's just going to an exchange and swapping the money and making sure the legalities are all in check for whatever jurisdiction the financial transaction takes place. But on the liquidity side, I think we're there and on the surface providing side, I mean, if this happens a lot and at scale, you would want to look at partnering with MoonPay or partnering with some providers and they will be happy to do that if there's the volume for it to make this completely automated. I don't see that part as a problem at the moment.

#### DJSTRIKANOVA

Yeah, I think what we need now really is just to get attention and show off we can do this because I've yet to see any project that's so specialized in what Effect Network is doing. So we just need to show that it can do it.

#### Jesse Eisses

Welcome brie, by the way. Good to see you.

#### Bree

I spoke before, but it didn't sound so I had to leave recheck in, you know, all that stuff. I had a few things, and I wish I'd written them down as I was listening, but why can't we have that gateway to be at the Spotify app right now? Is it complicated?

#### DJSTRIKANOVA

You meant shopify?

#### Bree

Well, not shopify itself, but let's see, app scene. My mind is just mush right now. Yeah, thanks.

#### Rochelle Trevarrow

What he's doing is, since those are Quickcats clients using his plugin, he is doing the conversions himself. They're paying him in Fiat to his account, and then he's buying EFX on the back end for it.

#### Bree

Yeah, I understand the mechanics of it. If we really want to get out.

#### Rochelle Trevarrow

There, there's a lot of data set.

#### Bree

Builders right now who are not using crypto. Right?

#### Rochelle Trevarrow

Yeah. But then that comes down to, okay, a real life bank account hooked to an exchange account. There's taxes, there's reporting involved. For me, I personally would not want to do all of the Fiat to EFX stuff platform wide for effect network, because then there's a tax liability that I have to deal with. So that's why I wouldn't do it. And as a company or as a Dow, there's some things that would need to be in place. So that's why Jesse said it's better if we have a lot of volume, then go with a company like MoonPay that specializes in it, that's already had their regulatory and compliance and infrastructure set up. So that's why we're not going to spend a lot of time and resources making that now when there's no volume, when first we just have to get established and have people using it.

#### Jesse Eisses

Okay, but it is getting better though. I think two years ago, this was a very big problem, but now there's a lot of companies making big strides. Like, Fiat on and off ramping is becoming better. Like, Stripe has a really good surface right now. If we would have to build this soon, which I think if people really need it, then we will build that soon. And you could use Stripe to basically get EOS into someone's crypto wallet. And then we just use the liquidity pool on DeFi box to switch that to EFX and put that in the Fee account. Like, all of that would be one automated process. So maybe spin for a minute, but then you could basically go from credit card to effect network EFX on the Fee account, where you can buy tasks that would just be one credit card transaction and then waiting for a minute for it to process. I do think we're getting there because the legalities are tricky, but companies like Stripe Mastercard, they're really taking this on now to make sure that these solutions become easy for the consumer and also for companies to facilitate.

#### Rochelle Trevarrow

Yeah, and even if you look, PayPal in the last nine months has really worked hard to incorporate crypto everywhere.

#### Bree

Canada yeah.

#### Rochelle Trevarrow

It'S getting better. So while everyone else improves on that, on those Fiat ramps and stuff, we'll just do our part and then probably pick a provider when we need to.

#### Bree

Now you need so much patience in this game. Things move quickly but not fast enough. Not that it's game.

#### DJSTRIKANOVA

What's the status of the bridge? Like are you building the last dow? We talked about it.

#### David Britt

So the bridge has been updated, it should be working properly now.

#### DJSTRIKANOVA

I meant more like along the fee. I think the idea was to build a bridge for the low EFX amounts.

#### Jesse Eisses

Yeah so technically we updated the bridge and it's working again but it has this big fee which is still a problem. So we cannot use the bridge right now for small amounts because she will just evaporate the amount because the fees are higher than what you're swapping mainly but we are working on it. I think we've discovered that atomic swaps is interesting and cool but it's going to take too much time and distraction from building the more important platform features. So right now we're aiming towards launching a proposal probably already for this cycle on providing liquidity on both sides and just have once a cycle a swap happen that people can do small transactions without paying a big fee. It will not solve though like people requesters basically using binance smart chain ethics to fund campaigns. So that part is still I'm personally almost leaning towards encouraging people to use EOS more and more and try to take that angle because it's going to take more effort than we expected to build our own bridge or to build our own atomic swap solution for small amounts. It's just tricky in a few ways.

#### DJSTRIKANOVA

We do want to focus on all these AI features and serving this community. It does feel like it's a distraction that was kind of frust upon us.

#### Jesse Eisses

Yeah, and maybe if we just encourage people to use EOS, especially on the requester side, and improving on to crypto transactions and using AI fund to basically help people fund it so they don't have to worry too much about your site. And EOS is really still improving a lot on wallets and it's getting more convenient and more cheap, really, every day. So I'm more confident that eoside will be the most convenient way to do this instead of doing a bridge and the binance march inside for using the platform. So maybe we should just go up right now with a solution so workers can at least swap their EFX using maybe once per cycle. We can help them swap it and basically recover the fees because we pull them together. I feel that that will work and it will solve the pain some workers have currently it's only very few so it's not even going to be, I think too difficult to set up and on the long term maybe even face the bridge out or look at different ways, but mainly get requesters to use EOS.

#### David Britt

Yeah, exactly. I think especially considering EOS does provide requesters a couple of more features compared to them using Finance Wallets, we should encourage them to use EOS as requesters and indeed, I don't think there's enough volume to justify really trying to build out that feature for having atomic swaps yet. It might come there someday, but at the moment it's not there and I think our time and investment is better spent elsewhere.

#### Rochelle Trevarrow

My personal opinion is that I remember when we started having our token also on BSE, and I thought it was going to be good and there was going to be a great community over at BSE and things and if there was. Maybe I missed out on some things, but my personal observations is that the EOS community is so welcoming, there's so much going on in it, and I would rather stay with an EOS side than explore anything on BSE. Even. I just don't feel like there's a lot of support or even interest with BSE projects that run on BSE and stuff that we have kind of anything in common with. But on EOS there's so many amazing things and I personally would rather see us just kind of get rid of the BSE stuff altogether. But that's just me speaking on my own opinion.

#### DJSTRIKANOVA

Well, I don't think we could even if we wanted to because it's a P token thing, but when it was first done, the ENF didn't even exist. So it's more like the EOS community improved while the BS bion smart chain community kind of, I guess didn't really change much in the years.

#### Bree

I think I would agree with that. The EOS has been really improving.

#### Jesse Eisses

Yeah, me too.

#### DJSTRIKANOVA

There are, I think some like I found this tool called Tours Protocol which basically, from what I understand, you can basically it checks if you have crypto in your wallet and if you have a sufficient amount, that means you are entitled to use like a model API for free and they use Binance smart chain. I do think that there definitely could be some synergies with Binance smart chain applications. So I don't want to throw it out just yet, but the bridge fee kind of just makes things annoying. I think we just need to just keep an eye out for crypto DAPs related to AI because I think they're the type that we can really kind of appeal to and maybe kind of work together with.

#### Jesse Eisses

And I think the binance marching side does have I think you're absolutely right that like when we moved to binance marching, EOS was sort of dead and dying a bit and this changed because the ENF got put together and there's a lot being built on EOS right now. So I think it makes really sense to embrace it and to also encourage it because it's going up binary smart chain has also not been growing at all. Yeah, absolutely right. I do think that the liquidity that Bank Expop provides and there's a lot of traders on binding smart chain so I don't think there's a lot of AI scientists building data sets on binding smart chain but there's a lot of people trading and that gets the liquidity to the token that has some value. So I don't think shutting it down would even be possible, but also not necessary. But for us as a project to really encourage people to stay on the EOS side or come over to the US side. I love that for example, EOS support is getting so much funding and growing so these facilities really help users to onboard and learn the tools and to get started on the OS. I think it's going to become a lot nicer than it was two years ago so that's a good thing for us. And maybe the bridge, we should just encourage people to only use it for big amounts or it's not super convenient and for users on the platform they should probably use EOS for working and posting tasks. Yeah, I think that makes sense.

#### DJSTRIKANOVA

The bias smart chain is good for getting your feet wet but if you want to do anything substantial you're going to have to move and migrate to EOS.

#### Jesse Eisses

And you suggested last time and I think it's a cool idea, definitely doable. Where you basically work on a hot wallet or on a binary smart chain key earning your first EFX and then we will provide this really convenient way where you can use your earnings to convert it to an EOS account which it doesn't cost that much at all, maybe a dollar or something. So you could convert that and create your EOS account from within effect network. I think that would make the onboarding experience very convenient for people and it's very doable as well technically in our system.

#### DJSTRIKANOVA

Yeah, now that we have a sizable pool on defy box I think all that can be done. You can now exchange the EFX to EOS automatically. Yeah, I think that would definitely help out a lot and then same with that once there's time to do it. I imagine maybe the same can be done for finance smart chain as well where you could just pay some EFX, like if you could pay EFX on one side and then it generates an account for you but it just uses a different pool of EFX and then you can use an EOS wallet.

#### Jesse Eisses

Yeah, definitely. We can consider, we can see even if people have some EFX there it is almost like also a bot protection because providing free EOS wallets for users wouldn't even be too much of an issue as long as it's not being abused by bots. And we are a human data annotation platform. So I think people having so many effects in their wallets would sort of allow us to do bot protection and provide free wallets. But, yeah, there's more ways. It's already as long as they can.

#### DJSTRIKANOVA

Just pay whatever currency they have. Right, so if they have their efxp tokens, they just pay to your service and then it generates an EOS wallet for them and then they can mike basically, if we don't want to have a very nice bridge, I think we still probably could use down the line just a service that helps migration be very easy. Because I think with POS, the learning curve always starts with creating the wallet. Right. For me, it involved going on some website and you're kind of worried too, is this a legit site? Can I trust it? And then you either use your credit card or you send it some crypto. It's kind of a hassle. So having a service will probably help a lot with migrating people to EOS.

#### Rochelle Trevarrow

Worker standpoint, you never want to have to pay to earn money because that's the first rule that is a scam and whatnot. So for me, it would be great if you want to test it out here, create a hot wallet, start earning some EFX, do your qualifications, and then having the worker be able to convert what they've earned on the BSE side over to an EOS account, that would be great. However, like Jesse says, it's easy. I would want it to be where they can keep their earned qualifications because no one wants to then, okay, here's your EOS account. You log in, but then all your qualifications are on the one you used with BSc hot wallet. It's got to be able to also convert over as well.

#### DJSTRIKANOVA

Yeah.

#### Jesse Eisses

This wouldn't be like a restart of your account, it should just be changing the authority of your account, but keep your history and your qualifications there. That's a good point, but that should indeed be how it works. It's past six already and I really have to go. I'm already a bit late. We go for the agenda at least. Yeah, I think I have, like, a minute if anyone wants to.

#### DJSTRIKANOVA

The last thing I can say is thank you for your donation to my Pamela Grant, and you two, Brie and Miguel, the last day.

#### Jesse Eisses

Yeah. Just in time for making the second iteration of the ground, because it's really cool. The results you have in the last one were really promising, so I'm happy you are making the progress and want to continue with it.

#### DJSTRIKANOVA

Yeah, I'll make sure to make the update. So all the NFT collections we can use for the update you've shown us, you can search for them as well and try to find the image you like the most.

#### Jesse Eisses

Yeah, amazing.

#### DJSTRIKANOVA

All right, well, I guess I don't want to hold you any longer, Jesse. So until next time, then.

#### Jesse Eisses

Yeah, thanks. Everyone was a good one. See you. See you guys next time.

#### Rochelle Trevarrow

Nice chatting with you.

#### DJSTRIKANOVA

All right, so I think we covered everything. So I'll see you all.

#### Rochelle Trevarrow

Oh, DJ, can I still donate? I knew I was forgetting something.

#### DJSTRIKANOVA

Yeah, there's one day left.

#### Rochelle Trevarrow

Okay, I do it.
