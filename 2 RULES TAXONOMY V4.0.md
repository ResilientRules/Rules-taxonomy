| Type        | ID   | Subtype     | Acronym | Definition                                                                 |
|-------------|------|-------------|---------|-----------------------------------------------------------------------------|
| AGGREGATION |  1.0|     |      |   |
| Aggregation |  1.1|  Aggregation Conflict        | AGG.con     | Defines the processes to be followed in cases of decision appeals or conflict resolution.  |
| AGGREGATION |  1.2|   Aggregation Node  |   AGG.nod   | Defines the presence of a decision node and specifies the positions involved in it.   |
| AGGREGATION |  1.3|  Aggregation Power-sharing    |  AGG.pow    | Establishes the distribution of power and the treatment of actors, taking into account both symmetry and asymmetry in decision-making.  |
| AGGREGATION |  1.3.1| Aggregation Power-sharing  Weight    | AGG.pow.wei     | Establishes the weighting assigned to actors in non-symmetric aggregation rules.  |
| AGGREGATION |  1.4| Aggregation Procedure     |   AGG.pro   | Defines the decision-making procedure.  |
| AGGREGATION |  1.4.1|  Aggregation Procedure Agreement   |   AGG.pro.agr   | Describes the process of reaching agreement before a decision can be made (e.g., proportion of the total, majority, consensus, binding opinions) |
| AGGREGATION |  1.4.1.1|   Aggregation Procedure Agreement Lack  | AGG.pro.agr.lac     | Outlines the process or decision to be taken in the event of a failure to reach an agreement.  |
| AGGREGATION |  1.4.2|    Aggregation Procedure Condition   |   AGG.pro.con   | Specifies the conditions that must be met during decision-making processes, such as the presence of observers and quorum requirements.   |
| AGGREGATION |  1.4.3|  Aggregation Procedure Form   |  AGG.pro.for     | Describes how decisions are conveyed (e.g., through secret vote, show of hands, voice vote, non-delegable, unipersonal).   |
| BOUNDARY  |  2.0|     |      |   |
| BOUNDARY  |  2.1|  Boundary Eligibility  |  BOU.eli    | Specifies eligibility criteria for entering and exiting a position.  |
| BOUNDARY  |  2.1.1| Boundary Eligibility Membership  | BOU.eli.mem     |  Specifies the criteria to enter a position based on the requirement to reside or be registered in a specific place or organization. |
| BOUNDARY  |  2.1.2| Boundary Eligibility Personal  |   BOU.eli.per   | Specifies the personal attributes to enter a position.  |
| BOUNDARY  |  2.1.2.1|   Boundary Eligibility Personal Ascribed   |    BOU.eli.per.asc  | Specifies the ascribed attributes to enter a position (e.g., gender).  |
| BOUNDARY  |  2.1.2.2|   Boundary Eligibility Personal Acquired   |   BOU.eli.per.acq   |  Specifies the acquired attributes to enter a position (e.g., education). |
| BOUNDARY  |  2.1.3|   Boundary Eligibility Resource  | BOU.eli.res     | Specifies the criteria to enter a position based on the association with a resource, infrastructure, or productive activity.  |
| BOUNDARY  |  2.2|  Boundary Entry   |   BOU.ent   | Describes the process of entering a position.   |
| BOUNDARY  |  2.2.1| Boundary Entry Control   |   BOU.ent.con   | Specifies the criteria mechanism by which eligible actors enter a position.  |
| BOUNDARY  |  2.2.2| Boundary Entry Multiple     | BOU.ent.mul     |  Specifies if holding multiple positions by eligible actors are allowed or required, and whether refusing a current position is necessary in order to assume another. |
| BOUNDARY  |  2.2.3|  Boundary Entry Past    |  BOU.ent.pas    |   Specifies the entry criteria for an individual who has held a specific position before. |
| BOUNDARY  |  2.2.4|   Boundary Entry Procedure   |   BOU.ent.pro   | Outlines the procedures or steps for eligible actors to enter a position.  |
| BOUNDARY  |  2.2.4.1|    Boundary Entry Procedure Elapse  |  BOU.ent.pro.ela    | Specifies the time frame that must pass between announcing the decision to enter a certain position and actually assuming it.  |
| BOUNDARY  |  2.2.4.2|  Boundary Entry Procedure Fee   |   BOU.ent.pro.fee   |  Assign an entry fee to a position. |
| BOUNDARY  |  2.2.5|  Boundary Entry Succession    |   BOU.ent.suc   | Defines the definitive or temporary succession process for positions through inheritance (due to death or in life), illness, death, censure, sale, etc.  |
| BOUNDARY  |  2.3|  Boundary Exit   |   BOU.exi   |  Describes the process of leaving a position. |
| BOUNDARY  |  2.3.1|  Boundary Exit Control   |   BOU.exi.con   |  Specifies the criteria mechanism by which eligible actors leave a position. |
| BOUNDARY  |  2.3.2|  Boundary Exit Procedure    |   BOU.exi.pro   | Outlines the procedures or steps for actors to leave or be dismissed from a position. |
| BOUNDARY  |  2.3.2.1|  Boundary Exit Procedure Elapse   |  BOU.exi.pro.ela    | Specifies the time frame that must pass between announcing the decision to leave a certain position and actually leaving it.   |
| BOUNDARY  |  2.3.2.2|  Boundary Exit Procedure Fee   |   BOU.exi.pro.fee   | Assigns an exit fee to a position. |
| BOUNDARY  |  2.3.3|  Boundary Exit Time   |   BOU.exi.tim   |Sets the permanence time in a position.  |
| CHOICE  |  3.0|     |      |  |
| CHOICE  |  3.1| Choice Actions    | CHO.act    | Specifies what specific positions are required, permitted, or prohibited to do. |
| CHOICE  |  3.2|  Choice Allocation    |   CHO.all   |Describes the forms and models of resource sharing and distribution allocation.  |
| CHOICE  |  3.2.1|  Choice Allocation Criteria   |  CHO.all.cri    | Sets the criteria for allocating resources (e.g. to whom, amount to be allocated, how, when). |
| CHOICE  |  3.2.2|  Choice Allocation Type   |   CHO.all.typ   | Specifies the type of resource to be allocated. |
| CHOICE  |  3.2.2.1|  Choice Allocation Type Economic    |  CHO.all.typ.eco    |Allocates financial resources.  |
| CHOICE  |  3.2.2.2|  Choice Allocation Type Material   |  CHO.all.typ.mat   | Allocates material and nonmonetary resources. |
| CHOICE  |  3.3|   Choice Contribution  |   CHO.con   |Establishes the contribution and input to be made by the actor who hold a position in terms of time, resources, or effort in a given activity.  |
| CHOICE  |  3.3.1|  Choice Contribution Criteria   | CHO.con.cri     | Sets the criteria for contributions (type and amount, frequency). |
| CHOICE  |  3.3.2|  Choice Contribution Type   | CHO.con.typ     |Specifies the types of contributions to be made by actors.  |
| CHOICE  |  3.3.2.1|  Choice Contribution Type Action   | CHO.con.typ.act     | Defines the time and effort required for contributions. |
| CHOICE  |  3.3.2.2|  Choice Contribution Type Economic   |   CHO.con.typ.eco   |  Defines financial contributions.|
| CHOICE  |  3.3.2.3|  Choice Contribution Type Material   |  CHO.con.typ.mat   | Defines material contributions. |
| CHOICE  |  3.4|  Choice Infrastructure    | CHO.inf     | Establishes the type, quality, and quantity of natural and physical infrastructure (such as materials, private or public infrastructure, tools, and technology) that are required, permitted and prohibited.  |
| CHOICE  |  3.5|  Choice Meeting   |   CHO.mee   | Describes all aspects related to meetings, gatherings, assemblies, events, courts, etc. |
| CHOICE  |  3.5.1|  Choice Meeting Domain   |   CHO.mee.dom   | Defines the characteristics of meetings within a domain. |
| CHOICE  |  3.5.1.1|  Choice Meeting Domain Location   |  CHO.mee.dom.loc    | Sets the location or venue for meetings. |
| CHOICE  |  3.5.1.2|  Choice Meeting Domain Time   |  CHO.mee.dom.tim    | Sets the time, frequency and duration for meetings. |
| CHOICE  |  3.5.1.2.1|  Choice Meeting Domain Time Duration   |    CHO.mee.dom.tim.dur  | Sets the duration for meetings.  |
| CHOICE  |  3.5.1.2.2|  Choice Meeting Domain Time Frequency   |  CHO.mee.dom.tim.fre     | Sets the frequency for holding meetings.|
| CHOICE  |  3.5.1.2.3|  Choice Meeting Domain Time Timing |  CHO.mee.dom.tim.tim    | Sets the time for meetings.  |
| CHOICE  |  3.5.1.3|  Choice Meeting Domain Type   |   CHO.mee.dom.typ   | Establishes the type of meeting (e.g., ordinary assembly. |
| CHOICE  |  3.5.2| Choice Meeting Participation    |   CHO.mee.par   | Defines who attends, chairs, or participates in meetings. |
| CHOICE  |  3.5.2.1|  Choice Meeting Participation Attendance   |  CHO.mee.par.att    | Specifies the action to be taken in case of actors’ absence, the number of absences allowed to actors, or lack of quorum. |
| CHOICE  |  3.5.2.2|  Choice Meeting Participation Behaviour   |  CHO.mee.par.beh    | Defines the actions and behaviors that are required, permitted, or prohibited during meetings, including guidelines regarding the voluntary or involuntary abandonment of meetings. |
| CHOICE  |  3.6| Choice Monitoring     | CHO.mon     |  Describes the monitoring processes for compliance with actions and outcomes.|
| INFORMATION  |  4.0|     |      |  |
| INFORMATION  |  4.1| Information Domain    | INF.dom     |  |
| INFORMATION  |  4.1.1|  Information Domain Channel   |  INF.dom.cha    | Defines the methods of communication, including assemblies, meetings, newsletters, online platforms, and signage. |
| INFORMATION  |  4.1.2|  Information Domain Format   | INF.dom.for     | Establishes the mode (e.g., oral, written, visual) and format (e.g., size, duration) for sharing information. |
| INFORMATION  |  4.1.2.1|  Information Domain Format Language   |   INF.dom.for.lan   |Establishes the official language for communication.  |
| INFORMATION  |  4.1.3|  Information Domain Time   | INF.dom.tim     | Sets the time and frequency for information exchange.  |
| INFORMATION  |  4.1.3.1|   Information Domain Time Frequency  |   INF.dom.tim.fre   |Sets the frequency for exchanging information.  |
| INFORMATION  |  4.1.3.2|  Information Domain Time Timing   |  INF.dom.tim.tim    | Sets the time for information exchange. |
| INFORMATION  |  4.2| Information Network    |    INF.net  |Establishes the communication network.  |
| INFORMATION  |  4.2.1| Information Network Node    |   INF.net.nod   |Defines the positions involved in communication and specifies who can access information.  |
| INFORMATION  |  4.2.2|  Information Network Subject   |  INF.net.sub   | Defines or restricts the flow of information (e.g., topics) shared among positions, including meeting announcements.  |
| INFORMATION  |  4.2.2.1|  Information Network Subject Accuracy   |   INF.net.sub.acc   | Regulates the accuracy of information. |
| PAYOFF  |  5.0|     |    |  |
| PAYOFF  |  5.1|  Payoff Cause   | PAY.cau   | Defines which actions or outcomes are subject to consequences. |
| PAYOFF  |  5.1.1|  Payoff Cause Action   | PAY.cau.act   | Assigns consequences to specific actions. |
| PAYOFF  |  5.1.2|  Payoff Cause Outcome   |  PAY.cau.out  | Assigns consequences to specific outcomes. |
| PAYOFF  |  5.2|  Payoff Consequence    | PAY.con   | Assigns rewards, sanctions or warnings to specific actions or outcomes. |
| PAYOFF  |  5.2.1|   Payoff Consequence Reward   | PAY.con.rew   | Assigns rewards to specific actions or outcomes. |
| PAYOFF  |  5.2.2|   Payoff Consequence Sanction   |  PAY.con.san  | Assigns sanctions to specific actions or outcomes. |
| PAYOFF  |  5.2.3|  Payoff Consequence Warning   | PAY.con.war   |  Set warnings to specific actions or outcomes prior to sanctions.|
| PAYOFF  |  5.3|   Payoff Criteria  | PAY. cri   | Sets the criteria for determining the nature, magnitude, and mode of consequences. |
| PAYOFF  |  5.4|   Payoff Type  |  PAY.typ  | Sets the type of consequence. |
| PAYOFF  |  5.4.1|  Payoff Type Action    | PAY.typ.act   | Assigns consequences by permitting or prohibiting specific activities. |
| PAYOFF  |  5.4.2|  Payoff Type Economic   |  PAY.typ.eco  | Assigns financial consequences. |
| PAYOFF  |  5.4.3|   Payoff Type Emotional   | PAY.typ.emo   | Describes emotional consequences. |
| PAYOFF  |  5.4.3.1|  Payoff Type Emotional External   |  PAY.typ.emo.ext  | Describes external emotional consequences. |
| PAYOFF  |  5.4.3.2|  Payoff Type Emotional Internal   |   PAY.typ.emo.int | Describes internal emotional consequences. |
| PAYOFF  |  5.4.4|   Payoff Type Legal  | PAY.typ.leg   | Assigns legal consequences. |
| PAYOFF  |  5.4.5|   Payoff Type Material  |   PAY.typ.mat | Assigns tangible, non-economic consequences. |
| PAYOFF  |  5.4.6|  Payoff Type Physical   |  PAY.typ.phy  | Assigns physical and/or sensorial (e.g., hugs, applause, or booing) consequences. |
| PAYOFF  |  5.4.7|  Payoff Type Positional  | PAY.typ.pos   |Assigns positional consequences.  |
| PAYOFF  |  5.4.8|  Payoff Type Spiritual   |  PAY.typ.spi  | Specifies divine consequences. |
| POSITION  |  6.0|     |    |  |
| POSITION  |  6.1| Position  Definition   | POS.def   | Creates, defines, and otherwise eliminates positions and entities in an action situation.   |
| POSITION  |  6.2|  Position Function   | POS.fun   |Defines the functions, rights, responsibilities, duties and obligations associated with each position or entity.  |
| POSITION  |  6.3| Position Number  | POS.num   | States the number of actors who hold a position. |
| POSITION  |  6.3.1| Position  Number Lower bound    |  POS.num.low  | States the lower bound on the number of actors to hold a position. |
| POSITION  |  6.3.2|   Position  Number  | POS.num.upp   | States the upper bound on the number of actors to hold a position. |
|  SCOPE |  7.0|      |    |  |
|  SCOPE |  7.0|      |    |  |
|  SCOPE |  7.0|      |    |  |
|  SCOPE |  7.0|      |    |  |
|  SCOPE |  7.0|      |    |  |
|  SCOPE |  7.0|      |    |  |
|  SCOPE |  7.0|      |    |  |
|  SCOPE |  7.0|      |    |  |
