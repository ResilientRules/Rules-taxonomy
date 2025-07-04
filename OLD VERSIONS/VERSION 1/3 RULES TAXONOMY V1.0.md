| ID     | Acronym      | Description                                                                 |
|--------|--------------|-----------------------------------------------------------------------------|
| 1.1    | POS_def      | Define positions                                                            |
| 1.2    | POS_num      | State whether there is a defined number, no limit, a lower limit, or an upper limit on the number of participants who hold a position |
| 1.2.1  | POS_num_low  | Defines the lower bound on the number of participants in a position         |
| 1.2.2  | POS_num_up   | Defines the upper bound on the number of participants in a position         |

| ID     | Acronym         | Description                                                                                       |
|--------|-----------------|---------------------------------------------------------------------------------------------------|
| 2.1    | BOU_eli         | Define the eligibility of individuals to hold the position of member. Specify criteria (e.g., ascribed and acquired attributes) |
| 2.1.1  | BOU_eli_asc     | Ascribed attributes: attained at birth, inheritance, or aging process (e.g., race, age, gender)   |
| 2.1.2  | BOU_eli_acq     | *(no description provided)*                                                                       |
| 2.2    | BOU_ent         | Define the process determining which eligible participants may or must enter positions            |
| 2.2.1  | BOU_ent_cnt     | Boundary rules: open (full control), invitational (selective invitation), competitive, compulsory  |
| 2.2.2  | BOU_ent_fee     | Entry rules may assign fees or inducements                                                        |
| 2.2.3  | BOU_ent_mul     | Rules about multiple positions (e.g., one vs. multiple simultaneous positions)                     |
| 2.2.4  | BOU_ent_suc     | Succession rules: eligibility to move between positions and criteria                               |
| 2.3    | BOU_exi         | Define how or when an individual may or must leave a position                                     |
| 2.3.1  | BOU_exi_pas     | Fixed term rules with no control to retain position after term expiry                             |
| 2.3.2  | BOU_exi_ela     | Time limit between announcing exit and actual exit                                               |
| 2.3.3  | BOU_exi_fee     | Fees associated with early exit (e.g., penalties)                                                |
| 2.3.4  | BOU_exi_mst     | Seniority or other rules restricting exit                                                       |
| 2.3.5  | BOU_exit_app    | Procedures for appealing involuntary termination                                                |

|Type | ID     | Acronym      | Description                                                                                      |
|-----|--------|--------------|------------------------------------------------------------------------------------------------|
|CHOICE| 3.1    | CHO_agn      | Choice rules affect the total power created  in action situations and the distributio of this power. One particular type of choice rules are agenda conrol rules. Agenda rules limit or expand the authority of participants in particular positions to propose particular actions.|
| | 3.1.1  | CHO_agn_cls  | A closed agenda control rule limits the number of alternative actions that can be decided uppon.                                         |
| | 3.1.2  | CHO_agn_opn  | An open agenda control rule allows any feasibile action to be considered.                        |
| | 3.1.3  | CHO_agn_ger  | A "germaneness rule" restricts alternatives to those that affect the same set of state variables???       |

| ID     | Acronym      | Description                                                                                      |
|--------|--------------|------------------------------------------------------------------------------------------------|
| 4.1    | AGG_sym      | Specify how participants in a situation are treated differently or alike in regard to some decision to be made at some point in a decision process. |
| 4.2    | AGG_wgh      | Specify the weights given to players in nonsymmetric aggregation rules.|
| 4.3    | AGG_vot      | Specify what proportion of the total must be in agreement before an authoritative decision can be made and what happens if the niminal agreement is not reached.|
| 4.4    | AGG_lck      | It states what will happen if a certain proportion of the participants does not agree to a proposed action. Specify what decision will happen if no agreement isreached. Whenever a decision depends on the approval of more than one participant, the possibility of no agreement is always present.|

| ID     | Acronym      | Description                                                                                      |
|--------|--------------|------------------------------------------------------------------------------------------------|
| 5.1    | INF_cha      | Specify the set of channels of communication that may or may not exist between postions in a situation. The set of all possible channels connecting all participants in a situation. The connections can be represented a a perfectly connected polygon of whatever dimension equals the number of participans. It there are five participants, there are nine possible connections between these participants. In formation rules partition this set of possible connections into subsets of required (a channel must exist), forbidden (a channel must not exist), and permitted (a channel may exist).|
| 5.2    | INF_frq      | Regulate the frequency of exchange of information.                                                  |
| 5.3    | INF_acc      | Regulate the accuracy of information. The accuracy rules affect what type of indicators may or must be used as evidence about the state of the world. Rules establishing audit procedures are intended to enforce the accuracy of financial information available to top management and shareholders of a firm.              |
| 5.4    | INF_sub      | Limit the topics that can be discussed among participants.     |
| 5.5    | INF_lan      | Specify the official language for communication.                                                 |

| ID     | Acronym               | Description                                                                                      |
|--------|-----------------------|------------------------------------------------------------------------------------------------|
| 6.1    | PAY_act               | Directly impact the net costs and benefit of actions.                                             |
| 6.2    | PAY_out               | Directly impact the net costs and benefit of outcomes.                                          |
| 6.3    | PAY_rew               | Assign external rewards.                                                                    |
| 6.3.1  | PAY_reward_direct     |                                                                   |
| 6.3.2  | PAY_reward_emotional  | Emotional rewards (internal or external)                                                      |
| 6.4    | PAY_san               | Assigns external sanctions                                                                     |
| 6.4.1  | PAY_sanction_direct   |                                                                    |
| 6.4.2  | PAY_sanction_emotional| Emotional sanctions (internal or external)                                                    |

| ID  | Acronym | Description                                                                                          |
|-----|---------|----------------------------------------------------------------------------------------------------|
| 7   | SCO     | Comment from Understanding ID: We find many fewer instances of explicit scope rules than choice rules, and thus less need to further divide scope rules into specific types. If outcome regulation continues to epand, and tereby increases the need for policy scholars to study scope rules, more attention will need to be paid to the types of scope rules that exist.|
