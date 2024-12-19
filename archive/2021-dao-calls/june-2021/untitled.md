# DAO CAll - June 2, 2021

![Text

Description automatically generated with medium confidence](<../../../.gitbook/assets/0 (7).png>)**Agenda,** Weekly DAO Call, June 2, 2021

**Team in Attendance**: Jesse

**Members in Attendance:** @ce, Alan, Bree, DavidB, DJSTRIKANOVA, Rochelle, splottingham, Vincent Calduch

**Roles:**

Call Moderator: Bree

Recorder: Bree

Proposal Tracker: TBA

**ANNOUNCEMENTS**:

Thanks to the community developer team for updating and filtering the proposals. Looks really clean and the coloured tags are very helpful.

Great appreciation for the community developers stepping up to learn and actively contribute. This is really helpful for the team, as it is easier to build the SDK when there is active interest.

Dynamic rewards/votes P22 to start June 4, 2021.

**Questions/Discussion** (with/for Team)**:**

Technology:

* How are things progressing with the SDK? (P16)
  * Will the SDK be written up in enough detail to enable developers flexibility in their designs?
  * Will the SDK provide ample structure/information for both front-end and back-end developers?
    * A lot of work is still needed before it will be ready for release, there are many small steps that need to be done.
    * There should be an update every week, starting as soon as P22 is implemented.
    * It is difficult to frame it ATM, there will be a small roadmap released, some websites, and there is also the Gitbook. But it is also dynamic, things will grow as we go along.
  * Are there any potential developers you are working with to see what type of use cases they are interested in? To work with a developer to see what they are thinking and what would help to inform the SDK?
    * We are open to working with developers to this end.
    * The priority is making sure the bare minimum are in place in the SDK, but there will be more that will be added and developed as progress is made.
  * EOS calls do not seem to be too difficult, there is a hope that the SDK will really focus on allowing things to become more decentralized. To be able to pull off some jobs for workers in an easy way.
    * We are trying to make the SDK more decentralized, which means authenticating with your wallet and making sure that you can post a task using only blockchain technology. This will be one of the first phases to get done. This is already in the works.
    * Backend and frontend templates exist already and need to have some reconfiguration. We already have some of this done.
      * This will work to flexibility. there will be the ability for developers to DIY  and there will be templates for those needing predeveloped structure.
* What is the smart contract address for the trading bot. (need to confirm that it is translate.ai) Are there other team bot accounts? (P30, PP)
  * The question is a bit confusing. There is no trading bot account, per sae.
  * translate.ai is not a trading bot account. translate.ai collects the funds from translation requesters and issues them to translators. We are moving away from PayPal.
  * The main account for paying workers is efxrequester. This account receives funds from various sources. This is the main account used for collecting from requesters to give to workers.
    * In the past each requester had their own account, but this did not work well at the time and so it was consolidated into this one account. (efxrequester)
    * Once fully decentralized, each requester should have their own account.
  * People are concerned about the flow of tokens. It would be really good to have a visualization of where the tokens are coming from. How and where is efxrequester getting their tokens from? There is a fee pool where the network fees and other DAO rewards pool, it would be good to see where everything is coming from. To show how and where the requester is getting their EFX from.
    * Right now, there is no real SDK, it is in development.  At this time the efxrequester is really the only account attached to the dApps on Effect Network, as there are no other external dApps. This account receives from various sources. Once the SDK is done there will be more requester accounts. The goals is one account per dApp. Each dApp's transactions on TEN will be able to be seen on the blockchain.
    * When we have the basic SDK first version, then anyone will be able to create an account that will feed tasks into Effect Force.&#x20;
    * A Token Flow Map would really show the activity on the Force. A Token Flow Map could be created by the team, not necessarily a proposal. Jesse will discuss with us later to get a good idea of what we are thinking.&#x20;
