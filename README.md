# AM_code_R
R code for the project of group AM
ata README

# Project data description
### Team name : AM

The data folder structure and organization contains two data sets of the two experiments' groups: 
the Self group and the Provider group. 
The data contains their answers to the questionnaire - rating every emotion from 1 to 5.  

#### General Details  

| Name of column | Type | Meaning |
|--------|------|---------|
|StartDate|Date|The date of starting to answer the questionnaire|
|EndDate|Date|The date of finishing to answer the questionnaire|
|Duration (in seconds)|int| How long it took to answer the question| 
|RecordedDate|Data|The date of answering the questionnaire|
|UserLanguage|char| person language|
|id| char| The person ID|
|Event| char| event or a situation that took place recently (in the past two days) that bothered the person|

#### The questionnaire: **Please rank your feeling from "Not very" (1) to "Very" (5)**


| Name of column | Type | Meaning |
|--------|------|---------|
|Neg Rate 1.1_1_Bad|dbl| How bad do you feel? |
|Neg Rate 1.3_1|dbl|How significant is the event to you?|
|mood1_1_Angery|dbl| How angry are you at the moment?|
|mood1_2_Happy|dbl| How happy are you at the moment?|
|mood1_3_anxious|dbl| How anxious are you at the moment?|
|mood1_4_distressed|dbl| How distressed are you at the moment?|
|mood1_5_cheerful|dbl| How cheerful are you at the moment?|
|mood1_6_calm |dbl| How calm are you at the moment?|
|mood1_7_sad |dbl| How sad are you at the moment?|
|mood1_8_relaxed|dbl| How relaxed are you at the moment?|
|mood1_9_lonely |dbl| How lonely are you at the moment?|
|mood1_10_energertic |dbl| How energetic are you at the moment?|
|reframe|char|reframe your feelings/thoughts to this negative situation in a way that makes you feel
 less negative.|
|regulaiton_effect|int| What is the effect of reframing your event on your mood? After the reframe|
|mood2_1_Angery |int|How angry are you at the moment?|
|mood2_2_Happy|int| How happy are you at the moment?|
|mood2_3_anxious|int| How anxious are you at the moment?|
|mood2_4_distressed |int| How distressed are you at the moment?|
|mood2_5_cheerful|int| How cheerful are you at the moment?|
|mood2_6_calm|int|How calm are you at the moment?|
|mood2_7_sad|int|How sad are you at the moment?|
|mood2_8_relaxed|int| How relaxed are you at the moment?|
|mood2_9_lonely |int| How lonely are you at the moment?|
|mood2_10_energertic |int|How energetic are you at the moment?|
|SSES_1|int|I feel confident about my abilities.|
|SSES_2|int|I am worried about whether I am regarded as a success or failure.|
|SSES_3|int|I feel satisfied with the way my body looks right now.|
|SSES_4|int| I feel frustrated or rattled about my performance.|
|SSES_5|int|I feel that I am having trouble understanding things that I read.|
|SSES_6|int| I feel that others respect and admire me.|
|SSES_7|int|I am dissatisfied with my weight.|
|SSES_8|int| I feel self-conscious.|
|SSES_9 |int|I feel as smart as others.|
|SSES_10|int| I feel displeased with myself.|
|SSES_11 |int|I feel good about myself.|
|SSES_12|int| I am pleased with my appearance right now.|
|SSES_13 |int|I am worried about what other people think of me.|
|SSES_14|int|I feel confident that I understand things.|
|SSES_15|int|I feel inferior to others at this moment.|
|SSES_16 |int|I feel unattractive.|
|SSES_17|int|I feel concerned about the impression I am making.|
|SSES_18 |int| I feel that I have less scholastic ability right now than others.|
|SSES_19 |int|I feel like I'm not doing well.|
|SSES_20|int| I am worried about looking foolish|
