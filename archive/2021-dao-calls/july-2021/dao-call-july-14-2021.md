# DAO Call - July 14, 2021

‌

​​![Text

Description automatically generated with medium confidence](<../../../.gitbook/assets/0 (21).png>)

**Summary Notes,** Weekly DAO Call, July 14, 2021

‌

**Team in Attendance**: Jesse

**Members in Attendance:** @ce, Alan, Bree, DJSTRIKANOVA, howard k, splottingham

**Roles:**

Call Moderator: Bree Recorder: Bree Proposal Tracker: splottingham



**ANNOUNCEMENTS**:

Find the AMA write-up and audio links here: [https://effect-dao-docs.gitbook.io/effect-dao-amas](https://effect-dao-docs.gitbook.io/effect-dao-amas)

Thanks to Jesse for the AMA recap! This was really well done, and it was really cool to get a tour around Amsterdam!

Thank you to Jesse for his nicely written article about the DAO [https://medium.com/effect-ai/6-month-anniversary-of-effectdao-bd655cc96241](https://medium.com/effect-ai/6-month-anniversary-of-effectdao-bd655cc96241)



**PROPOSALS:**

DAO Governance Rewards 30% Unused vs Fixed [https://dao.effect.network/proposals/64](https://dao.effect.network/proposals/64) Status: Pending

* How much does the 30% distribution of the unused cycle budget influence voting behaviour?
  * Currently, votes do seem to be influenced by the rewards given via the 30%. This does serve as an anti-inflationary mechanism to help keep spending from being too high, but at the same time it does seem to influence a resistance to spending.
  * The price of EFX is not really high enough at the moment to really allow for substantial spending. Now might be the time to address this before the price does get substantial, because it will be more challenging to change it later.
  * When larger proposal asks start to come in it would be better to not have a variable reward system that is dependent upon how much is paid out.
  * If we have a base amount, then when the network fees start coming in automatically this will be on top of that amount. These would then be separate from the cycle budget for spending.
    * The burn mechanism could then be switched on.
    * It could be that the 30% of the unused cycle fees for distribution could be stopped and just returned to the treasury, or could be burned instead of distributed.
    * Network fees are still to come, to be caught up with, but automation will distribute these fees each cycle.
    * Ideally, there would be only network fees for distribution and the unused cycle fees would be returned to the treasury for future use.
  * This could be achieved either manually by sending a fixed amount to the fee pool, or by making a change to the smart contract.
    * The more added to the smart contract the more complex it becomes. It would be preferable to keep the smart contracts simple.
  * This current proposal is simply a poll to gather sentiment
* There are plans in the next update to allow proposals to issue funds to an alternate account. This means that the proposal could do more than just pay out funds.
  * A proposal could execute transactions.
    * A transaction could mean sending tokens to an alternate account or to a testing contract or a locked contract or to go to the fee pool.

Open Source Grant for work previously completed by DJSTRIKANOVA, set through multiple proposals P52-P63. It is important to read P52 carefully to understand the concept of what is being asked through the 12 proposals. [https://dao.effect.network/proposals/52](https://dao.effect.network/proposals/52) Status: Pending

* The last proposal that this is readdressing was very close, had DJ not abstained it would have passed, so it was really split.
  * DJ abstained because he feels his holding are very high and would sway the vote.
* This proposal has changed from the last one in that this time he is asking for a grant for everything he has done so far. The last proposal was specifically for the calculator.
* This proposal framework is really designed to be completed in order. Hopefully, people follow the instructions and vote in the proper order. So anyone voting yes to the 7th proposal, should also be voting yes in every prior proposal. Otherwise, this might not work.
  * This is a first attempt at multi-option vote. This is a way for selecting a baseline amount that people are willing to give, if done in order, at some point the no votes will become the majority, thereby establishing the base amount the DAO is willing to grant.
* This leads to working out a way to have proposals with variable choices for voting options.
* Understanding of Grant vs. Invoice.
  * Invoice – a job is done, there is an amount charged for the job done.
  * Grant – an amount given for a skill/talent in a set context or in recognition for accomplishments. There may or may not be stipulations on how a grant may be spent, but is usually given to be used in a particular context or purpose.

Weekly DAO Call – Seeking equitable Weekly DAO Call Times [https://dao.effect.network/proposals/66](https://dao.effect.network/proposals/66) Status: Pending

DAO Call Recorder June ‘invoice’ request [https://dao.effect.network/proposals/65](https://dao.effect.network/proposals/65) Status: Pending

* Food for thought: Recent discussions with the community bring up an idea to have the DAO decide what they want to pay for the roles of responsibility. In the form of an employer/employee relationship.
  * The DAO creates an employment contract where there is a fixed pay amount (per hour or contract salary) attached to the role that someone will agree to work for. If there is no one willing to agree to work for that pay, then the DAO would need to consider increasing the pay amount.
* Making proposals with an ask price should be enough though, the DAO will vote to agree or disagree.
* Depending upon where a DAO member comes from their perspective upon what is a reasonable pay is will differ. People from more affluent countries will tend to agree to higher ask prices.

Integrate My Calculator With The Effect DAO Dashboard [https://dao.effect.network/proposals/51](https://dao.effect.network/proposals/51) Status: Active, Vote: No‌

* Proposals 52-63 are in response to finding out just how much the DAO would be willing to pay out.
* It is important for the DAO to really understand just how important the developers are to the future of the project. Developers will need to be paid out reasonable fees (reasonable to the developer) to attract and hold onto their talents.
* Once network fees begin to come in, it should be easier to see how important developers are to increasing network fees.

**QUESTIONS/DISCUSSIONS FOR/WITH TEAM:**

* Proposal Flexibility Solutions:
  * 12 proposals, asking 25K each proposal to consecutively find out what the DAO will accept. Re: calculator/dev costs
    * Providing multiple proposals to determine a level of support is one way to go about it, but not a convenient way.
    * Prevents price haggling over multiple cycles.
  * Imbedded polls
    * This is one way to find out more specific information. Will find out if this is effective. Will people engage in the poll?
  * Other?
  * There is a great amount of proposals currently, this is an experiment to see if there are any problems with many proposals present, especially regarding resources.
  * The ram for casting a vote in the DAO should be free after a while. This still needs to be added, but there should be an accumulation of ram available after a while, so it should become free. This still needs to be implemented.
* Role of Responsibility: Treasurer
  * A treasurer is an important role, but is the need for one now?
  * Is it possible to taper down the volatility of EFX.
    * A treasurer could help with volatility
    * Mikel is working on liquidity which should help with volatility.
  * This might be a waiting period while we wait on liquidity improvements, the SDK, and additional developers coming in.
* The swap tool is available, The Bridge will be open sourced on GitHub (should be this week).
  * So it could be integrated into the dashboard so that the dashboard becomes a fully integrated location for all things EFX.
  * If we go ahead with building out the Master Chef contract then this should be in the same location as well.
    * It would be really beneficial to have everything available in one place.
    * There are three smart contract interfaces:
      * Effect Force, Effect DAO Dashboard, The Bridge
    * Perhaps the liquidity interface and bridge could live on the DAO Dashboard.
* The migration of Effect Force over to BSC is progressing nicely.
  * We are building out the SDK and the new account system and it will be released as a testnet version this month in a blog post.
  * This will be the first SDK and will be a basic version that will allow people to get started.
* Discuss a system to subsidize or support resource fees for DAO members.
* Is there API available on GitHub for team created swap tools and other interface tools?

**LIQUIDITY INCENTIVIZATION/VOLUME:**

* Is the foundation interested in getting involved in liquidity?
  * Yes, there is interest from the foundation to contribute to liquidity, but there are no numbers yet.
  * This will likely be on the upcoming proposal.
* CMC, CoinGecko, etc, BSC for EFX is not listed yet. What needs to happen yet for getting this listed?
  * To have an official logo on the BSC Scan the volume needs to increase the amount of token holders to about 3000-5000.
    * This will be increased as workers switch over to BSC.
  * Jesse is not certain about what is required to update CMC or CoinGecko
* Would increasing liquidity volume on BSC increase the likelihood of being whitelisted for Vigor Protocol? (Defi on EOS)
  * Jesse has been on their DAO call with them a few times. They are still working on testing it and building tech.
    * There might be some good features that would be worth accessing.
    * There might be stable coins that could be paired with in Vigor that would be EOS based.
  * Previously, EFX won a competition to be listed with them. This was never really developed further.
  * The question might be what does Vigor need from us before they will list us
    * What would be our next steps?
  * Community member Lennie is really involved in Vigor and will look into what needs to happen with EFX for it to be listed with Vigor.
* Would it be worthwhile actively accessing more exchange options, even if not peer 1 or 2 levels?
  * So long as we have more volume, more exchanges will not help. Having too many exchanges could lead to lower prices over the exchanges. This could do more harm than good.

**HACK-A-THON:**

* Updates: None at this time.
* Question for Chris:
  * Chris announced a prize pool of 50k, but did not specify if this was dollars or EFX.
    * Was this amount random? Was there discussions about this?

**OPEN DISCUSSION:**

* Why are people still not satisfied with the AMA answer given about the NEO swap to the 5 accounts as quick access for the Market Maker to avoid a pump and dump?
  * The transactions make sense in light of a Market Maker requiring quick access to funds to help stabilize the EFX. It makes sense why the transactions happened as they did.
  * What doesn’t make sense is why a pump would be stifled to avoid a dump during a bull period when people are expecting a pump to occur. A crash is expected after a bull run.
  * What would be expected is that they sell the pump, but then use the funds to then prevent a big dump. But the token has dumped a significant amount.
  * When you transfer a large amount of EFX into KuCoin you cannot prevent a drop in value because the only solution that could work is to transfer or swap the EFX to any other currency to then buy the EFX back to stabilize, which is useless without \[?]. The amount of EFX sent to KuCoin was not an amount sufficient to stabilize the price. It really wasn’t clear what this transaction was for, but it seems clear to many that this was not an amount intended to stabilize the price.
* Should rewards given to the DAO members be issued in NFX (the governance token) and not EFX (the worker token)?
  * There isn’t really any NFX available. The DAO doesn’t hold NFX. The Foundation doesn’t have many.
  * The rewards for the DAO are really coming from the network fees, which is essentially a tax paid for using TEN.
    * So the greater the amount of network fees the greater the amount of rewards.
  * The EFX given out of the leftover cycle budget isn’t part of the original design intention.
    * This remaining cycle budget really should cease to be used for rewards once the network fees are automatically flowing. It really only serves as a ‘placeholder’ until the network fees are automatically flowing into the fee pool.
    * The full cycle budget should be tapped into development to increased the amount of dApps using the network and thereby increasing the network fees going into the fee pool for distribution.
* One idea is to have the translation services open to developers to make use of these services.
  * When the SDK is done accessing the workers for translations should be open source for developers to tap into for their own purposes. This is our understanding, but this could be confirmed.
  * Once this is open source, the DAO could look into marketing to developers.
  * Effect Captions is available for independent use.
  * In the meantime, contacting the team for them to work with developers to have what is needed designed and built is the way to go.

**OLD DISCUSSIONS** (tabled)

* Alternating times for DAO Calls to allow for greater participation.
  * Proposal in place.
* Discuss further with team about incorporating worker pay in perpetuity of trained algorithms.
* Reporting of sub-groups to the weekly calls.
  * Suggestions:
    * Define exactly what the HG’s role is,
      * this should be visible on the blockchain and on the dashboard, in the smart contract
    * Elect new members
    * Make use of GitBook
* Has there been any updates to this that can be shared?

**Potential Proposals:**

* How to become a guardian guide
* Using Effect Captions to update community made guide videos. Especially videos with lasting relevance. Could be used to promote Effect Captions.
  * Would need to include the quoted price points in the proposal
  * What languages would be prudent to put into the closed captions
    * English only would be about $20
* ~~Developer costs for dashboard improvements~~
  * ~~The community developer group~~
  * ~~There will likely be a proposal mapped out with multiple phases.~~
  * ~~Before the proposal is put forth they need to decide how to arrange for taxes and other dynamics related to payments~~
  * ~~Proposal for opensource the product~~
* Timeline
* Proposals to the Foundation:
  * DAO Store start-up expenses
  * Hack-a-thon expenses

‌

‌

**Tasks**:

1. Vigor inquiry
2. Time zone proposal
3. Dashboard updates:
   1. Reward calculator (P30)
   2. Timeline
   3. Token Flow Map
   4. Worker of the Week into DAO dashboard (P29)
4. Ambassador TEAM google Drive
   1. Discuss decentralized options or to create an interface to access IFPS storage
5. GitBook:
   1. &#x20;Guide on how to become a guardian