* Will it be possible to integrate an EFX payment directly into GitHub, for developers completing tickets?&#x20;
  *   So instead of contributors creating DAO proposals requesting payment for each ticket on GitHub that community developers complete. Some tickets on GitHub are simple enough to do in spare time, some require significant work. It isn't efficient to wait on each proposal to cycle through in order to pay for the ticket completion.&#x20;

      That perhaps there could be a mechanism to directly payout upon the completion of the task imbedded in GitHub. To provide efficiency.&#x20;

      * There are other projects that are doing something similar (Colony) integrating in GitHub. Unsure how to do this without creating significant infrastructure.&#x20;
      * Perhaps each ticket could have a suggested value amount assigned for how much each ticket is worth.&#x20;
      * Perhaps a proposal could be put forth that gives Jesse and Laurens a budget from which they can make small payouts to fairly cover the work for these tickets.&#x20;
* So now that we have the ptokens on BSC is there any plan to have NFX as a ptoken?&#x20;
  * Maybe, it could make sense. NFX is more related to governance. At this time it doesn't make sense to do this, but if people come up with really good reasons to do this it should be really easy to do now.&#x20;
* As a member of the team, what are your thoughts on the workers getting paid in perpetuity for any task that the AI can now do alone?&#x20;
  * This is a really epic idea! This is in line with the fundamental philosophy of the project.  Effect Force is sort of an algorithm with a human in a box. You have your inputs and outputs that resemble an algorithm, and we can see in the future a lot of these boxes being replaced by machines.&#x20;
  * It's going back to when Bill Gates thought to tax algorithms and pay people from the tax collected. We do not have that right now going on. Our clients own these algorithm, so we do not have control over these.&#x20;
  * There have been many clients that have disappeared because they have trained their algorithms and the AI no longer needs learning.&#x20;
  * The idea is that Effect Network should incorporate when the algorithm is finished be also included in Effect Network, so that we can also see when the algorithm is finished, how much it is doing, how much input the workers had.&#x20;
  * Will keep this on the table for future discussions.&#x20;

Reward distribution:

* How will the rewards from BSC liquidity be taken and distributed to the DAO?
  * This week's Ask Effect questions answers this questions.&#x20;
  * The current liquidity in Pancake Swap comes from Effect Network. Any rewards generated will go into the fee pool, which are currently generated by the trading fees, which right now is just the basic liquidity pool. The only fees that are being generated are the trading fees. A small percentage of every trade goes into the the pool, but because we own the LP tokens there is some fees being generated.  Because these fees are a mix of BNB and EFX this will need to be done manually. They will go periodically every 2 or 4 weeks, this is not fixed yet. This will go into the fee pool of the DAO, where the rewards are currently coming from. So this does mean you will need to be voting to receive the rewards.
* Will there be farming on Pancake Swap?&#x20;
  * To set up farming/syrup pools is not just as simple as applying or paying an 'entrance' fee. Pancake swap is very particular about which tokens become part of these pools. There is a rather large incentive that needs to go with it. &#x20;
    * To be on the farm you need to first be on a syrup pool.&#x20;
    * The team would love to be in a syrup pool and a farm. There isn't too much that can be said at this time, but this is a goal for the team.&#x20;
* What is the scalability of P22? Reliably how many users could vote in one cycle?
  * there were many tests done on this.&#x20;
  * Technically there are only 10M NFX in supply, so if everyone held only 1 NFX that is the max amount of voters.&#x20;
    * There are plenty of EFX to cover any supply of NFX.
    * There shouldn't be any level of problems with this spread.
* There is a possibility that the smaller users could be priced out of their voting due to the resources required for making the transaction.&#x20;
  * There could be a system developed to create EOS power for DAO members to subsidise or fuel DAO related transactions.&#x20;
    * providing liquidity to Defibox and the rewards going into eospowerup
    * The EOS technology is annoying for newcomers, but once you learn it, it is so flexible and accessible for developers.&#x20;
    * it would be an encouragement to stake if there were a mechanism or system in place to give the members a shared pools of fees to go to EOS resources, this might filter into other EOS transactions.

Token Map:

