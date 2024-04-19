<h1>A/B Test Results - Data Cleaning and Data Visualization in Tableau Dashboard </h1>

Fr: Nettoyage et visualisation de données pour un test A/B
• Python : nettoyage et manipulation des données du test A/B sur un site web
• Tableau Desktop: élaboration de dashboards permettant de visualiser et bien interpréter les résultats du test A/B

<a href="https://public.tableau.com/app/profile/regina.pollyana.bernardes/viz/tableau_vanguard_abtest/Story1?publish=yes"> Tableau Visualization </a>

<a href="https://github.com/Pollybs/ab-test-vanguard-tableau-viz/blob/main/Presentation_Vanguard%20A_B_test.pdf"> Final Presentation </a>

This project involved analyzing a fictitious dataset from an A/B test using Python and Tableau. The dataset was cleaned and manipulated using Python, and then connected to Tableau Desktop for visual analysis. The results of the A/B test were displayed on interactive dashboards and presented in a Tableau Story, providing valuable insights into user behavior and preferences. The project aimed to demonstrate proficiency in data cleaning, manipulation, and visualization, as well as the ability to effectively communicate findings to stakeholders.


<h2>Vanguard A/B Test</h2>

The digital world is evolving, and so are Vanguard’s clients. Vanguard believed that a more intuitive and modern User Interface (UI), coupled with timely in-context prompts (cues, messages, hints, or instructions provided to users directly within the context of their current task or action), could make the online process smoother for clients. The critical question was: Would these changes encourage more clients to complete the process?

The Experiment Conducted
An A/B test was set into motion from 3/15/2017 to 6/20/2017 by the team.

Control Group: Clients interacted with Vanguard’s traditional online process.
Test Group: Clients experienced the new, spruced-up digital interface.
Both groups navigated through an identical process sequence: an initial page, three subsequent steps, and finally, a confirmation page signaling process completion.

The goal is to see if the new design leads to a better user experience and higher process completion rates

<h3> Data sources </h3>

Client Profiles (df_final_demo): Demographics like age, gender, and account details of our clients. 
https://github.com/data-bootcamp-v4/lessons/blob/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_demo.txt

Digital Footprints (df_final_web_data): A detailed trace of client interactions online, divided into two parts: pt_1 and pt_2. 
https://github.com/data-bootcamp-v4/lessons/blob/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_web_data_pt_1.txt
https://github.com/data-bootcamp-v4/lessons/blob/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_web_data_pt_2.txt

Experiment Roster (df_final_experiment_clients): A list revealing which clients were part of the grand experiment
https://github.com/data-bootcamp-v4/lessons/blob/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_experiment_clients.txt

<h3>Dataframes in python files </h3>

cp = data Client Profiles

dfp1 and dfp2 = data Digital Footprints 

dfp = data Digital Footprints (concat of dfp1 and dfp2) 

exc = data Experiment Roster

