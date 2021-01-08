The Double-Edged Sword of Neurobiological Association: Mental Illness
Trends & Implications
================

## Project Overview

Although rooted in science and good-intention, the recent push to view
mental disorders as a function of neurobiological idiosyncrasies rather
than a consequence of character or social environment, has also
unfortunately resulted in public interpretation of mental illnesses as
immutable and a highly negative prognostic. The belief of permanence is
often coupled with perception of incurable danger, unpredictability and
fear-based stereotypes surrounding mental illnesses such as
schizophrenia already struggling to overcome years of socially-ingrained
negative stigma.

This small project looks to build upon both previous clinical psychology
literature highlighting the negative impact neurobiological associations
can have on clinical diagnoses and the social psychology literature
highlighting the warmth and competence mechanisms that often drive
common social stereotypes and valuation. For full study design overview,
see included powerpoint presentation.

## Included Files

**/data**:  
\* ‘StigmaRating\_S1\_V1.csv’: Raw data collected from qualtrics created
and provided to MTurk participants for Study 1a

  - ‘survey\_one\_data\_clean.csv’: Cleaned data from Study 1a survey

  - ‘Stigma Rating - Full Battery\_April 20, 2019\_08.41.csv’: Raw data
    collected from qualtrics survey created and provided to MTurk
    participants for Study 1b

**/code**:  
\* ‘survey\_one\_data\_cleaning.ipynb’: Run to clean Study 1a survey
data (produces ‘survey\_one\_data\_clean.csv’)

  - ‘survey\_one\_pca.ipynb’: Run for principle component analysis used
    to determine underlying mechanisms driving particpants’ perception
    of those diagnosed with either schizophrenia or depression

  - ‘survey\_two\_eda.ipynb’: Run to clean and perform exploratory data
    analysis on Study 1b survey data looking at how 20 syndromes are
    perceived by participants with resulting components from Study 1a
    pca (warm/likeable, competent, and dangerous)

  - ‘survey\_one\_data\_cleaning\_functions.py’: functions utilized in
    survey\_one\_data\_cleaning.ipynb

## Main Findings

Principal factor analyses in Study 1a revealed three underlying
mechanisms driving participants’ perception of mental illnesses:
warmth/likability, competence and dangerousness. This aligns well with
previous social psychology literature identifying warmth and competence
stereotype mechanisms and underscores the potential public association
between mental illness and assumed violence.

Study 1b findings show that, on average, perceptions of dangerousness
decrease if participants have previous familiarity with a given
syndrome. It is also shown that, on average, perceptions of
dangerousness decrease as perceptions of competence and likability
increase and that those with addiction disorders are more likely to be
perceived as dangerous, unlikable and incompetent compared to those with
other biological syndromes such as autism, diabetes or dyslexia. Other
mental illnesses such as schizophrenia, depression and borderline
personality disorder were also perceived to be more dangerous, less
competent and more unlikable compared to the other biological syndromes,
but less severely than the addiction disorders.