* The token map on DAO dashboard no longer shows the x.efx account. This account is showing increased activity lately.
  * What is the reason for this account being removed from the token map?
    * This might be an oversight, will have a look at the map and update it.&#x20;
  * The tokens got swapped from NEO to the foundation EOS account, afterward there was some redesigns of account purpose.&#x20;
    * The efx account and the bsc.efx accounts are the two foundation accounts.
    * The e.efx account is the operational account for the foundation.&#x20;
* The foundation tokens say they are locked, but clearly they are not locked because 100m tokens was moved out of the foundation account into liquidity/partnerships.
  * There is not an official time lock on it. There is no set purpose or plan for these token should do. So they will be out of use until there is a definite plan for them. These are leftover from the total token supply and will remain on reserve. There may be a point where the project really needs them, but there is no specific date.&#x20;
  * It may be prudent to have a short explanation on the Token Map that states what these tokens are. &#x20;
* 12M EFX went to the Pancake Swap liquidity and do you plan for the other 88M to be for partnerships on Binance Smart Chain?
  * What is your definition of a partnership?&#x20;
    * A partnership must be very valuable to the project and must be made public, what it is or who it is.
  * Primarily there is Pancake Swap where a healthy liquidity is important.&#x20;
    * There may be other ways to keep the pool healthy without tapping only on to this account.&#x20;
    * There will be a proposal soon, as a result of discussions on the high guard that will help contribute to the BSC liquidity pool. This will be a kind of incentivization for people to put liquidity into the pool.&#x20;
  * For the Pancake Swap BSC side, we might not need that many tokens, but we are not 100% sure. Chris might have a better idea.
  * The 88M are reserved for partnerships on BSC, and for marketing for liquidity.&#x20;
    * It makes sense to use the foundation tokens for liquidity.
      * Who are those partnerships with?&#x20;
      * Chris is a better person to speak with partnerships about.&#x20;
        * PTokens?
        * Other?
    * Marketing:&#x20;
      * There are community and team members who think we can be doing much better with marketing, and there is a budget for it. There are many ideas about how to do this.&#x20;
      * This budget is there to help make Effect Network better.&#x20;
      * This is something for the AMA and for Chris to address. &#x20;
  * The main take away is to update the Token Map
    * Suggested that the Token Map is written up in a Medium article (suggested that Jesse write it up.)
    * This then could be integrated into the DAO dashboard.
    * Gitbook may also be able to be integrated into the dashboard.

Organization:

* Effect Network, Effect DAO, Effect.AI BV, and Effect Foundation are all distinct, but tied to each other.
  * There are many new members, and there is confusion among member who have been involved for a while, about what each are and how they are distinctly different from each other and how they are connected and work together.
  * These entities need to be explicitly delineated. This is not specifically DAO related, but there is overlap though as the DAO needs to be clearly defined on what it’s role is and what it can grow into.&#x20;
    * The DAO really are the guardians of the treasury.&#x20;
      * So anything to protect or build the treasury
    * The Foundation is the entity that performed the initial token sales, it raised the funds and are the guardian of those tokens.
      * they determine where those tokens are distributed to.&#x20;
        * for example the amount reserved for the future
      * the smart contracts that are powering the network are also managed by the foundation
    * the DAO is new, but in time more of those responsibilities will be moved over the the DAO for guardianship.
      * with the authority over the staking contract
      * This is both exciting and scary
      * presently and initially the proposals on the DAO is intended to give out funding to strengthen TEN.&#x20;
      * but increasingly having more authority to change smart contracts
  * The primary goal before moving to full decentralization will be to increase the numbers and have enough developers involved to be able to manage any technical requirements.
  * We also need to be very careful to avoid abuses. The high guard is an important safeguard for now, but this is only intended to be a temporary protection.
  * The DAO treasury is intended to last about 10 years to promote development on TEN. So the DAO also needs to work toward building a nice economy.&#x20;

Competition:

