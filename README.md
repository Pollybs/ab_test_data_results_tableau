# A/B Test - Data Cleaning and Data Visualization in Tableau Dashboard

<a href="https://public.tableau.com/app/profile/regina.pollyana.bernardes/viz/tableau_vanguard_abtest/Story1?publish=yes"> Tableau Visualization </a>

This project used a fictitious data set from an A/B test. 
The dataset was cleaned and manipulated using Python.
The data was then connected to Tableau Desktop with the aim of analysing and displaying the results of the A/B test on dashboards and in a Tableau Story.


# Vanguard A/B Test

The digital world is evolving, and so are Vanguard’s clients. Vanguard believed that a more intuitive and modern User Interface (UI), coupled with timely in-context prompts (cues, messages, hints, or instructions provided to users directly within the context of their current task or action), could make the online process smoother for clients. The critical question was: Would these changes encourage more clients to complete the process?

The Experiment Conducted
An A/B test was set into motion from 3/15/2017 to 6/20/2017 by the team.

Control Group: Clients interacted with Vanguard’s traditional online process.
Test Group: Clients experienced the new, spruced-up digital interface.
Both groups navigated through an identical process sequence: an initial page, three subsequent steps, and finally, a confirmation page signaling process completion.

The goal is to see if the new design leads to a better user experience and higher process completion rates

Data sources

Client Profiles (df_final_demo): Demographics like age, gender, and account details of our clients. 
https://github.com/data-bootcamp-v4/lessons/blob/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_demo.txt

Digital Footprints (df_final_web_data): A detailed trace of client interactions online, divided into two parts: pt_1 and pt_2. 
https://github.com/data-bootcamp-v4/lessons/blob/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_web_data_pt_1.txt
https://github.com/data-bootcamp-v4/lessons/blob/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_web_data_pt_2.txt

Experiment Roster (df_final_experiment_clients): A list revealing which clients were part of the grand experiment
https://github.com/data-bootcamp-v4/lessons/blob/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_experiment_clients.txt

Dataframes in python files:

cp = data Client Profiles

dfp1 and dfp2 = data Digital Footprints 

dfp = data Digital Footprints (concat of dfp1 and dfp2) 

exc = data Experiment Roster

