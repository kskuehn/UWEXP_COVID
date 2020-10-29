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
    
## Within.csv
 Data file that includes only participants in both 2019 and 2020
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

## Pooled.ESM.CSV: 
  2019 and 2020 experience sampling data from the 95 participants who took part in both years
   ### Variables included in this file:
    PID
    rank	
    Anxious	
    Depressed	
    Frustrated	
    Scared	
    Lonely	
    neg.aff	
    PSS4.scale	
    PHQ4.scale	
    Q_BDI2	
    Q_STAI	
    Q_UCLA	
    cohort	
    BDI.scale	
    STAI.scale	
    UCLA.scale	
    Depressed.scale	
    Anxious.scale	
    neg.aff.scale	
    Lonely.scale
  
## 2020ESM.csv: 
  2020 experience sampling data 
   ### Variables included in this file:
    PID
    date
    rank
    Depressed
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