* How is Effect Network different and better than Cryptotask? [http://about.cryptotask.org](http://about.cryptotask.org/)
  * Similar to Fivver?
* What is the plan for managing competition as other projects with similar outputs arise?
* What role could the DAO have in countering competition?



**Proposals** (Active, Pending, and Newly added)**:**

**UPDATED Effect DAO E-Commerce Store**  [http://dao.effect.network/proposals/2](http://dao.effect.network/proposals/2)  Status: Draft.            There is a .pdf to read through for feedback. Please give this a read through.

* Suggestion to go with option B for payment options. This would include EOS and would be the closest to using EFX as is possible at this time.&#x20;
* Some day it will be ideal to have an EFX option, but this is not possible right now.&#x20;
  * Community developers are looking into solutions.
* Proposal is looking good.

**Proposal Tracker Term C13 through the end of C20** [http://dao.effect.network/proposals/46](http://dao.effect.network/proposals/46)  Status: Pending

**DAO Gitbook Proposal Tracker** [https://dao.effect.network/proposals/45](https://dao.effect.network/proposals/45)  Status: Pending

* What about tying the ask to a $ amount? Then the EFX amount would be adjusted to the current price in dollars.
  * This would required an oracle and it is very tricky. There have been discussions with EOS Titan. They can make EOS into the Delphi oracle, but it is a bit dangerous because there can be security breaks and oracles are centralized, so this becomes risky.&#x20;
  * The price fluctuation with an oracle is 1 hour, and without the oracle things are much more simple. There is risk of token price fluctuation that could have an impact upon voting results if the token goes up significantly enough to make the ask too expensive by the time of vote closing.&#x20;

**DAO GitBook Write-Up Consolidation** [http://dao.effect.network/proposals/42](http://dao.effect.network/proposals/42) Status: Processing, Vote: Yes

**Deployment of Dynamic Rankless Vote System (P22)** [https://dao.effect.network/proposals/43](https://dao.effect.network/proposals/43)  Status: Processing, Vote: Yes

* P22 has had a lot of stress tests and security tests. It does work and it will be ready for June 4.&#x20;
* Scalability: see aforementioned&#x20;
* Could an interactive distribution chart be added to the dashboard?
  * Could zoom in and click on an account name and be taken to their profile

**DAO Call Recorder**  [https://dao.effect.network/proposals/44](https://dao.effect.network/proposals/44) Status: Processing, Vote: Yes

**Potential Proposals:**

* Using Effect Captions to update community made guide videos. Especially videos with lasting relevance. Could be used to promote Effect Captions.
  * Would need to include the quoted price points in the proposal
  * What languages would be prudent to put into the closed captions
    * English only would be about $20
* Roles of responsibility (with compensation)
  * Define role: Recording secretary
  * Define role: Proposal tracker - proposal has been created for this role.
* Developer costs for dashboard improvements
  * The community developer group
  * There will likely be a proposal mapped out with multiple phases.
  * Before the proposal is put forth they need to decide how to arrange for taxes and other dynamics related to payments
  * Proposal for opensource the product
* Timeline

**Open Discussion:**

* Discuss the potential for Proposal #3 Effect Design.
* DAO dashboard profile image.
  * Anyone else having problems adding an avatar?
  * Avatar.pixios.art try to create in this place, then have Laurens update dashboard
* A small group to organize an ‘interview’ event with the team to go over some of the non-DAO questions

**Tasks**:

1. Discuss further with team about incorporating worker pay in perpetuity of trained algorithms.
2. Discuss a system to subsidize or support resource fees for DAO members.
3. Dashboard updates:
   1. Reward calculator (P30)
   2. Timeline
   3. Token Flow Map
   4. Worker of the Week into DAO dashboard (P29)
   5. ~~Archival/filter system for proposals~~
4. Create a sub-group for brain storming. – attendees not yet enough to warrant a smaller group
5. Ambassador TEAM google Drive
   1. ~~Update to be a storage for the DAO completed~~
   2. Discuss decentralized options or to create an interface to access IFPS storage
   3. Create a document to start developing role descriptions
      1. Secretary role expectations.
      2. ~~Proposal Tracker role expectations~~
