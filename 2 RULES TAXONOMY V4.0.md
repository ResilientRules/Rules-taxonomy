| Type        | Order   | Subtype     | Acronym | Definition                                                                 |
|-------------|------|-------------|---------|-----------------------------------------------------------------------------|
| AGGREGATION |  1.0|     |      |   |
|  |  1.1|   Conflict        | AGG.con     | Defines the processes to be followed in cases of decision appeals or conflict resolution.  |
|  |  1.2|    Node  |   AGG.nod   | Defines the presence of a decision node and specifies the positions involved in it.   |
|  |  1.3|   Power-sharing    |  AGG.pow    | Establishes the distribution of power and the treatment of actors, taking into account both symmetry and asymmetry in decision-making.  |
|  |  1.3.1|  Weight    | AGG.pow.wei     | Establishes the weighting assigned to actors in non-symmetric  rules.  |
|  |  1.4|  Procedure     |   AGG.pro   | Defines the decision-making procedure.  |
|  |  1.4.1|  Agreement   |   AGG.pro.agr   | Describes the process of reaching agreement before a decision can be made (e.g., proportion of the total, majority, consensus, binding opinions) |
|  |  1.4.1.1|    Lack  | AGG.pro.agr.lac     | Outlines the process or decision to be taken in the event of a failure to reach an agreement.  |
|  |  1.4.2|     Condition   |   AGG.pro.con   | Specifies the conditions that must be met during decision-making processes, such as the presence of observers and quorum requirements.   |
|  |  1.4.3|   Form   |  AGG.pro.for     | Describes how decisions are conveyed (e.g., through secret vote, show of hands, voice vote, non-delegable, unipersonal).   |
| BOUNDARY  |  2.0|     |      |   |
|   |  2.1|  Eligibility  |  BOU.eli    | Specifies eligibility criteria for entering and exiting a position.  |
|   |  2.1.1| Membership  | BOU.eli.mem     |  Specifies the criteria to enter a position based on the requirement to reside or be registered in a specific place or organization. |
|   |  2.1.2| Personal  |   BOU.eli.per   | Specifies the personal attributes to enter a position.  |
|   |  2.1.2.1|   Ascribed   |    BOU.eli.per.asc  | Specifies the ascribed attributes to enter a position (e.g., gender).  |
|   |  2.1.2.2|   Acquired   |   BOU.eli.per.acq   |  Specifies the acquired attributes to enter a position (e.g., education). |
|   |  2.1.3|   Resource  | BOU.eli.res     | Specifies the criteria to enter a position based on the association with a resource, infrastructure, or productive activity.  |
|   |  2.2|  Entry   |   BOU.ent   | Describes the process of entering a position.   |
|   |  2.2.1| Control   |   BOU.ent.con   | Specifies the criteria mechanism by which eligible actors enter a position.  |
|   |  2.2.2| Multiple     | BOU.ent.mul     |  Specifies if holding multiple positions by eligible actors are allowed or required, and whether refusing a current position is necessary in order to assume another. |
|   |  2.2.3|  Past    |  BOU.ent.pas    |   Specifies the entry criteria for an individual who has held a specific position before. |
|   |  2.2.4|   Procedure   |   BOU.ent.pro   | Outlines the procedures or steps for eligible actors to enter a position.  |
|   |  2.2.4.1|    Elapse  |  BOU.ent.pro.ela    | Specifies the time frame that must pass between announcing the decision to enter a certain position and actually assuming it.  |
|   |  2.2.4.2|  Fee   |   BOU.ent.pro.fee   |  Assign an entry fee to a position. |
|   |  2.2.5|  Succession    |   BOU.ent.suc   | Defines the definitive or temporary succession process for positions through inheritance (due to death or in life), illness, death, censure, sale, etc.  |
|   |  2.3|  Exit   |   BOU.exi   |  Describes the process of leaving a position. |
|   |  2.3.1|  Control   |   BOU.exi.con   |  Specifies the criteria mechanism by which eligible actors leave a position. |
|   |  2.3.2|  Procedure    |   BOU.exi.pro   | Outlines the procedures or steps for actors to leave or be dismissed from a position. |
|   |  2.3.2.1|  Elapse   |  BOU.exi.pro.ela    | Specifies the time frame that must pass between announcing the decision to leave a certain position and actually leaving it.   |
|   |  2.3.2.2|  Fee   |   BOU.exi.pro.fee   | Assigns an exit fee to a position. |
|   |  2.3.3|  Time   |   BOU.exi.tim   |Sets the permanence time in a position.  |
| CHOICE  |  3.0|     |      |  |
|   |  3.1| Actions    | CHO.act    | Specifies what specific positions are required, permitted, or prohibited to do. |
|   |  3.2|   Allocation    |   CHO.all   |Describes the forms and models of resource sharing and distribution allocation.  |
|   |  3.2.1|   Allocation Criteria   |  CHO.all.cri    | Sets the criteria for allocating resources (e.g. to whom, amount to be allocated, how, when). |
|   |  3.2.2|   Allocation Type   |   CHO.all.typ   | Specifies the type of resource to be allocated. |
|   |  3.2.2.1|   Allocation Type Economic    |  CHO.all.typ.eco    |Allocates financial resources.  |
|   |  3.2.2.2|   Allocation Type Material   |  CHO.all.typ.mat   | Allocates material and nonmonetary resources. |
|   |  3.3|    Contribution  |   CHO.con   |Establishes the contribution and input to be made by the actor who hold a position in terms of time, resources, or effort in a given activity.  |
|   |  3.3.1|   Contribution Criteria   | CHO.con.cri     | Sets the criteria for contributions (type and amount, frequency). |
|   |  3.3.2|   Contribution Type   | CHO.con.typ     |Specifies the types of contributions to be made by actors.  |
|   |  3.3.2.1|   Contribution Type Action   | CHO.con.typ.act     | Defines the time and effort required for contributions. |
|   |  3.3.2.2|   Contribution Type Economic   |   CHO.con.typ.eco   |  Defines financial contributions.|
|   |  3.3.2.3|   Contribution Type Material   |  CHO.con.typ.mat   | Defines material contributions. |
|   |  3.4|   Infrastructure    | CHO.inf     | Establishes the type, quality, and quantity of natural and physical infrastructure (such as materials, private or public infrastructure, tools, and technology) that are required, permitted and prohibited.  |
|   |  3.5|   Meeting   |   CHO.mee   | Describes all aspects related to meetings, gatherings, assemblies, events, courts, etc. |
|   |  3.5.1|   Meeting Domain   |   CHO.mee.dom   | Defines the characteristics of meetings within a domain. |
|   |  3.5.1.1|   Meeting Domain Location   |  CHO.mee.dom.loc    | Sets the location or venue for meetings. |
|   |  3.5.1.2|   Meeting Domain Time   |  CHO.mee.dom.tim    | Sets the time, frequency and duration for meetings. |
|   |  3.5.1.2.1|   Meeting Domain Time Duration   |    CHO.mee.dom.tim.dur  | Sets the duration for meetings.  |
|   |  3.5.1.2.2|   Meeting Domain Time Frequency   |  CHO.mee.dom.tim.fre     | Sets the frequency for holding meetings.|
|   |  3.5.1.2.3|   Meeting Domain Time Timing |  CHO.mee.dom.tim.tim    | Sets the time for meetings.  |
|   |  3.5.1.3|   Meeting Domain Type   |   CHO.mee.dom.typ   | Establishes the type of meeting (e.g., ordinary assembly. |
|   |  3.5.2|  Meeting Participation    |   CHO.mee.par   | Defines who attends, chairs, or participates in meetings. |
|   |  3.5.2.1|   Meeting Participation Attendance   |  CHO.mee.par.att    | Specifies the action to be taken in case of actors’ absence, the number of absences allowed to actors, or lack of quorum. |
|   |  3.5.2.2|   Meeting Participation Behaviour   |  CHO.mee.par.beh    | Defines the actions and behaviors that are required, permitted, or prohibited during meetings, including guidelines regarding the voluntary or involuntary abandonment of meetings. |
|   |  3.6|  Monitoring     | CHO.mon     |  Describes the monitoring processes for compliance with actions and outcomes.|
| INFORMATION  |  4.0|     |      |  |
|   |  4.1|  Domain    | INF.dom     |  |
|   |  4.1.1|   Domain Channel   |  INF.dom.cha    | Defines the methods of communication, including assemblies, meetings, newsletters, online platforms, and signage. |
|   |  4.1.2|   Domain Format   | INF.dom.for     | Establishes the mode (e.g., oral, written, visual) and format (e.g., size, duration) for sharing information. |
|   |  4.1.2.1|   Domain Format Language   |   INF.dom.for.lan   |Establishes the official language for communication.  |
|   |  4.1.3|   Domain Time   | INF.dom.tim     | Sets the time and frequency for information exchange.  |
|   |  4.1.3.1|    Domain Time Frequency  |   INF.dom.tim.fre   |Sets the frequency for exchanging information.  |
|   |  4.1.3.2|   Domain Time Timing   |  INF.dom.tim.tim    | Sets the time for information exchange. |
|   |  4.2|  Network    |    INF.net  |Establishes the communication network.  |
|   |  4.2.1|  Network Node    |   INF.net.nod   |Defines the positions involved in communication and specifies who can access information.  |
|   |  4.2.2|   Network Subject   |  INF.net.sub   | Defines or restricts the flow of information (e.g., topics) shared among positions, including meeting announcements.  |
|   |  4.2.2.1|   Network Subject Accuracy   |   INF.net.sub.acc   | Regulates the accuracy of information. |
| PAYOFF  |  5.0|     |    |  |
|   |  5.1|   Cause   | PAY.cau   | Defines which actions or outcomes are subject to consequences. |
|   |  5.1.1|   Cause Action   | PAY.cau.act   | Assigns consequences to specific actions. |
|   |  5.1.2|   Cause Outcome   |  PAY.cau.out  | Assigns consequences to specific outcomes. |
|   |  5.2|   Consequence    | PAY.con   | Assigns rewards, sanctions or warnings to specific actions or outcomes. |
|   |  5.2.1|    Consequence Reward   | PAY.con.rew   | Assigns rewards to specific actions or outcomes. |
|   |  5.2.2|    Consequence Sanction   |  PAY.con.san  | Assigns sanctions to specific actions or outcomes. |
|   |  5.2.3|   Consequence Warning   | PAY.con.war   |  Set warnings to specific actions or outcomes prior to sanctions.|
|   |  5.3|    Criteria  | PAY. cri   | Sets the criteria for determining the nature, magnitude, and mode of consequences. |
|   |  5.4|    Type  |  PAY.typ  | Sets the type of consequence. |
|   |  5.4.1|   Type Action    | PAY.typ.act   | Assigns consequences by permitting or prohibiting specific activities. |
|   |  5.4.2|   Type Economic   |  PAY.typ.eco  | Assigns financial consequences. |
|   |  5.4.3|    Type Emotional   | PAY.typ.emo   | Describes emotional consequences. |
|   |  5.4.3.1|   Type Emotional External   |  PAY.typ.emo.ext  | Describes external emotional consequences. |
|   |  5.4.3.2|   Type Emotional Internal   |   PAY.typ.emo.int | Describes internal emotional consequences. |
|   |  5.4.4|    Type Legal  | PAY.typ.leg   | Assigns legal consequences. |
|   |  5.4.5|    Type Material  |   PAY.typ.mat | Assigns tangible, non-economic consequences. |
|   |  5.4.6|   Type Physical   |  PAY.typ.phy  | Assigns physical and/or sensorial (e.g., hugs, applause, or booing) consequences. |
|   |  5.4.7|   Type Positional  | PAY.typ.pos   |Assigns positional consequences.  |
|   |  5.4.8|   Type Spiritual   |  PAY.typ.spi  | Specifies divine consequences. |
| POSITION  |  6.0|     |    |  |
|   |  6.1|   Definition   | POS.def   | Creates, defines, and otherwise eliminates positions and entities in an action situation.   |
|   |  6.2|   Function   | POS.fun   |Defines the functions, rights, responsibilities, duties and obligations associated with each position or entity.  |
|   |  6.3|  Number  | POS.num   | States the number of actors who hold a position. |
|   |  6.3.1|   Number Lower bound    |  POS.num.low  | States the lower bound on the number of actors to hold a position. |
|   |  6.3.2|     Number  | POS.num.upp   | States the upper bound on the number of actors to hold a position. |
|  SCOPE |  7.0|      |    |  |
|   |  7.1|   Definition    | SCO.def   |Specifies the definitions, designations, and descriptions of activities, infrastructure, resources, and symbols.  |
|   |  7.2|   Domain  |  SCO.dom  | Sets the spatial, temporal, and legal domain, as well as the resources and activities to which the rules apply. |
|   |  7.2.1|     Domain Activity   |SCO.dom.act    |Defines the activities over which the rules apply.  |
|   |  7.2.2|   Domain Legal    |   SCO.dom.leg | Specifies the legal framework (e.g. national laws, regulations of natural protected areas, international treaties) and describes changes within that framework in which the rules are established. |
|   |  7.2.3|     Domain Resource   |  SCO.dom.res  |Specifies the resource to which the rules apply and describes its characteristics. |
|   |  7.2.4|   Domain Social    |   SCO.dom.soc | Specifies the socio-cultural dimension (e.g., cultural, historical) over which the rules apply. |
|   |  7.2.5|    Domain Spatial   | SCO.dom.spa   | Specifies the spatial extent to which the rules apply and describes its characteristics. |
|   |  7.2.6|   Domain Temporal    |  SCO.dom.tem  | Specifies the temporal scope over which the rules apply. |
|   |  7.3|   Goal    | SCO.goa   | Defines the goals of the rules. |
|   |  7.3.1|    Goal Action   |  SCO.goa.act  | Specifies the goals in terms of actions. |
|   |  7.3.2|  Goal Outcome     | SCO.goa.out   | Specifies the goals in terms of outcomes. |
