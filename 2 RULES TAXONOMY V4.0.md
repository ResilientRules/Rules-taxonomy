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
| CHOICE  |  3.0|     |      |  |
| CHOICE  |  3.0|     |      |  |
| CHOICE  |  3.0|     |      |  |
| CHOICE  |  3.0|     |      |  |
| CHOICE  |  3.0|     |      |  |
| CHOICE  |  3.0|     |      |  |
| CHOICE  |  3.0|     |      |  |
| CHOICE  |  3.0|     |      |  |
