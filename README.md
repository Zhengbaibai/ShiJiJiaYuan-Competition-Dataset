"# ShiJiJiaYuan-Competition-Dataset" 


### 1.Interaction records of users

   - #### train.txt

- Each sample consists of the following information: USER_ID_A, USER_ID_B, ROUND, ACTION.

- | Action | Description |
| ------- | ------- |
|    rec     |   System recommended user B to user A      |
|    click     |   User A clicked to browse personal information of user B, after the recommendations from system      |
|    msg     |   User A sent a message to user B    |


### 2.User profiles

- profile_m.txt: profiles of male users in datasets
- profile_f.txt: profiles of female users in datasets
- Description of profiles




- | Field name | Description |
| ------- | ------- |
|    Uid     |    |
|    sex     |   F:female <br> M:male     |
|    msg     |   User A sent a message to user B    |
|    register_time     |   Number of seconds since 1970 |
|    last_login     |  Number of seconds since 1970  |
|    birth_year     |    |
|    Birthday     |    |
|    work_location     |    |
|    work_sublocation     |    |
|    status     | 1: Looking for dates<br>2: on a date<br>3: Already found the right person<br>4: Leave temporarily   |
|    ms_mobile     |  Whether to verify the mobile phone  |
|    education     |  10: Technical secondary school<br>20: College<br>30: Undergraduate<br>40: Double major<br>50: Master<br>60: Ph.D.<br>70: Postdoctor  |
|    house     |  0: Confidential<br>1: Not owning houses<br>2: Owning houses<br>3: Renting a house shared with others<br>4: Renting a house alone<br>5: Living with parents<br>6: Living with relatives or friends<br>7: Living in dormitories  |
|    auto     |  0: Confidential<br>1: Not owning cars<br>2: Owning cars  |
|    marriage     |  1: unmarried<br>2: Divorce<br>3: Widowed  |
|    children |  0: Confidential<br>1: No children<br>2: Leaving with children<br>3: Having children but not living together     |
|    industry     |  0: Confidential<br>1: students<br>2: Computer/Internet/IT<br>3: Electronics/Semiconductor/Instrument<br>4: Communication Technology<br>5: Sales<br>6: Market expansion<br>7: PR/Business<br>8: Sourcing/Trade<br>9: Customer Service/Technical Support<br>10: Human Resources/Administration/Logistics<br>11: Senior Management<br>12: Production/Processing/Manufacturing<br>13: Quality Control/Security Check<br>14: Construction Machinery<br>15: Mechanic<br>16: Accounting/Auditing/Statistics<br>17: Finance/Securities/Investments/Insurance<br>18: Real Estate/Renovation/Property<br>19: Warehousing/Logistics<br>20: General Labor/Housekeeping<br>21: General service industry<br>22: Aviation Services<br>23: Education/Training<br>24: Consulting/Consultants<br>25: Academic/Research<br>26: Law<br>27: Design/Creativity<br>28: Literature / Media / Film and Television<br>29: Dining/Tourism<br>30: Chemicals<br>31: Energy/Geological Exploration<br>32: Medical/Nursing<br>33: Health/Beauty<br>34: Biological/Pharmaceutical/Medical Devices<br>35: Sports Workers<br>36: Translation<br>37: Civil servants/state cadres<br>38: Private Owners<br>39: Agriculture / Forestry / Animal Husbandry / Fishery<br>40: Police/Other<br>41: Freelancers<br>42: Other<br>43: Traffic/Transportation  |
|    privacy    |    |
|    level      |    |
|    nation     |  0: Confidential<br>1: Han nationality<br>2: Tibetan nationality<br>3: Korean nationality<br>4: Mongolian nationality<br>5: Hui nationality<br>6: Manchu nationality<br>7: Uyghur nationality<br>8: Zhuang nationality<br>9: Yi nationality<br>10: Miao nationality<br>11: Other Nationalities  |
|    height     |    |
|    income  |  Average monthly salary<br>0:Confidential<br>10:2000 ￥<br>20:2000 ～ 5000 ￥<br>30:5000 ～ 10000 ￥<br>40:10000 ～ 20000 ￥<br>50:over 20000 ￥     |
|    avatar   |    |
| belief       | 0: Confidential<br>1: No religion<br>2: Mahayana Buddhism<br>3: Mahayana Buddhism Tantra<br>4: Theravada Buddhism<br>5: Taoism<br>6: Confucianism<br>7: Christian Catholicism<br>8: Christian Orthodox<br>9: Protestant Christianity<br>10: Judaism<br>11: Shia Islam<br>12: Sunni Islam<br>13: Hinduism<br>14: Shintoism<br>15: Shamanism<br>16: Other Religious Beliefs   |
|    match_min_age    |    |
|   match_max_age|    |
|    match_min_height     |    |
|    match_max_height     |    |
|    match_certified       |    |
|    match_marriage|   0: unlimited<br>1: Unmarried<br>2: Divorce<br>3: Widowed<br>4: Unmarried, divorced<br>5: Unmarried, widowed<br>6: Divorced, widowed  |
|    match_education    |    |
|    match_edu_more_than     |    |
|    match_avatar     |    |
|    match_work_location|    |
|    match_work_sublocation     |    |


