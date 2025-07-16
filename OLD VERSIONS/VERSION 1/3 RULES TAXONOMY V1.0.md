| Type        | Order   | Subtype     | Acronym | Definition                                                                 |
|-------------|------|-------------|---------|-----------------------------------------------------------------------------|
| AGGREGATION |  1.0 |     |      |   |
|  |  1.1|   Lack        | AGG_lck     | It states what will happen if a certain proportion of the participants does not agree to a proposed action. Specify what decision will happen if no agreement isreached. Whenever a decision depends on the approval of more than one participant, the possibility of no agreement is always present.  |
|  | 1.2 |  Symmetry (symmetric, nonsymmetric)   | AGG_sym     | Specify how participants in a situation are treated differently or alike in regard to some decision to be made at some point in a decision process. |
|  | 1.3 |   Vote  |  AGG_vot    |  Specify what proportion of the total must be in agreement before an authoritative decision can be made and what happens if the niminal agreement is not reached. |
|  | 1.4 |   Weight | AGG_wgh     | Specify the weights given to players in nonsymmetric aggregation rules.  |
| BOUNDARY    | 2.0 |        |      |        |
|     | 2.1 |  Eligibility       | BOU.eli     |  Define the eligibility of individuals to hold the position of member. Define who is eligible to enter a position. Specify the criteria to be used (e.g., ascribed and acquired attributes) to determine whether an actor is eligible to fill a particular position. These rules include a set of transformations that partition a defined set of individuals, usually bounded in space and time, into subsets of individuals who are eligible and ineligible to hold the position of member.      |
|     | 2.1.1 |     Eligibility Acquired |  BOU_eli_acq    |        |
|     | 2.1.2 |     Eligibility Ascribed   | BOU_eli_asc     | Ascribed refers to characteristics of an individual attained at birth, by inheritance, or through the aging process. E.g., race, age, gender       |
|     | 2.2 |    Entry    |   BOU.ent   |   Define the process that determinew which eligible participants may enter (or must enter) positions. Define how the set of eligibles are further partitioned into subsets of position-holders and nonholders     |
|     | 2.2.1 |    Entry Control    |   BOU_ent_cnt   |        |
|     | 2.2.2 |     Entry Fee   |   BOU_ent_fee   |     Entry rules that are open, invitational, or competitive may assign a fee or unducement to any eligible individual who wishes to enter a position. The level or strictness of entry and exit costs is relative to the availability of an attribute or a resource in a community.   |
|     | 2.2.3 |    Entry Multiple     |   BOU_ent_mul   |  Rules related to multiple positions. For example, members hold one, and only one, position. Another option is when members may hold several differetn positions simultaneously. This type of rule set covers, but does not partition, the set of participants.     |
|     | 2.2.4 |    Entry Succession   |   BOU_ent_suc   |   Boundary rules may also define eligibility for entry to positions in terms of rules that define who is eligible to move from one position to another and what criteria must be met, often called succession rules. E.g., move into higher-level positions when vacancies occur.     |
|     | 2.3 |     Exit    |   BOU.exi   |     Define how an individual may leave (or must leave) a position. Define the conditions under which a participant must, must not, or may leave a position. The capability of a participant to leave a position is a fundamental limit on the power that other participants can exert over a participant.   |
|     | 2.3.1 |    Exit Appeal     |   BOU_exit_app   |    Provide a forum and procedure for a participant who wishes to appeal an involuntary termination    |
|     | 2.3.2 |   Exit Elapse      |  BOU_exi_ela    |    Particular rules may set a limit on the amount of time that must elapse from announcing a decision to leave and actually leaving    |
|     | 2.3.3 |    Exit Fee     |   BOU_exi_fee   |  Particular rules may set a charge associated with leaving a position prior to fulfilling some aspects of a contract (e.g., pay court charges)      |
|     | 2.3.4 |   Exit Must      |   BOU_exi_mst   |    While the holder of a position in most situations may be able to exit voluntarily, others may also have greater or lesser control over whether the person continues in or leaves the position. One particular rule is the socalled seniority rules: e.g., contracts often specify rights to positions according to seniority, which limits the power of a boss to select which employees will be terminated during times of financial restrictions. Under seniority rules, the last person hired into a position is the first to be laid off, regardless of work performance.    |
|     | 2.3.5 |    Exit Past     |   BOU_exi_pas   |   Rules sometimes set fixed terms of office with stringent rules concerning the eligibility of a past position holder to be eligible to hold the same position again. Under such circumstancers, the person in the position has no control over retaining the position after the fixed term has expired     |
| CHOICE      | 3.0 |     |      | |
|       | 3.1 |   Agenda   |  CHO_agn    | Choice rules affect the total power created  in action situations and the distributio of this power. One particular type of choice rules are agenda conrol rules. Agenda rules limit or expand the authority of participants in particular positions to propose particular actions.|
|       | 3.1.1 |  Agenda Close  |    CHO_agn_cls  |A closed agenda control rule limits the number of alternative actions that can be decided uppon. |
|       | 3.1.2 |  Agenda German   |  CHO_agn_ger    |A "germaneness rule" restricts alternatives to those that affect the same set of state variables |
|       | 3.1.3 |  Agenda Open   |  CHO_agn_opn    |An open agenda control rule allows any feasibile action to be considered. |
| INFORMATION | 4.0|         |   	   |        |
|  | 4.1|   	Accuracy      |   INF_acc	   |  Regulate the accuracy of information. The accuracy rules affect what type of indicators may or must be used as evidence about the state of the world. Rules establishing audit procedures are intended to enforce the accuracy of financial information available to top management and shareholders of a firm.      |
|  | 4.2 |   	Channel      |    INF_cha  |     Specify the set of channels of communication that may or may not exist between postions in a situation. The set of all possible channels connecting all participants in a situation. The connections can be represented a a perfectly connected polygon of whatever dimension equals the number of participans. It there are five participants, there are nine possible connections between these participants. In formation rules partition this set of possible connections into subsets of required (a channel must exist), forbidden (a channel must not exist), and permitted (a channel may exist).   |
|  | 4.3 |    	Frequency     |  INF_frq    |   Regulate the frequency of exchange of information.    |
|  | 4.4 |     	Language     |  INF_lan    |    Specify the official language for communication.    |
|  | 4.5|     	Subject    |   INF_sub   |    Limit the topics that can be discussed among participants.    |
| PAYOFF      | 5.0 |      |      |                  |
|       | 5.1 |   	Action   |  PAY_act    |   Directly impact the net costs and benefit of actions.               |
|       | 5.2 |   	Outcome   |   PAY_out   |      Directly impact the net costs and benefit of outcomes.            |
|       | 5.3 |  	Reward    |   PAY_rew   |     Assign external rewards.             |
|       | 5.3.1 |  	Reward  Direct  |   PAY_reward_direct   |                  |
|       | 5.3.2 |  	Reward Emotional   |   PAY_reward_emotional   |     Emotional rewards (internal or external)             |
|       | 5.4 |  	Sanction    |   PAY_san   |     Assigns external sanctions             |
|       | 5.4.1 |  	Sanction Direct    |   PAY_sanction_direct   |                  |
|       | 5.4.2 |  	Sanction Emotional    |   PAY_sanction_emotional   |     Emotional sanctions (internal or external)             |
| POSITION    | 6.0 |         |      |              |
|     | 6.1 |     	Definition    |    POS_def  |      Define positions        |
|     | 6.2 |     	Number    |  POS_num    |      State whether there is a defined number, no limit, a lower limit, or an upper limit on the number of participants who hold a position        |
|     | 6.2.1 |     	Number Lower bound    |  POS_num_low    |     Defines the lower bound on the number of participants in a position         |
|     | 6.2.2 |   	Number	Upper bound      |  POS_num_up   |   Defines the upper bound on the number of participants in a position           |
| SCOPE       | 7.0 |     |      |     |
