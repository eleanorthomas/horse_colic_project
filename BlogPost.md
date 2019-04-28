# Horse Colic Cases: What Does the Data Show?

![horse grazing](horse-grazing.jpeg)

**DISCLAIMER:** I am not a veterinarian! Merely a horse lover and machine learning enthusiast. PLEASE do not take any of the information presented in this blog post as veterinary advice, and ALWAYS consult with your veterinarian if you are concerned that your horse (or a horse under your care) may be experiencing colic. I am merely a data nerd with a passion for horses!

## What is Colic?

Colic is a condition of gastrointestinal upset or abdominal pain in horses. Colic is one of the worst nightmares of any horse owner. Symptoms of colic can include decreased appetite, little to no gut sounds, restlessness, obvious discomfort, pacing, rolling, and kicking at the abdomen. In more severe cases, horses can become violent in their movements or display more severe indications of distress, such as an elevated heart rate and respiratory rate, or other abnormal vital signs.

In the most mild cases, colic can resolve on its own with or without medical attention. In more severe cases, colic can require invasive and expensive surgery to resolve, and this isn't always feasible or successful, especially in older or weaker horses. It is valuable to understand the signs of colic, particularly those which are associated with the most severe cases, and in relation to normal, healthy levels for a horse.

## What Can the Data Tell Us?

The Horse Colic Dataset, available from 
[the UC Irvine machine learning archives](https://archive.ics.uci.edu/ml/datasets/Horse+Colic), contains a variety of data for nearly 300 cases of horse colic, including cases which resolved with or without surgical intervention, and cases which resulted in death or euthanization. In cases where the horses did not survive, autopsies were performed to determine if the colic would have required surgery or not. 

Using a machine learning classification technique called "Random Forest Classification", which uses multiple "Decision Tree" classifiers under the hood, we can explore the data in this dataset to attempt to answer two questions of particular interest in any case of colic: Given the health parameters, is this horse likely to require surgery to recover? And: Given the health parameters, is this horse likely to survive? Finally, we can take a look at the ranges of some easily measured vital signs present in the data to get a feeling for how they compare to healthy levels.

## What Does the Data Tell Us?

**TODO: Include summary of results.**

![plot of vital signs](vital_signs.png)

## Why Do We Care?

Colic is a scary situation for any horse owner or horse professional! The more information we have about colic cases, the more armed we are with knowledge to help us take care of our beloved, four-legged friends. I hope you've enjoyed reading about my explorations of this dataset, and perhaps I've inspired you to take a data-driven approach to learning about something you are passionate about!
