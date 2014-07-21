The Precedent Protocol Whitepaper
===================================

A Decentralized Autonomous Legal Procedure Organization<br><br>
Incentivizing arbitrators and parties to voluntarily opt for publication of arbitral outcomes and rewarding both arbitrators and parties for their participation in precedential matters.

Bootstrapping a million new legal systems, one precedent at a time.

"Only polycentric law can keep up with that most polycentric of networks, the Internet." - Tom. W. Bell, Polycentric Law in the New Millennium 







##Table of Contents

1. [Background & Introduction](#background-&-introduction)

2. [Proof of Precedent (PoP)](#proof-of-precedent-(PoP))

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. [Roles](#roles)

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. [Bonding Process](#bonding-process)
 
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. [Fee Structure](#fee-structure)
 
3. [Consensus](#consensus)

4. [Reward Schedule](#reward-schedule)

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. [Publication Reward](#publication-reward)

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. [Citation Reward](#citation-reward)
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i. [Precedents as Assets](#precedents-as-assets)
 
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ii. [Exchange](#exchange)
 
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;iii. [Burn-for-Authority](#burn-for-authority)
   
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. [Supply & Initial Distribution](#supply-&-initial-distribution)
 
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. [Demand for PrecedentCoin](#demand-for-precedentcoin)

5. [Considerations](#considerations)

6. [Implications & Outcomes](#implications-&-outcomes)

7. [Conclusion](#conclusion)

8. [Glossary](#glossary)

9. [Appendix](#appendix)



<a name="background-&-introduction">
###Background & Introduction

Law has been described as “the enterprise of subjecting human conduct to the governance of rules. Unlike most modern theories of law, this view treats law as an activity and regards a legal system as the product of a sustained purposive effort.” 

Todays judicial systems lack price discovery for the voluntary publication and citation of judicial outcomes.  Publication and dissemination of judicial outcomes, like many public goods, suffers from the free rider problem: wherein producers of public goods (precedents) are not compensated by those consuming them. Judicial outcomes and their publication have long been primarily the domain of the state; however, innovations in cryptocurrency and blockchain technology now give anyone the ability to fund the publication and citation of precedential matters, thereby forming the basis for a decentralized, voluntary polycentric legal order. 

The Precedent Protocol is strictly concerned with the justiciability of the dispute in question and is wholly agnostic to the justness or fairness of the outcome. Users dictate what it means for a dispute to be justiciable, and can fork the protocol if new standards are deemed preferable.
 
The goal of any legal system is to provide for just outcomes and certainty through  predictability of relief from injury. Incentivizing publication of precedents and imposing a price mechanism for their citation makes this goal more attainable than ever before. 

<a name="proof-of-preceent-(PoP)">
###Proof of Precedent (PoP)

Proof of Precedent is the successful demonstration of a justiciable, bona fide dispute, and its subsequent publication for possible citation in future disputes. PrecedentCoins are the incentivization mechanism underlying the Precedent Protocol, rewarding arbitrators and parties for the publication of precedents, thus contributing to the development of a body of polycentric common law. To amplify the value of publication, the protocol tokenizes published precedents, the value of which is determined by said precedent’s utility, clarity, and persuasiveness. 

As a preliminary matter, a user can take on one of four roles at any given time when using the Precedent Protocol:

<a name="roles">
###ROLES

POSSESSOR - An individual who possesses PrecedentCoin without posting a deposit bond.

WITNESS - An individual who has posted a deposit bond and may periodically vote on the justiciability of OPINIONS.

PARTY - An individual who has posted a deposit bond, who has previously entered into an contract which stipulates the use of the Precedent Protocol and is now in dispute. 

ARBITRATOR - An individual who has posted a deposit bond, and adjudicates a dispute per the Precedent Protocol. 

<a name="bonding-process">
###Bonding Process

Implementation: 
Bitcoin Contracts: Deposit Bonds
Distributed Oracles System for Cryptocurrency Contracts
Donations as Bonds

A POSSESSOR submits a deposit bond, agreeing that the deposit bond will be released by the protocol at some time in the future (this is a variable within the open source Precedent Protocol and will need extensive real-world testing). The cost of the bond and the time in which value is inaccessible to both the user and the protocol is the primary means through which bad actors are discouraged for generating spurious OPINIONS and DECISIONS.

1. POSSESSOR agrees to a deposit bond with the following terms: 1 BTC for a six month term. The POSSESSOR becomes a WITNESS, ARBITRATOR, or PARTY upon the deposit bonds verification by the Precedent Protocol. The following scenarios describe how REPUTATION affects bonding requirements.  

a. WITNESSES revert to being POSSESSORS in the event that their reputation falls below the threshold requirements for their Precedent Protocol verified deposit bond. Former WITNESSES will no longer be able to vote after reverting to POSSESSOR status without having met the additional bonding requirements.  

b. When a WITNESS votes with the majority, their REPUTATION improves and no new deposit bonding requirements are imposed.

Deposit Bonding terms cannot be extended ad hoc. Even in the event of the imposition of additional bonding requirements, the term of the original deposit bond remains intact.

The protocol recognizes when a particular pubkey has entered into a deposit bond contract with the protocol. If a user’s reputation begins to wane, the protocol will impose a greater deposit bond requirement for the duration of the prior bond contract, this is referred to as the PENALTY. 

BAMin is predetermined by the protocol
P = PENALTY ; and is predetermined by the protocol <br><br>
BACur = Current Bond
<br><br>
BARequired = BAMin  BACur | R For some WITNESS at WE sub n  5<br>

else<br>

BACur + [ BAMin  * [% P *  ( 5-R ) ] ]<br>

<a name="fee-structure">
###Fee Structure

Theory: PARTIES must compensate both ARBITRATORS and WITNESSES to fully decentralize the cost of PoP.  ARBITRATORS depend on WITNESSES to arrive at a determination as to the occurrence of PoP, which triggers the ARBITRATORS’ publication reward.  PARTIES are reimbursed the protocol fees they paid at the outset (as opposed to accepting some larger portion of the publication reward), and they will be owners of the resulting PRECEDENT ASSET.  

Minimum fee requirements are instituted to create an incentive compatible system.   PARTIES pay two equal minimum “deposits” to ARBITRATOR and WITNESSES (ultimately the fee is equally distributed among WITNESSES). 

WITNESSES keep deposit when CONSENSUS is achieved; the WITNESSING EVENT must result in either AFFIRMATIVE or NOT AFFIRMATIVE.  

Arbitrators maintain possession of the deposits when an OPINION is created, pending justiciability determination at the WITNESSING EVENT.  

PARTIES are reimbursed their fees in the form of a protocol reward if Proof of Precedent is satisfied (AFFIRMATIVE, a DECISION is reached and published).

<a name="consensus">
###Consensus

The Precedent Protocol achieves consensus via a voting mechanism (e.g. see Mastercoin Stake Weighted Voting) wherein a group of WITNESSES vote as to what constitutes a bona fide precedent. A given WITNESS’ reputation is enhanced for voting with the majority and adversely affected for voting in the minority. Deposit bonding requirements are increased for users who accumulate a negative reputation lower than the threshold.

(Threshold REPUTATION = 5 in the example)
Y - A vote by a witness for AFFIRMATIVE
N - A vote by a witness for NOT AFFIRMATIVE
A - AFFIRMATIVE
NA - NOT AFFIRMATIVE
R - Reputation 
WE - WITNESSING EVENT
      
R For some WITNESS at WE sub n = 5  +/-  R at WE sub 1R at WE sub n -1  { [ Y | A + N | NA ] - [ Y | NA + N | A ] }   

CONSENSUS - is the required outcome for completion of the WITNESSING EVENT.*
CA = if (AFFIRMATIVE > NOT AFFIRMATIVE,  O → D , O )
CNA = if (NOT AFFIRMATIVE > AFFIRMATIVE, O → O , null)

PoP = CA ; and publication, as determined by the protocol


e.g. One WITNESSING EVENT is voted as follows:

Bond Amt. = BA (min.= 1, max.= 10) in BTC 
Bond Time = T (min.= 0.5, max.= 10) in Years
Reputation = R (1-10, min. needed to vote w/o addt’l bond requirements = 5)
*Normalized Values

| BA   | T   | R  | BA*   | T*   | R*  | Y | N | i     | i(y)  | i(n) |
|------|-----|----|-------|------|-----|---|---|-------|-------|------|
| 1    | 0.5 | 5  | 0.1   | 0.05 | 0.5 | 1 | 0 | 0.65  | 0.65  | 0    |
| 2    | 1   | 5  | 0.2   | 0.1  | 0.5 | 1 | 0 | 0.8   | 0.8   | 0    |
| 1.5  | 2   | 6  | 0.15  | 0.2  | 0.6 | 1 | 0 | 0.95  | 0.95  | 0    |
| 1.25 | 10  | 5  | 0.125 | 1    | 0.5 | 1 | 0 | 1.625 | 1.625 | 0    |
| 2.25 | 5   | 8  | 0.225 | 0.5  | 0.8 | 1 | 0 | 1.525 | 1.525 | 0    |
| 3    | 4   | 5  | 0.3   | 0.4  | 0.5 | 0 | 1 | 1.2   | 0     | 1.2  |
| *1.9 | 3   | *4 | 0.19  | 0.3  | 0.4 | 1 | 0 | 0.89  | 0.89  | 0    |
| 5    | 2   | 5  | 0.5   | 0.2  | 0.5 | 0 | 1 | 1.2   | 0     | 1.2  |
| 5    | 1   | 7  | 0.5   | 0.1  | 0.7 | 0 | 1 | 1.3   | 0     | 1.3  |
| 1    | 0.5 | 5  | 0.1   | 0.05 | 0.5 | 0 | 1 | 0.65  | 0     | 0.65 |
| 1    | 0.5 | 5  | 0.1   | 0.05 | 0.5 | 0 | 1 | 0.65  | 0     | 0.65 |
|      |     |    |       |      |     |   |   |       | 6.44  |      |
|      |     |    |       |      |     |   |   |       |       | 5    |

AFFIRMATIVE = 6.44<br>
NOT AFFIRMATIVE = 5<br>
CA is achieved.<br>

*CONSENSUS is the goal of the WITNESSING EVENT.  Constraints may be built into the protocol which would result in NON-CONSENSUS, requiring “re-voting”. 

<a name="reward-schedule">
###Reward Schedule

M = 264 - 1<br>
Block reward = (M - A) / 220 / 1012, where A = current circulation.

<a name="publication">
###Publication Reward

Publication must occur in a manner that is freely and easily accessible by anyone.

ARBITRATORS are rewarded with a number of PrecedentCoins for OPINIONS which meet the requirements for Proof of Precedent (PoP), thus becoming DECISIONS. 

PARTIES are rewarded (reimbursed) the minimum fee (denominated in PrecedentCoin) which was required as part of the ARBITRATORS fee. 

<a name="citation-reward">
###Citation Reward

To further incentivize both parties and arbitrators to be active participants in the protocol, when arbitrators cite old precedents which adhere to the Precedent Protocol, the network compensates the original ARBITRATOR and PARTIES with PrecedentCoins, on a predictable, decaying schedule.

Citations are accomplished using in text cites to Precedent CASE NUMBERS, which are tied to both the pubkey of the original ARBITRATOR, and the pubkeys of the original PARTIES whom were responsible for the production of the cited DECISION.

C = Citation
CN = CASE NUMBER 

CREWARD for some PARTIES,ARBITRATORS = PoPCur | CN0 → Cur-1 |  CN0 → Cur-1 < count_CREWARD = 250

PubREWARD for some PARTIES, ARBITRATOR = CNCur ; as defined by the protocol and PARTIES returned original fee 

Please refer to Diagram 1 or a depiction of this mechanism.

<a name="supply-&-initial-distribution">
###Supply & Initial Distribution

There will be a bitcoin crowdfund which will create a total number of PrecedentCoins base on the following factor

BTC X * 1,000,000

Total Number of PrecedentCoin     - X

First Pool of Arbitrators         - 0.05X
Kickstarter Pre-Sale               - 0.15X
Publication & Citation Rewards            - 0.8X 


First Pool of Arbitrators 

Arbitrators will be able to submit a pubkey during the kickstarter period in order to be awarded these PrecedentCoins. Must prove that they have been an arbitrator for T period of time.

<a name="demand">
###Demand for PrecedentCoin

1. PARTIES are required to pay PrecedentCoin to ARBITRATORS who are participating in the Precedent Protocol.
2. ARBITRATORS who publish their opinions in a uniform and predictable manner.
3. ARBITRATORS who support a body of polycentric law and those fellow arbitrators producing it.
4. Individuals who merely possess PrecedentCoin and desire to support a body of polycentric law and those ARBITRATORS producing it.

<a name="considerations">
###Considerations

Q: What happens when all of the PrecedentCoins have been distributed?
A: Fee-based

Q: Does the Precedent Protocol discourage the settlement of disputes.
A: No, the Precedent Protocol does not do away with the parties desire, nor the arbitrators willingness to settle a given dispute, and at most will have a de minimus impact on incentives to settle.

Q: What happens when bad actors overtake the network and produce maligned precedents?
A: This will be hugely costly due to bonding reqs/rep. Otherwise fork.

What is being published? How is it being published? What are WITNESSES assenting to and AFFIRMING during the WITNESSING EVENT. What structure, framework, and procedures should the protocol promote? A discussion of the possible requirements of bona fide OPINIONS is taking place here.

What should constitute a valid precedent? Arbitrator must prove that certain procedures were followed in a given OPINION, what procedures? What are other indicia of integrity(justiciability) in this context? 

Software licenses for arbitral OPINIONS? MIT, CC, GPL? Public Domain?

[Publication Requirements - Publish to at least three venues? (MaidSafe, Pastebin, Throww?) Bonus for additional publication?]

Future Development
- Search and Shepardization
- Arbitrator specific coins?
- bitrated.com and trustbit.com integration, Wikipedia ArbCom

<a name="implications-&-outcomes">
###Implications & Outcomes 

The massive success of eLance-oDesk and Guru coupled with the existence of services like Judge.me, Bitrated.com, Trustbit, and Wikipedia ArbCom demonstrate that in the future an ever increasing amount of commerce; and by extension dispute resolution and adjudication will occur online between geographically disparate parties. Further, trustless e-cash systems and anonymous routing schemes dispense with the need for arbitrators, parties, and witnesses to be privy to the identity of those adjudicating and disseminating common law precedents.  


The commoditization of adjudication will help coordinate voluntary action between status quo arbitral processes and the Precendent Protocol, as the Precedent network grows, so to will the incentive to participate.   
smart/self-executing contracts will not eliminate the need for human judgment, reasoning

As open source software, the Precedent Protocol may be forked at any time by anyone. A forking event is indicative of ethical or procedural disagreements with the direction of the protocol, and in which prior precedents are technically and practically obsolete for the fork.

<a name="conclusion">
###Conclusion

We have presented a novel mechanism whereby arbitrators and parties are rewarded for the publication and citation of arbitral decisions. As a low-trust system built atop trustless infrastructures, we have proposed deposit bonding and reputation systems as an attempt to eliminate perverse incentives from the protocol.

<a name="glossary">
###Glossary

DEPOSIT BOND - an amount of value committed by an individual, to the Protocol as inaccessible for an identifiable period of time (See Bonding Process below). 

OPINION (.txt file) - the outcome of a dispute between PARTIES as decided by an ARBITRATOR. This document will detail the procedures, rules, reasoning and logic employed in deciding the legal question at issue.

REPUTATION - the measure of a witness’ proclivity to vote with simple majorities during WITNESSING EVENTS.  

INFLUENCE - a value determined by a WITNESS’ bond amount, bond duration, and REPUTATION, exercised during WITNESSING EVENTS.  INFLUENCE is calculated by the following procedure:
INFLUENCE = ⅓ * (Bond Amount) + ⅓ * (Bond Duration) + ⅓ * REPUTATION

AFFIRMATIVE - The cumulative INFLUENCE voted during the WITNESSING EVENT deeming an OPINION justiciable and bona fide.

NOT AFFIRMATIVE - The cumulative INFLUENCE voted during the WITNESSING EVENT deeming an OPINION non-justiciable and not bona fide. 

WITNESSING EVENT - conclusive determination of the justiciability of the OPINION by the randomly selected WITNESSES. Each WITNESS can deem an OPINION either AFFIRMATIVE or NOT AFFIRMATIVE. An INFLUENCE weighted vote of WITNESSES dictates whether an OPINION is AFFIRMATIVE or NOT AFFIRMATIVE. Only OPINIONS voted in the AFFIRMATIVE become DECISIONS. (At present WITNESSING EVENTS are binary choices). 

DECISION (file) - a justiciable and bona fide OPINION resulting from the WITNESSING EVENT. Following PUBLICATION the ARBITRATOR receives a PROTOCOL REWARD (see reward schedule).
PRECEDENTCOIN - The token used to incentivize ARBITRATORS and PARTIES to publicize arbital outcomes

PUBLICATION REWARD - The PRECEDENTCOINS released by the protocol to ARBITRATORS and PARTIES as a result of an AFFIRMATIVE vote in a WITNESSING EVENT

PRECEDENT ASSET - A set of tokens created upon the submission of an OPINION to the WITNESSING EVENT. The ARBITRATOR and PARTIES agree on the supply and proportional distribution for a given PRECEDENT ASSET prior to the submission of the OPINION to the WITNESSING EVENT. Following an AFFIRMATIVE determination during the WITNESSING EVENT the tokens are distributed to the ARBITRATOR and PARTIES. Following a NOT AFFIRMATIVE determination during the WITNESSING EVENT the tokens are burnt/destroyed.

PRECEDENT EXCHANGE - The mechanism by which PRECEDENT ASSETS are bought and sold. PRECEDENT ASSETS are denominated in PRECEDENTCOIN.

BURN FOR AUTHORITY - The act of an ARBITRATOR burning some amount of a particular PRECEDENT ASSET to effect a citation a prior DECISION.


<a name="appendix">
###Appendix

Selected Excerpts from Benson, The Enterprise of Law: Justice Without the State

Recognition. Recognition of law was based on kinship and contractual reciprocities motivated by the benefits of individual rights and private property. Indeed, a "mental codification of abstract rules" existed, so that legal decisions were part of a "going order"(Benson, Citing Popisil, Anthropology of Law: A Comparative Theory). Grammatical phrases or references to specific customs, precedents, or rules were present in all adjudication decisions that Popisil observed. He concluded: "not only does a legal decision solve a specific case, but it also formulates an ideal - a solution intended to be utilized in a similar situation in the future. The ideal component binds all other members of the group who did not particiapte in the case under consideration. The [adjudicator] himself turns to his previous decisions for consistency. In a way, they also bind him. Lawyers speak in such a case about the binding force of precedent."(Id.)

Externalities and Public Goods

The externality argument for public provision of law and order might be characterized this way, private sector production of law and law enforcement generates external benefits for which private suppliers may be unable to charge. Suppose that a few individuals hire a private security firm to patrol their neighborhood. The patrol deters criminals, both for those who pay the firm and those who do not. Thus, there are strong free-rider incentives at work here. If everyone paid for the benefits received, the firm would patrol more often and prevent more crime; but because individuals can reap benefits without paying, they have strong incentives not to enter into the neighborhood group that hired the firm. Even many strong free market advocates have accepted the validity of this argument.

If there is a significant free-rider problem, it means that too little private sector protection is purchased and produced. The problem arises because individuals cannot be persuaded to cooperate in buying the good or service in question, not because the private sector would not produce it if producers were fully compensated for the benefits that they provide. Professor Richard Epstein concluded:

"In essence the entire system of governance presupposes that in a state of nature there are two, and only two failures of the system of private rights. The first is the inability to control private aggression, to which the police power is the proper response. The second is that voluntary transactions cannot generate the centralized power needed to combat private aggression. There are transaction costs, holdout and free-rider problems that are almost insurmountable when the conduct of a large number of individuals must be organized. To this problem, the proper response is the power to force exchanges upon payment for public use."

This argument has been used to a greater or lesser degree to justify the historical trend of increasing production of such services to supplement or replace private sector production efforts.

**A similar rationale has been made to justify the public provision of courts. Perhaps the most widely claimed external benefit of court decisions is the body of law or precedents that court decisions generate. Mabry, et., for instance, wrote that
    
"the continuous creation of a collection of decisions, interpretations, opinions, and precedents is the production of a collectively consumed service. ... Since they are available to others at no additional cost, precedents are externalities. Indeed the entire set of law known as common law has developed as an external benefit of past adjudication.”

While individuals would be willing to pay for the private benefits they obtain from a private court (e.g. dispute resolution, restitution), they would be the only benefits considered. The failure to recognize and capture payment for additional benefit accruing to the community at large implies that suppliers in a private market would be unwilling to provide enough judicial services to maximize the net benefits of adjudication.

A similar but perhaps even more fundamental externality argument is put forth by even the staunchest supporters of the market economy. F. A. Hayek, for instance, argued that "government becomes indispensible...in order to see that the mechanism which regulates the production of...goods and services is kept in working order...it provides an essential condition for the preservation of...overall order." Clearly defined property rights are critical requirements for the operation of a market system, so some system of defining and then protecting and enforcing property rights is needed before a market economy can develop. Enforcement of property rights, it is suggested, requires coercion, and only the government is widely viewed to have coercive powers. The establishment of laws and a mechanism for their enforcement, therefore, has the beneficial external effect of allowing the market economy to develop and function. Because no private individual who might benefit from laws and their enforcement would be able to charge for all the benefits generated, too few laws and too little enforcement would develop without government. Besides, individuals would not freely grant other individuals the power to coerce.

It could be contended that the existence of non-exclusionary external benefits makes laws and law enforcement "public goods." And they are, given Samuelson's delineation of the domain of public goods: "A public good is one that enters two or more persons' utility. What are we left with? With a knife-edge pole of the private good case, and with all the rest of the world in the public good domain by virtue of involving some consumption externality." As Goldin pointed out, however, the theory of public goods "is dangerous and misleading theory if it suggests to the unwary that government services should be handled as if they were public goods." The efficient provision of goods that generate benefits requires cooperation, but cooperation does not always require government. Whenever external benefits exist, there are tremendous incentives to internalize them. Consequently, voluntary cooperation occurs daily in the private sector. Every market transaction involves cooperation between the buyer and seller, every good or service produced requires the voluntary cooperation of input suppliers, and every contract is a formal agreement to cooperate. A major distinction between government and private sector is the means used to induce cooperation.

Courts

**A typical "efficiency" argument for courts has been stated by Landes and Posner:

"because of the difficulty of establishing property rights in a precedent, private judges may have little incentive to produce precedents. They will strive for a fair result between the parties in order to preserve a reputation for impartiality, but why should they make any effort to explain the result in a way that would provide guidance for future parties? To do so would confer an external, an uncompensated benefit, not only on future parties but also on competing judges. If anything, judges might deliberately avoid explaining their results because the demand for their services would be reduced by rules that, by clarifying the meaning of the law, reduce the incidence of disputes."

As Friedman commented, this argument "shows insufficiency of ingenuity" in envisioning the system of private courts that would probably arise. Indeed, Landes and Posner cited evidence contradicting their own arguments. For instance, they contended that "a problem is that a system of voluntary adjudication is strongly biased against the creation of precise rules of any sort," but then observed that "precise rules are familiar features of primitive legal systems." As explained, primitive law was privately adjudicated customary law. Landes and Posner also criticized private law for being too precise, preferring what they perceived to be the flexibility and potential for setting precedents of modern common law to the inflexible precision of primitive law. Such inflexibility, they predicted, would probably characterize private law today. Of course, this is simply not the case. If a primitive society was characterized by very few and very slow changes then the benefits of precision would far outweigh any advantage of extreme flexibility....

Landes and Posner argued that in a private judicial system judges are likely to "deliberately avoid explaining the results" in order to create demand for their services, although

"private judges just might produce precedents...competitive private judges would strive for a reputation for competence and impartiality. One method of obtaining such a reputation is to give reasons for a decision that convince the disputants and the public that the judge is competent and impartial. Competition could lead private judges to issue formal or informal "opinions" declaring their interpretation of the law, and these opinions-though intended simply as advertising-would function as precedents, under a public judicial system."

Landes and Posner contended that this is an unlikely scenario because, in an effort to reduce costs, other methods of advertising would be sought. As with the policing function however, contractual organizations and surety arrangements would internalize the benefits of precedents. These organizations would either have their own judges or contract with judges who applied a clear set of rulings that would reduce future disputes. Under such an arrangement, maximizing profit does not involve maximizing the number of cases decided. A judge who provided clear rules and opinions would command a relatively high price for contracts with various organizations. Once under contract, the judge would actually have incentives to minimize the number of disputes that go to trial by making his rules clear-that is, by setting precedents. Under this scenario, private judges have precisely the opposite incentives to those predicted by Landes and Posner. Those judges who "tend to promulgate vague standards which give each party to a dispute a fighting chance" would actually do less business.

The point is not that these internalization procedures arise in all private adjudication arrangements, but that institutions can be envisioned that produce incentives to write clear opinions and set precedents.

Furthermore, such institutions are likely to arise if they generate substantial benefits. Thus, Fuller contended that private arbitrators' incentives are diametrically opposed to those proposed by Landes and Posner. He proposed: "Being unbacked by state power... the arbitrator must concern himself directly with the acceptability of his award. He may be at greater pains than a judge to get his facts straight, to state accurately the arguments of the parties, and generally to display in his award a full understanding of the case."

There is another reason for demanding clear, well founded decisions. Smith referred to it as the "verification aspect." In order to satisfactorily end a dispute the decision must be acceptable-verifiable-not just to the victim and offender but also to the groups or firms representing these parties and groups that might be drawn into a confrontation with one of the groups involved in the dispute. The willingness of other firms and organizations to enter into and honor reciprocal arrangements, such as extradition contracts, with those involved in the dispute depends in part on the way this and other disputes are handled. If an organization's disputes are submitted to judges whose opinions are not clear and well founded, then that organization will have problems influencing the choice of a judge and otherwise supporting their clientele in non-internal disputes.

Smith predicted that private courts would have to 1. allow citizen access to trials so third parties could observe proceedings (exceptions could arise if the parties in the suit had strong demands for privacy), 2. make details of that court's procedures accessible to any interested third party, and 3. make accurate records of a trial available to anyone who might want to review them. These predictions certainly seem to be supported by most historical examples of private courts. Popsil's description of trial procedures among the pimitive Kapauku, for instance, stressed the "public" nature of trials and the efforts that the tonowi took to firmly establish legal precedent for the solution to a dispute. Similarly, the medieval Icelandic, Anglo-Saxon, and Law Merchant courts were public forums. Even though a well publicized aspect of modern arbitration and rent-a-judge systems is their secrecy, this does not necessarily contradict Smith or the historical evidence that supports him. After all, what we see today is a relatively limited system of private courts. Those disputants who have a strong desire for privacy cannot get it from public courts, so they may have the strongest incentives to employ private courts today. Under complete privatization, there will be many disputes that demand clear decisions for public scrutiny.











