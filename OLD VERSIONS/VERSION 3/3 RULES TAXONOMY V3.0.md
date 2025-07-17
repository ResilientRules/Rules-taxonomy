| Type        | Order   | Subtype     | Acronym | Definition                                                                 |
|-------------|------|-------------|---------|-----------------------------------------------------------------------------|
| AGGREGATION |  1.0|     |      |   |
|  |  1.1|   Lack        | AGG.lac     | Outlines the process or decision to be taken in the event of a failure to reach an agreement.  |
|  | 1.2 |   Node   | AGG.nod     | Defines the presence of a decision node and specifies the positions involved in it. |
|  | 1.3 |   Power-sharing  |  AGG.pow    |  Establishes the distribution of power and the treatment of participants, taking into account both symmetry and asymmetry in decision-making. |
|  | 1.3.1 |   Power-sharing Weight | AGG.pow.wei     | Establishes the weighting assigned to actors in non-symmetric aggregation rules.  |
|  |  1.4 |   Procedure | AGG.pro     | Defines the decision-making procedure.  |
|  |  1.4.1|   Agreement  | AGG.pro.agr     | Describes the process of reaching agreement before a decision can be made (e.g., proportion of the total, majority, consensus, binding opinions).|
|  | 1.4.2 |  Condition  | AGG.pro.con     | Defines the presence of a decision node and specifies the positions involved in it. |
|  | 1.4.3 |  Form   |  AGG.pro.for    |  Establishes the distribution of power and the treatment of participants, taking into account both symmetry and asymmetry in decision-making. |
| BOUNDARY    | 2.0 |        |      |        |
|     | 2.1 |  Eligibility       | BOU.eli     |  Defines the eligibility criteria to enter a position.      |
|     | 2.1.1 |    Credential |  BOU.eli.cre    |  Specifies the documentary evidence necessary to validate that actors possess the required attributes for a given position.      |
|     | 2.1.2 |     Membership/residency   | BOU.eli.mem     | Specifies the criteria for entering a position based on the requirement to reside or be registered in a specific place or organization.       |
|     | 2.1.3 |  Personal      |BOU.eli.per      |   Specifies the personal attributes to enter a position.     |
|     | 2.1.3.1 | Acquired       |   BOU.eli.per.acq   |  Specifies the acquired attributes to enter a position (e.g., education, experience).      |
|     | 2.1.3.2 |   Ascribed     | BOU.eli.per.asc    |    Specifies the ascribed attributes to enter a position (e.g., gender, age, race, caste, class ethnicity, clan).    |
|     | 2.1.4 |    Resource   |  BOU.eli.res    |    Specifies the criteria for entering a position based on the association with a resource.    |
|     | 2.2 |    Entry    |   BOU.ent   |   Describes the process of entering a position.     |
|     | 2.2.1 |    Appeal    |   BOU.ent.app   | Defines the process for appeal when an applicant has (not) been selected for a position.       |
|     | 2.2.2 |    Control   |   BOU.ent.con   |     Specifies the control mechanism process through by which eligible actors enter a position.   |
|     | 2.2.2.1 |    Order     |   BOU.ent.con.ord   |  Establish an order or hierarchy for deciding who enters a position (e.g., seniority rights).     |
|     | 2.2.3 |    Elapse   |   BOU.ent.ela   |   Specifies the time frame that must pass between announcing the decision to enter a certain position and actually assuming it.     |
|     | 2.2.4 |    Fee    |   BOU.ent.fee   |   Assigns an entry fee to a position.     |
|     | 2.2.5 |   Multiple     |  BOU.ent.mul    |    Specifies if actors may or must hold multiple positions.    |
|     | 2.2.6 |   Past     |   BOU.ent.pas   | Specifies the entry criteria for an individual who has held a specific position before.       |
|     | 2.2.7 |   Procedure    |    BOU.ent.pro  |     Outlines the procedures or steps for eligible actors to enter a position.   |
|     | 2.2.8 |    Succession   |   BOU.ent.suc   |    Defines the definitive or temporary succession process for positions through inheritance (due to death or in life), illness, death, censure, sale, etc.    |
|     | 2.3 |     Exit    |   BOU.exi   |     Describes the process of leaving a position.   |
|     | 2.3.1 |    Appeal     |   BOU.exi.app   |    Defines the process to appeal an involuntary termination of a position.    |
|     | 2.3.2 |  Control      |  BOU.exi.con    |    Specifies the control mechanism by which eligible actors leave a position.    |
|     | 2.3.2.1 |   Order     |   BOU.exi.con.ord   |  Establish an order or hierarchy for deciding who exits a position.      |
|     | 2.3.3 |   Elapse      |   BOU.exi.ela   |    Specifies the time frame that must pass between announcing the decision to leave a certain position and actually leaving it.    |
|     | 2.3.4 |    Fee     |   BOU.exi.fee   |   Assigns an exit fee to a position.     |
|     | 2.3.5 |    Procedure     |  BOU.exi.pro    | Outlines the procedures or steps for actors to leave or be dismissed from a position.       |
|     | 2.3.6 |   Time      |    BOU.exi.tim  |   Sets the permanence time in a position.     |
| CHOICE      | 3.0 |     |      | |
|       | 3.1 |   Actions   |  CHO.act    | Specifies what an actor occupying a position must, must not, or may do at a particular point in a decision process.|
|       | 3.2 |  Allocation  |    CHO.all  |Describes the forms and models of resource sharing and distribution allocation. |
|       | 3.2.1 | Criteria   |  CHO.all.cri    |Determines the criteria for allocating resources (e.g. to whom, amount to be allocated). |
|       | 3.2.2 | Procedure  |   CHO.all.pro   | Establishes the allocation procedure (e.g. how, when).|
|       | 3.2.3 |  Type |  CHO.all.typ    | Specifies the type of resource to be allocated.|
|       | 3.2.3.1 |  Economic | CHO.all.typ.eco     |Specifies the allocation of financial resources. |
|       | 3.2.3.2 |  Material   |   CHO.all.typ.mat   | Specifies the allocation of material and nonmonetary resources.|
|       | 3.3 |  Contribution  |  CHO.con    |Establishes the contribution and input to be made by the actor who hold a position in terms of time, resources, or effort in a given activity. |
|       | 3.3.1 |  Criteria | CHO.con.cri     |Sets the criteria to define the type and amount of contributions. |
|       | 3.3.2 |  Procedure |  CHO.con.pro    | Establishes the contribution method (e.g., frequency).|
|       | 3.3.3 |  Type   |  CHO.con.typ    |Specifies the type of contribution to be made by actors. |
|       | 3.3.3.1 | Action  |   CHO.con.typ.act   |Assigns the time or effort contribution actors are required to make. |
|       | 3.3.3.2 |  Economic  |  CHO.con.typ.eco    | Assigns the financial contribution actors are required to make.|
|       | 3.3.3.3 |  Material |  CHO.con.typ.mat    |Assigns the material and nonmonetary contributions actors are required to make. |
|       | 3.4 |   Infrastructure  |  CHO.inf    |Establishes the type, quality and quantity of natural and physical infrastructure (such as materials, private or public infrastructure, tools, and technology) that are required, permitted and prohibited. |
|       | 3.5 |  Meeting    | CHO.mee     | Describes all aspects related to meetings, gatherings, assemblies, and events.|
|       | 3.5.1 |  Location  |  CHO.mee.loc    | Sets the location or venue for meetings.|
|       | 3.5.2 | Participation    |  CHO.mee.par    |Establishes the required participation in meetings. |
|       | 3.5.2.1 | Actor   |  CHO.mee.par.act    | Defines who attends or participates in the meetings, including the mandatory attendance of specific actors.|
|       | 3.5.2.2 |  Attendance |   CHO.mee.par.att   | Describes the mandatory attendance at meetings, including the number of absences allowed to actors and the action to be taken by them in case of absence.|
|       | 3.5.2.3 |  Behavior   |   CHO.mee.par.beh   |Defines the behaviors that may or must be adopted during meetings. |
|       | 3.5.2.4 |  Number   |   CHO.mee.par.num   |Determines the required number of participants or quorum for meetings. |
|       | 3.5.2.5 | Procedure |    CHO.mee.par.pro  |Describes the procedure for participating in a meeting. |
|       | 3.5.3 |  Subject  |    CHO.mee.sub  | Outlines the topics to be discussed during meetings.|
|       | 3.5.4 | Time  | CHO.mee.tim     |Sets the time, frequency and duration for meetings. |
|       | 3.5.4.1 | Duration | CHO.mee.tim.dur     |Sets the duration for meetings. |
|       | 3.5.4.2 | Frequency  |  CHO.mee.tim.fre   | Sets the frequency for holding meetings.|
|       | 3.5.4.3 | Timing   | CHO.mee.tim.tim     |Sets the time for meetings. |
|       | 3.5.5 |  Type   |   CHO.mee.typ   | Establishes the type of meeting (e.g., general assembly, ordinary assembly).|
|       | 3.6 |  Monitoring  |  CHO.mon    | Describes the monitoring processes for compliance with actions and outcomes.|
|       | 3.7 |  Resolution  |  CHO.res    |Defines the action taken and process of conflict resolution. |
| INFORMATION | 4.0 |         |      |        |
|  | 4.1 |    Accuracy      |   INF.acc   |   Regulates the accuracy of information.     |
|  | 4.2 |      Channel  |  INF.cha    |  Defines the methods of communication, including assemblies, meetings, newsletters, online platforms, and signage.      |
|  | 4.3|   	Control      |   INF.con	   |  Defines the information control process      |
|  | 4.3.1 |   Network      |    INF.con.net  |     Establishes the control of the communication network.   |
|  | 4.3.2 |   Procedure     |  INF.con.pro    |   Establishes procedures for controlling access to information.     |
|  | 4.3.3 |     Subject     |  INF.con.sub    |    Establishes control over communication topics.    |
|  | 4.4|     	Format    |   INF.for   |    Establishes the mode (e.g., oral, written, visual) and format (e.g., size, duration) for sharing information.    |
|  | 4.5 |    	Language     |   INF.lan   |   Establishes the official language for communication.     |
|  | 4.6 |      	Network   |   INF.net   |  Establishes the communication network.      |
|  | 4.7 |     	Subject    |   INF.sub   |  Defines or restricts the information (e.g., topics) shared among actors, including meeting announcements.      |
|  | 4.8 |     	Time    |   INF.tim   |      Sets the time and frequency for information exchange.  |
|  | 4.8.1 |    Frequency     |   INF.tim.fre   |     Sets the frequency for exchanging information.   |
|  | 4.8.2 |    	Timing    |   INF.tim.tim   |     Sets the time for information exchange.   |
| PAYOFF      | 5.0 |      |      |                  |
|       | 5.1 |   	Action   |  PAY.act    |   Assigns rewards or sanctions for actors based on specific actions that have been taken.               |
|       | 5.1.1 |   	Reward   |   PAY.act.rew   |      Assigns rewards for actors based on specific actions.            |
|       | 5.1.1.1 |  	Criteria    |   PAY.act.rew.cri   |     Sets the criteria for determining the type and amount of rewards for actors based on specific actions.             |
|       | 5.1.1.2 |   	Form   |  PAY.act.rew.for    |   Sets the form and frequency of payments to particular actions.              |
|       | 5.1.1.3 |    Type  |   PAY.act.rew.typ   |    Sets the type of rewards to particular actions.              |
|       | 5.1.1.3.1 |  	Action   | PAY.act.rew.typ.act     |     Assigns rewards for actors by permitting certain activities based on particular actions.             |
|       | 5.1.1.3.2 |   	Economic   |  PAY.act.rew.typ.eco    |    Assigns financial rewards for actors based on specific actions.              |
|       | 5.1.1.3.3 |   Emotional   |  PAY.act.rew.typ.emo    |   Describes emotional rewards for actors based on specific actions.               |
|       | 5.1.1.3.3.1 |   	External   |   PAY.act.rew.typ.emo.ext   |   Describes external emotional rewards for actors based on specific actions.               |
|       | 5.1.1.3.3.2 |   Internal   |  PAY.act.rew.typ.emo.int    |   Describes internal emotional rewards for actors based on specific actions.               |
|       | 5.1.1.3.4 |   Legal   |  PAY.act.rew.typ.leg   |   Assigns legal rewards for actors based on specific actions.               |
|       | 5.1.1.3.5 |   	Material   | PAY.act.rew.typ.mat     |  Assigns tangible, non-economic rewards for actors based on specific actions.                |
|       | 5.1.1.3.6 |   	Physical   | PAY.act.rew.typ.phy |  Assigns physical and/or sensorial (e.g., hugs, applause, cheering) rewards for actors based on specific actions.       |
|       | 5.1.1.3.7 |  Positional   |  PAY.act.rew.typ.pos    | Assigns positional rewards for actors based on specific actions.                 |
|       | 5.1.1.3.8 |   	Spiritual   |  PAY.act.rew.typ.spi    |Specifies divine rewards for actors based on specific actions.                  |
|       | 5.1.2 |   	Sanction   |PAY.act.san      |    Assigns sanctions for actors based on specific actions.              |
|       | 5.1.2.1 |   	Criteria    |  PAY.act.san.cri    |   Sets the criteria for determining the type and amount of sanctions for actors based on specific actions.               |
|       | 5.1.2.2 |   	Form   |  PAY.act.san.for    |    Sets the form and frequency of sanctions.              |
|       | 5.1.2.3 |   	Type   |  PAY.act.san.typ    |  Sets the type of sanctions to particular actions.                |
|       | 5.1.2.3.1 |   	Action   |PAY.act.san.typ.act      |   Assigns sanctions to actors by mandating or prohibiting certain activities based on specific actions.               |
|       | 5.1.2.3.2 |   Economic   | PAY.act.san.typ.eco     | Assigns financial sanctions for actors based on specific actions.                 |
|       | 5.1.2.3.3 |   	Emotional   | PAY.act.san.typ.emo     | Describes emotional sanctions for actors based on specific actions.                 |
|       | 5.1.2.3.3.1 |  	External   |  PAY.act.san.typ.emo.ext    | Describes external emotional sanctions for actors based on specific actions.                 |
|       | 5.1.2.3.3.2 |  	Internal   |  PAY.act.san.typ.emo.int    | Describes internal emotional sanctions for actors based on specific actions.                 |
|       | 5.1.2.3.4 |   Legal   | PAY.act.san.typ.leg     |  Assigns legal sanctions for actors based on specific actions.                |
|       | 5.1.2.3.5 |   	Material   |   PAY.act.san.typ.mat   | Assigns tangible, non-economic sanctions for actors based on specific actions.                 |
|       | 5.1.2.3.6 |   Physical   |  PAY.act.san.typ.phy    | Assigns physical and/or sensorial (e.g., booing) sanctions for actors based on specific actions.                 |
|       | 5.1.2.3.7 |   Positional   | PAY.act.san.typ.pos     |  Assigns positional sanctions for actors based on specific actions.                |
|       | 5.1.2.3.8 |   Spiritual  |   PAY.act.san.typ.spi   | Specifies divine sanction for actors based on specific actions.                 |
|       | 5.1.2.4 |   	Warning   | PAY.act.san.war     |  Set warnings for actors based on particular actions prior to sanctions.                |
|       | 5.2 |   	Outcome   |  PAY.out    |      Assigns rewards or sanctions for actors based on specific outcomes.            |
|       | 5.2.1 |   Reward   |  PAY.out.rew    |  Assigns rewards for actors based on specific outcomes.                |
|       | 5.2.1.1 |   Criteria  |  PAY.out.rew.cri    |  Sets the criteria for determining the type and amount of rewards for actors based on specific outcomes.                |
|       | 5.2.1.2 |   	Form   |   PAY.out.rew.for   |    Sets the form and frequency of rewards to specific outcomes.              |
|       | 5.2.1.3 |   	Type   |  PAY.out.rew.typ    |   Sets the type of rewards to specific outcomes.               |
|       | 5.2.1.3.1 |  	Action   | PAY.out.rew.typ.act     | Assigns rewards for actors by permitting certain activities based on specific outcomes.                 |
|       | 5.2.1.3.2 |   Economic   | PAY.out.rew.typ.eco     |  Assigns financial rewards for actors based on specific outcomes.                |
|       | 5.2.1.3.3 |  Emotional   |   PAY.out.rew.typ.emo   | Describes emotional rewards for actors based on specific outcomes.                 |
|       | 5.2.1.3.3.1 |   External   | PAY.out.rew.typ.emo.ext     |   Describes external emotional rewards for actors based on specific outcomes.               |
|       | 5.2.1.3.3.2 |   Internal   | PAY.out.rew.typ.emo.int     |  Describes internal emotional rewards for actors based on specific outcomes.                |
|       | 5.2.1.3.4 |  Legal   |  PAY.out.rew.typ.leg    |  Assigns legal rewards for actors based on specific outcomes.                |
|       | 5.2.1.3.5 |   Material   | PAY.out.rew.typ.mat     |  Assigns tangible, non-economic rewards for actors based on specific outcomes.                |
|       | 5.2.1.3.6 |   	Physical   | PAY.out.rew.typ.phy     | Assigns physical and/or sensorial (e.g., hugs, applause, cheering) rewards for actors based on specific outcomes.        |
|       | 5.2.1.3.7 |   Positional   | PAY.out.rew.typ.pos     | Assigns positional rewards for actors based on specific outcomes.                 |
|       | 5.2.1.3.8 |   Spiritual   | PAY.out.rew.typ.spi     |  Specifies divine rewards for actors based on specific outcomes.                |
|       | 5.2.2 |   	Sanction   |PAY.out.san      | Assigns sanctions for actors based on specific outcomes.                 |
|       | 5.2.2.1 |   Criteria   |  PAY.out.san.cri    |  Sets the criteria for determining the type and amount of sanctions for actors based on specific outcomes.                |
|       | 5.2.2.2 |   Form   |PAY.out.san.for      |  Sets the form and frequency of sanctions based on particular outcomes.                |
|       | 5.2.2.3 |   Type   |  PAY.out.san.typ    |    Sets the type of sanctions to particular outcomes.              |
|       | 5.2.2.3.1 |   Action   |    PAY.out.san.typ.act  |     Assigns sanctions to actors by mandating or prohibiting certain activities based on specific outcomes.             |
|       | 5.2.2.3.2 |   Economic   | PAY.out.san.typ.eco     |   Assigns economic sanctions for actors based on specific outcomes.               |
|       | 5.2.2.3.3 |   Emotional   | PAY.out.san.typ.emo     |  Describes emotional sanctions for actors based on particular outcomes.                |
|       | 5.2.2.3.3.1 |  	External   | PAY.out.san.typ.emo.ext     |     Describes external emotional sanctions for actors based on specific outcomes.             |
|       | 5.2.2.3.3.2 |   Internal   |  PAY.out.san.typ.emo.int    | Describes internal emotional sanctions for actors based on specific outcomes.                 |
|       | 5.2.2.3.4 |   Legal   | PAY.out.san.typ.leg     | Assigns legal sanctions for actors based on specific outcomes.                 |
|       | 5.2.2.3.5 |   Material    |PAY.out.san.typ.mat      | Assigns tangible, non-economic sanctions for actors based on specific outcomes.                 |
|       | 5.2.2.3.6 |   Physical   |  PAY.out.san.typ.phy    | Assigns physical and/or sensorial (e.g., booing) sanctions for actors based on specific outcomes.                 |
|       | 5.2.2.3.7 |   Positional   |PAY.out.san.typ.pos      |  Assigns positional sanctions for actors based on specific outcomes.                |
|       | 5.2.2.3.8 |   Spiritual   | PAY.out.san.typ.spi     | Specifies divine sanctions for actors based on specific outcomes.                 |
|       | 5.2.2.4 |   Warning   | PAY.out.san.war     |  Set warnings for actors based on particular outcomes prior to sanctions.                |
| POSITION    | 6.0 |         |      |              |
|     | 6.1 |     	Definition    |    POS.def  |      Creates, defines, and otherwise eliminates positions and entities in an action situation.        |
|     | 6.2 |     	Function    |  POS.fun    |      Defines the functions, rights, and obligations associated with each position or entity.        |
|     | 6.3 |     	Number    |  POS.num    |     States the number of actors who hold a position.         |
|     | 6.3.1 |  Lower bound      |  POS.num.low   |   States the lower bound on the number of actors to hold a position.           |
|     | 6.3.2 |   Upper bound      | POS.num.upp     |  States the upper bound on the number of actors to hold a position.            |
| SCOPE       | 7.0 |     |      |     |
|        | 7.1 | 	Definition    |  SCO.def    | Specifies definitions and descriptions of activities, infrastructure, resources, and symbols (e.g., visual identity).    |
|        | 7.2 |  	Domain  |   SCO.dom   |  Defines the spatial, temporal, and legal scope or domain, as well as the resources and activities on those resources, to which the rules apply.   |
|        | 7.2.1 |  Activity   |  SCO.dom.act    | Defines the activities over which the rules apply    |
|        | 7.2.2 |  	Legal   |   SCO.dom.leg   | Specifies the legal framework (e.g. national laws, regulations of natural protected areas, international treaties) and describes changes within that framework in which the rules are established.    |
|        | 7.2.3 |  Resource   | SCO.dom.res     |   Specifies the resource over which the rules apply.  |
|        | 7.2.3.1 |  		Activity   |  SCO.dom.res.act    |  Defines the activities that can be developed with a given resource.  |
|        | 7.2.3.2 |  Characteristics   |  SCO.dom.res.cha    | Specifies the characteristics or condition of the resources to which the rules apply.    |
|        | 7.2.4 |  Social   |   SCO.dom.soc   |  Specifies the social dimension (cultural, historical, ...) over which the rules apply.   |
|        | 7.2.5 |  Spatial   |   SCO.dom.spa   |  Specifies the spatial scope or domain over which the rules apply.   |
|        | 7.2.5.1 |  S	Activity   |  SCO.dom.spa.act    |  Specifies the activities subject to regulation in a particular spatial scope or domain.  |
|        | 7.2.5.2 |  	Characteristics   |   SCO.dom.spa.cha   |   Specifies the characteristics of the spatial scope or domain over which the rules apply.  |
|        | 7.2.6 |  	Temporal   |   SCO.dom.tem   |   Defines the activities that can be developed within a particular time period or domain (e.g., fishing seasons).  |
|        | 7.3 |  	Goal   |  SCO.goa    |  Defines the goals of the rules.   |
|        | 7.3.1 |  	Action  | SCO.goa.act     |  Specifies the goals in terms of actions (e.g. use of pesticides).   |
|        | 7.3.2 |  Outcome   |  SCO.goa.out    |  Specifies the goals in terms of outcomes (e.g., water quality).   |
