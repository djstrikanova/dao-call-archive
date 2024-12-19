---
description: >-
  *Assembly AI generated transcripts may not be 100% accurate, listen to video
  for original audio.
---

# July 12th, 2023 DAO Call

{% embed url="https://www.youtube.com/watch?v=Q2h1dO4HHJs" %}

## Short Summary

* David has been working on a prototype tool to help review Optical Character Recognition tasks for LAION. Label Studio Templates can be integrated into Effect Force.
* Hackathon partners are secured though exact amounts and schedule not yet set. Goal is August.
* DJSTRIKANOVA discusses Eden on EOS direction, investigating potential collaboration and synergy over hackathons.
* (For Reference, Label Studio is an Open Source Data Labeling Platform that volunteers on LAION use https://labelstud.io/)

## Assembly AI Generated Transcript

{% embed url="https://www.assemblyai.com/playground/transcript/60lcjnyk5c-3f31-48dd-8c85-4da2b843bc59" %}

#### DJSTRIKANOVA

This is July 12, 2023 DAO call. And I guess here's David and Rochelle with their updates on how things are going.

#### David Britt

Okay.

#### Rochelle Trevarrow

Sorry, I was just popping the call out so I could click through and make sure I speak about everything we want to update on Th. So I need just a moment.

#### David Britt

Things have been a bit slow these past two weeks. Wasn't able to get around to publishing the dashboard. I'm not really sure why I'll need to bug him in order to get him to publish it. But besides that, there are no proposals this cycle. There are also no agenda items. The one big update is that we've been working on the label box for Layon, so we finally have a proper front end for him that Chris can actually take a look at all of the results properly. I've been working around with it, and it's a really good tool, actually. I think there's a lot of potential here of incorporating the label box tool deeper into how we label data going forward. So I'm really imagining that we'll start using all of their different templates for data labeling. Instead of building out our own things, we'll start leaning on label box a bit more. I can share a link with you that you can take a look at the latest campaign or task patch we ran. I'd like to get your feedback on it. Where's a good spot for me to drop? There is a chat here, right?

#### DJSTRIKANOVA

Yeah.

#### David Britt

There we go. It.

#### DJSTRIKANOVA

So what am I looking at here?

#### David Britt

So that first one all the way up at the top is at the table. That's one batch. It's 200 tasks. You can click on it then, and it'll drop down another table below it with then individual tasks. And you can click on them and then see the template and the results loaded into the template. So this is kind of like the data that Chris would be interested in. So it's an interface for then people who want to see how their tasks were done.

#### DJSTRIKANOVA

I see. Yeah. This is pretty neat. Make sure to share this with Chris too. Yeah, keep them updated.

#### David Britt

Indeed. This is part of too long we've been working indeed. And making sure that we publish batches and we get some proper campaigns. I think we've been working on this for two weeks now, and the first couple of batches didn't go well. Just having issues with the data properly loading in and whatnot. But, yeah, I'm excited to share this with him, and I think he might actually find this useful, even though it's not very pretty, but at least it's usable.

#### Rochelle Trevarrow

And then, too, this also shows the worker ID and the time it was submitted. And we identified a couple of the workers on here. Either. Some tasks were done. Okay. Some were not. The greatest instructions weren't followed. I know a couple of them, I noticed the text in the image was upper and lowercase mixed and what they input was all caps. And so that is not how the directions of the task said to do things. So a couple other I think they were just, I don't know, use the term loosely, scammed. So this experiment, this one was done with just workers with a human qualification. I have the same data set. David gave it to me. I'm going to rerun this one again and use that special qualification that I handed out to known workers that I have a working relationship with. So I guess you could say trusted workers to do. And then I'm going to compare the results between the two batches to see of course, all this is being done without a qualifier test in place. Since this is still mostly in the planning stages.

#### DJSTRIKANOVA

This is actually really nice.

#### Rochelle Trevarrow

We don't know how we're going to fund this or proceed working with Chris.

#### DJSTRIKANOVA

Like I'm looking at it right now, you can basically view each task and you can also verify I'm looking at their labels and also the box. Right?

#### Rochelle Trevarrow

Yeah.

#### DJSTRIKANOVA

This is actually really great because then maybe if you could add just like one more thing. If you could just easily say you could have a moderator just manually scroll through these and then just down vote any bad ones. And then after that get a list of the good workers and then you can just iterate this process and then you can get like the best workers doing the sets.

#### Rochelle Trevarrow

Qualifier was in place. I think the results right off the bat would be great. Excellent. David brought up a good point when him and I were discussing this that he created. It'd be really nice right next to the view button, or even when you hit view when you're looking at a task, while you have that task up, say you don't like it. Like it was done just completely wrong. There is a way to repost just that task to have it redone.

#### David Britt

Yeah, exactly. I don't think that's properly implemented yet, but there should be a mechanism where you can reject the task, but because it's already paid for, then it doesn't go then to the worker, it just gets reused then for another worker to pick it up. Yeah, I think that might be a good mechanism in order to where you can moderate the task and you can get proper results out of it without relying too much on the qualification. Even though I do think the qualification is still a good idea. But yeah, we'll just have to rely a little bit more on moderation, I think going forward and just having such an easier interface makes it a lot easier to then verify that the tasks were done properly.

#### Rochelle Trevarrow

Yeah, I just think the whole thing is great. Just even the task template, being able to pull from label box and integrate completely with all of that. And then this too seeing the results and going through the results and everything, just being able to show properly and stuff, it's a feat in itself. So I am so psyched and pleased with this.

#### David Britt

Yeah, absolutely.

#### DJSTRIKANOVA

Yeah. I think this thing I can even just envision Chris himself just looking all of these and then just, okaying, which workers each time and then it gets better every time and I think that already will help get more and more tasks done.

#### David Britt

Yeah, exactly.

#### Rochelle Trevarrow

It'll also help him almost curate his workforce because as he keeps approving, if he just notes down some worker IDs of workers that he keeps noticing are doing consistently well, he could give them a separate qualification. And then when he has images that are difficult or more involved or that take more time, like have more boxes of text in them that need annotated, those cost more. So then he would pay more for those tasks to the workers, but then he would have his group of trusted workers that he could put on those and knowing that, okay, when I load these tasks of images that have so much text and I'm paying the workers more for them and I'm paying for these things up front. By loading them onto the platform, I know that money is going to be put to good use and not just have to go through and reject a bunch and things. So it's a way for him to not only tailor his workforce, but also make his funds the most used in the most cost effective way.

#### David Britt

I'm still not sure though, how we would kind of give him access to be able to curate workforce because like, we're managing the campaign right now. Yeah, but I'm guessing we could sit down with him or give him a special permission that he can also then access certain tasks or be able to do certain actions. But yeah, it's definitely something that we can think about. But, yeah, I think for now, this is, like, a pretty good prototype. And we can keep leaning on this as well and try to find a data set somewhere and just use that as something that we can just continually keep pushing tasks onto the platform as well so that we have an active group of users that are actually doing tasks every day. Because we had that previously with the Twitter tasks. But yeah, as you probably know, Twitter is a bit of a yeah, like it feels like that whole boat is going under at the moment and we need something else to be able to fill in that void. So I think this is a good thing to fill in that void with and I feel like it's much more true as well to what the ideals and the motivation for starting Effect Network was.

#### DJSTRIKANOVA

Yeah, definitely hope, definitely make these updates to Chris because I think he'll be very interested because I think layon in general will be a great way to show off what we can do. Just building a big data set. I think even with the tasks, I think we have a good amount in the AI fund. Right. So once we get the process down, I think we can definitely go for a big amount, at least a good portion of the AI fund.

#### David Britt

Yeah, indeed. I'm not sure how much it is, but indeed.

#### DJSTRIKANOVA

Well, he said one of the numbers he threw out me of the images that need to be done, it could be up to, like, 10 million. But I think the starter set that I think we want to get done is 100,000.

#### David Britt

That's still a lot. That's a huge amount. That's an exciting amount to think about. But yeah, definitely. Indeed. I'll do it right up to Chris and we can iterate on this a little bit further.

#### DJSTRIKANOVA

Yeah, definitely do that. Because I think my personal opinion is, and it remains to be that I think it's easy enough to make your template and make the DAP it's the worker management that's tricky. And the tool you're working on, I think, could definitely be used for that because I don't know, rochelle, a while ago you were building this validation service, but I don't know, it seemed to kind of simmer down. But I think some sort of tool to manage your workers so you can filter out. Like, you could start off with cheap tasks to just find out which workers are the best and most serious, and then just even moderating yourself to find the best workers, I think is a very good way to get consistently good work.

#### Rochelle Trevarrow

Yeah, I'm still actively developing it. It's some features that I want built in on. Kind of like the requester side of the UI, with the UI updates for effect for us. Yeah, there's some features and buttons and sorting, I guess I want to say, like modules or interfaces on the requester thing. Like when you can see your campaign results and the completed tasks, how you can hit the eyeball to view and things. There are some buttons I want to have put into where you can reject the task.

#### David Britt

Yeah, some of the things I've done for this interface, I should be able to do that for the force as well. So just like, in general, to have these features already makes it so much easier to just quickly go through them and instead of doing all of the grunt work necessary to load it in and then copy paste the links and whatnot, it should be much easier. So I'll be taking a look at that soon.

#### Rochelle Trevarrow

And then when we do have those features in place, there will also be in depth how to guides and tutorials linked nearby closely in relevant spots that point the person, whether they're a requester or a worker, to helpful information to make the experience completely better and intuitive and just really support people on both sides. Of the spectrum with getting work done on our platform.

#### David Britt

I did notice going through it myself, it's very tedious to go through the different steps of selecting the annotation box and then filling in the annotation. I've been kind of imagining that all of those little steps could also be broken down into a task. So right now, you have to do the whole process for one image. And I think that's where a lot of people kind of give up when a particular image is too difficult, they just give up.

#### Rochelle Trevarrow

Go ahead.

#### David Britt

I imagine a better process would be every time, for example, somebody they pick up task and the initial part would be them just like creating the label box. And then afterwards that a new task would be created off of the back of that one to be able to fill in the content of that specific label box. And so it will go through this iterative process until it ends up as a complete labeled with all of the necessary data.

#### Rochelle Trevarrow

That's what I originally designed with that plan that I shared in drive. And then Jesse was like, well, that's pretty in depth because I was like, immediately, as soon as we got this, I made this huge, giant plan and rollout and how the order of things would go and one would feed into the other, the other. Yeah, it was just insane. I wrote a book like I always do, and Jesse was like, that is great. It's a solid plan, but this is still in the beginning and make sure everything technically can work first. So let's do the testing and the build with everything in one, and then if it's going to be feasible and this is really going to be a go, then we can split it into the three different ones. Yeah, I have three different qualifier tests designed. I have three different tasks designed. I have the whole validation process for each of them. The qualification process for each of them. Yeah, it's all made up. It's like a million things. I got it all, and I'm just like, okay, now I'm just waiting for the tech and the fine tuning with that and stuff.

#### David Britt

Okay.

#### Rochelle Trevarrow

Yeah, I shared this with you.

#### David Britt

Yeah, could be. That's probably where I got this idea from.

#### Rochelle Trevarrow

Probably things going on.

#### David Britt

Indeed. Yes. We should definitely take a look at that after the hackathon. I think then we'll be able to have some time to work on something like that.

#### Rochelle Trevarrow

Yeah, it's going great so far.

#### DJSTRIKANOVA

Speaking of the hackathon, how is the progress with that going?

#### Rochelle Trevarrow

It's going smoothly. Gabby has been working a considerable amount, having meetings and talks and notes and planning. She's really spearheaded this, and she is like the go to person for organizing all of it. So we're all working along with her when she needs us to do certain parts. It's still a lot of things with figuring the budget, exact dates, who's partnering with what, who's sponsoring what part of it and things. And I know she has a marketing plan already. Skeleton outline already built around it. Now it's just left to the decision makers with budgets and finances with the other entities and Jesse to fine tune like the actual goes with things. So it's going along good. It just takes time. People in their different workloads and time zones and stuff with their own projects, events and tech things to get everything to gel at the same time.

#### DJSTRIKANOVA

Is Gabby in Netherlands with you all, David?

#### David Britt

Yes, she is living in the Netherlands indeed. But she's always working remotely so I don't really see her that often.

#### DJSTRIKANOVA

Okay.

#### David Britt

At all actually.

#### DJSTRIKANOVA

Then is she able to make the next Dow calls?

#### David Britt

Yeah, I can ask her to.

#### DJSTRIKANOVA

Yeah. It would be nice to have her updates as well.

#### Rochelle Trevarrow

And by the time the next Dow call comes we'll have more concrete dates and stuff I think as well.

#### DJSTRIKANOVA

Right. So August is for sure then.

#### Rochelle Trevarrow

So far.

#### David Britt

Indeed. Like it is supposed to happen in August.

#### DJSTRIKANOVA

But I know you wanted to complete some qualifications updates. How are those going?

#### David Britt

I didn't manage to get around to them.

#### DJSTRIKANOVA

Okay.

#### Rochelle Trevarrow

I know I'm resuming them. I had a little bit of time off around the fourth holiday so I was kind of working part time while I had holiday time off and family visiting and a few short, few short trips. You know how the 4 July is. It was really weird being in the middle of the week, but I had a whole week of light work to get done or that I worked. I put in a little bit less hours but I am back full steam ahead this week. So Monday and Tuesday were catch up days and today is just organizing and planning day going through all my backlog. And the qualifications ones were up there. I have to go through and make sure anyone waiting on a pending call has it. And I have a folder to open of qualifications in progress. Like just standard ones revamping the English proficiency, basic English proficiency. One that is still ongoing and then exploring relevant ones that could be standalone or used in part with a combination of others for our everyday offerings for requesters for free. Like a basic set of free ones that are just built in for people to use on our platform. And of course that always leads me down the rabbit hole of specialized ones we could create that would be lucrative, that could be upsells and profitable for the Dow to use and get a revenue on too. That's that stuff. But that's my jam. So that's like my favorite part of what I do. So for me right now it's cleaning up the boring things that I don't really love too much so I can get back to doing the stuff I really love. My computer freeze.

#### DJSTRIKANOVA

No.

#### Rochelle Trevarrow

Okay.

#### David Britt

There goes no. Yeah, you're fine.

#### Rochelle Trevarrow

Cat killer. Again, sorry.

#### David Britt

Was there anything else important that we need to talk about? Because I do have to get going soon.

#### DJSTRIKANOVA

I think you covered the updates. Yeah, just remember to update Chris because I think Leon is always interested in people who help build up their data sets. So I think that will definitely be a great resource for us to be get close to.

#### David Britt

I agree. I'll also get Gabby to publish an update about the hackathon this week because we really need to get on top of that and make sure that at least we have some marketing material out there and to start letting people know that we're doing the hackathon.

#### DJSTRIKANOVA

Yeah, I've been following do you remember Eden audios?

#### David Britt

Yes.

#### DJSTRIKANOVA

So I posted an article in the general chat form. So they're kind of like trying to figure out what their Dow should do and they're settling on becoming incubator accelerator for basically the EOS platform. And so yeah, I'm trying to I think I helped set up an interview. He's called Nova Crypto with Jesse, and I think they'll have one. I don't know when it will be though. But anyway, I think I sent them a message. I think there's definitely potential for collaboration and maybe being partners, but I don't know. With Edenos it's kind of like their Dow is kind of the exact opposite of ours in the sense that it's like super bureaucratic. They're really talking about the Bylaws and all these papers on what Eden should do, and they're making all these circle committees, which is similar to what you wanted for effectile, but they're, like, codifying it and everything and yeah. So I don't know what their timeline is on when they'll actually start doing the incubation accelerator stuff, but I think it's the direction they're heading towards. And since I think we're basically one of the few DApps running on EOS still right? So I think there's definitely some synergy there and all effect DAPs naturally run on EOS too. So I'm hoping we can set something up, but that's just what I'm thinking of. Nothing concrete has happened.

#### David Britt

Okay, yeah, that would be great. I can imagine. Indeed. They have some funds and they want to start using it a bit more proactively. I'm not sure how that would work, but yeah, it sounds really interesting though.

#### DJSTRIKANOVA

The way I just envision it is I know in the hackathons we're seeking partners, so they could be like a partner as well. And I could contribute, say, like 2500 EOS to a price pool for whatever their favorite application is that they want to continue in the incubator program or something like that. And it could just help drive more participation in the hackathons.

#### David Britt

Yeah, Gabby is the one that has managed to line up a couple of partnerships and I think so for now, we're done. Actually we can get some more funds. I think that would be always welcome but the idea is also as well to do another hackathon later this year. So maybe they would be a good partner then for that hackathon instead of this one.

#### DJSTRIKANOVA

Well, I think that will be the case too, since as I said, they're bureaucratic, so this whole thing may be only possible for them to do like a few months from now anyway, so that's what I'm thinking. Okay, but I read the lenny sent me the bylaws and I think they are interested in doing frequent hackathons. So not only could we, I think, have them as a partner on our effect hackathons, it would be great if we could also contribute a price pull if they have hackathons too. So yeah, I'm keeping on top of it and if there's any time for establishing something concrete, I'll let Gabby know.

#### David Britt

Yes, please. Yeah, that would be great. I really do need to get going though, but yeah, thanks for the updates and yeah, we'll be in touch.

#### DJSTRIKANOVA

Bye, David.

#### Rochelle Trevarrow

See you. Bye bye.

#### DJSTRIKANOVA

Bye.

#### David Britt

Talk later.
