# Data Processing Dofile Introduction
## School Panel
### School Directory

### OneApp Data
* [UE_do](index_e.html): This file extracts schools recruiting from OneApp system and generate a dataset including all UE schools for each year.
* [UE_oacode_to_schid](X:\era_nola\Analysis_Li_Ng\UE\UE_school\UE_oacode_to_schid.do): When tring to merge school directory data with UE_flag, Junhan and Jianduo found inconsistency of sch_id, this file is to solve the sch_id problem. Junhan & Jianduo use a new system of sch_id to make sure that identifiers from all datasets are consistent and can be merged together. Finally, Jianduo checks each merge step and makes sure that observations whose _merge!=3 are illegal observations or Pre-K schools or non-public schools.
## Student Panel
## Student Rank Order List
* [stu_rank_order_list_do.do](X:\era_nola\Analysis_Li_Ng\UE\stu_rank_order_list\stu_rank_order_list_do.do)


Hello world
