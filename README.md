# ciq-data-analysis
This is a personal repositories to add context for CIQ data anlaysis
This repository contains information related to CIQ Pilot data collection and data analysis. 

## What is CIQ 
CIQ is a conceptual theory and a software platform in psychological domain. This project targets to some of the sophisticated areas in work related bunrout, fatigue and flowstate. Proposed software framework will
help humans to optimize these areas and give thier full potential. This project has three parts
1. Developmnt of CIQ theory
2. Development CIQ platform
3. Development of CIQ Applications

Development of CIQ theory is out of this scope and that part has been already done in a closed research. In summary CIQ theorical framework proves there a optimal states of flowstate somewhere around a person's burnout and fatiuge and other similar states of mind. 
CIQ states that there are proven theories which coorelates some human behavioral biometrics, voice tones/pitch, body states to suhc psychological states. For example bunrout is coorelated to eye blink rate, voice tone or something. At this stage project is considering burnout as the primary are a. 

### CIQ Platform 
This is also in conceptual stage where software engineers, machine learning and AI experts and domain experts are working to develop a common framework or platform to predict burnout and subsequently other such states. Engineering team has identified this stage requires data analysis and machine learning. 

### CIQ Data Collection 
Team has decided that we need data to do analysis and machine learning thus we have planned a pilot application to collect data and conduct our initial study on data. This is called as CIQ Pilot Data Collection and subsequent stage is called data analysis and machine learning. 

# CIQ Pilot Study

## Scope of the pilot study 
Collect samples from available population a 30 person sample has been defined by scientific team. We dont have population of a speific work domain since this is preliminary sample collection pilot, we have selected a diversified population where there are professionals, entreprenuers, houseiwfes, community leaders, freelancers on various domains. 

## Data Collection methedology 
1. An open invitation to participate in pilot study
2. Scientific team verified and validated the volneteers and informed the members to participate
3. As per scientif team a person should participate in 3 consecutive weeks on given dates where the gap from one collection to other is 7 days or in somecases 6 days
4. There  is a Web application specifically dsinged for pilot study.
5. Participant will be givne a uniq login id and have to sit infront of the laptop allocated to them where applicationis already loaded in browser
6. Once the user journey has completed application records the data and allow the team to download the data file for each user 

### Web Application and User flow 
1. This is web application runs on laptop browser and there is a backend server where most of the procesing occurs
2. Aditionaly there in MUSE EEG devic plugged into the app through bluetooth connect where EEG data will be collected
3. User will be logd in using given user id and the MUSE headband will be placed in his head as per the MUSE device instructions
4. User click start session button
5. Where an Agentic AI backed by Azure OpenAI Live Vocie Agent interfaced with GPT model stats to speak
6. From this time onwards MUSE EEG data wil be collected in browser front-end through bluetooth connect
7. User wil be asked for a 3 minutes open eye baseline test where a certain behavioral biometric and EEG data collected
8. Then user wil be asked for another 3 minutes closed eye baseline test where a certain behavioural biometric and EEG data collected
9. Then user will be aksed to anser through voice for prdeifned BAT-4 survey and CBI-3 suvery where the app voice agent asks the questions and record voice answers
10. There can be delays in answers since participants takes varied time to answer
11. Once those questions are anwered the data collection stops and a repiort will be genrated
12. User can optionaly participate in a post survey conversation with voice agent but no data will be collected here
13. Approximately a well attended un interrupted session is 7 - 10 minutes long

Sample data file of one user a data dictionary is is given sepratly in this repository.

