# UWEXP COVID Mixed Methods Study
Data and analysis scripts for UWEXP COVID mixed methods study. 

Analysis scripts are here: https://kskuehn.github.io/UWEXP_COVID/ 

# Data files included in repository: 

## Year2Year.csv:
 Data file used to compare 2019 and 2020 Time 1 responses
  ### Variables included in this file:
    PID: Participant ID
    Phase: Variable specifying if 2019 or 2020 data 
    Q_BDI: BDI-II scale scores  
    Q_STAI: State-Trait Anxiety Inventory scale scores
    Q_PSS: Perceived Stress Scale Scores
    Q_UCLA: UCLA Loneliness Scale scores

## 2020pre.post.csv: 
  Data file to compare 2020 pre and post survey
  ### Variables included in this file:
    PID: Participant ID
    tp: Variable specifying if Time or Time 2 score
    Q_BDI: BDI-II scale scores  
    Q_STAI: State-Trait Anxiety Inventory scale scores
    Q_PSS: Perceived Stress Scale Scores
    Q_UCLA: UCLA Loneliness Scale scores

## 2020ESM.csv: 
  2020 experience sampling data. Includes some responses from 2020 pre survey (high_BDI2, high_STAI, high_UCLA) which represents participants who reported levels     more than one standard deviation above the mean. 
   ### Variables included in this file:
    PID
    date
    rank
    Depressec
    Anxious
    Frustrated
    Lonely
    neg.aff
    high_BDI
    high_STAI
    high_UCLA
    low_SES
    PHQ4
    PSS4
    academic
    Learning.Barriers
    caregiving
    Finance
    coping.prop
    coping.prop.GMC
    coping.prop.CWP
    Severity
    Coping.success
