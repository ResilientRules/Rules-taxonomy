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
| | 3.1.1  | CHO_agn_cls  | A closed agenda control rule limits the number of alternative actions that can be decided uppon                                         |
| | 3.1.2  | CHO_agn_opn  | An open agenda control rule allows any feasibile action to be considered                        |
| | 3.1.3  | CHO_agn_ger  | A "germaneness rule" restricts alternatives to those that affect the same set of state variables???       |

| ID     | Acronym      | Description                                                                                      |
|--------|--------------|------------------------------------------------------------------------------------------------|
| 4.1    | AGG_sym      | Specifies whether participants are treated symmetrically or asymmetrically in decision-making  |
| 4.2    | AGG_wgh      | Specifies weights assigned to players in nonsymmetric aggregation rules                        |
| 4.3    | AGG_vot      | Specifies required proportion for authoritative decisions and consequences if not reached     |
| 4.4    | AGG_lck      | Specifies what happens if no agreement is reached                                             |

| ID     | Acronym      | Description                                                                                      |
|--------|--------------|------------------------------------------------------------------------------------------------|
| 5.1    | INF_cha      | Specifies communication channels allowed, required, or forbidden among participants            |
| 5.2    | INF_frq      | Regulates frequency of information exchange                                                   |
| 5.3    | INF_acc      | Regulates accuracy of information; e.g., audit procedures                                     |
| 5.4    | INF_sub      | Limits topics allowed for discussion                                                          |
| 5.5    | INF_lan      | Specifies official language for communication                                                 |

| ID     | Acronym               | Description                                                                                      |
|--------|-----------------------|------------------------------------------------------------------------------------------------|
| 6.1    | PAY_act               | Directly impacts net costs and benefits of actions                                             |
| 6.2    | PAY_out               | Directly impacts net costs and benefits of outcomes                                           |
| 6.3    | PAY_rew               | Assigns external rewards                                                                       |
| 6.3.1  | PAY_reward_direct     | *(no description provided)*                                                                    |
| 6.3.2  | PAY_reward_emotional  | Emotional rewards (internal or external)                                                      |
| 6.4    | PAY_san               | Assigns external sanctions                                                                     |
| 6.4.1  | PAY_sanction_direct   | *(no description provided)*                                                                    |
| 6.4.2  | PAY_sanction_emotional| Emotional sanctions (internal or external)                                                    |

| ID  | Acronym | Description                                                                                          |
|-----|---------|----------------------------------------------------------------------------------------------------|
| 7   | SCO     | Fewer explicit scope rules than choice rules. As outcome regulation grows, more study of scope rules is needed |
