# Setting Up An Elastic SIEM w/Kali Linux
I will be using Elastic to ingest and visualize data from security events in Kali Linux and create alerts/rules based on the data.

# Adding An Agent For Log Collection
<img width="947" alt="image" src="https://github.com/user-attachments/assets/3764242c-b8ce-47d7-ba9c-f28346437edc">

<img width="521" alt="image" src="https://github.com/user-attachments/assets/ee1e5e80-7aff-4144-9264-2456f7c32f08">

Running the command in Kali 
<img width="811" alt="image" src="https://github.com/user-attachments/assets/deaa8ac0-b544-4fb3-923e-7450c8d5db0f">

Successfully installed an Elastic Agent on the machine

<img width="304" alt="image" src="https://github.com/user-attachments/assets/c8dc6750-2798-4c85-9cdf-b7d3382da1cc">

Confirming the agent was successfully installed

<img width="434" alt="image" src="https://github.com/user-attachments/assets/b35138d1-4ef6-4c4d-ba15-82b56c126495">

# Creating Security Events in Kali
Running Nmap scans on a couple of different hosts

<img width="477" alt="image" src="https://github.com/user-attachments/assets/9cace240-0629-44ba-aa38-0f689abee788">

# Querying Generated Data in The Elastic SIEM
Navigating to the Logs

<img width="122" alt="image" src="https://github.com/user-attachments/assets/78b488a8-bc82-4d67-b13e-cd4ef7318a50">





# Visualizing Data

<img width="119" alt="image" src="https://github.com/user-attachments/assets/ac4ce6a9-32a9-4db0-9641-ef37af508d46">


Creating a Dashboard

<img width="896" alt="image" src="https://github.com/user-attachments/assets/6e107a54-9ccf-4ce9-86a3-9214780eff06">


Creating a Visualization

<img width="949" alt="image" src="https://github.com/user-attachments/assets/2fa821a7-3ba6-400f-9907-5876e6db7fe1">

Created a visualization using the "Area" type to show the count of records over time

<img width="937" alt="image" src="https://github.com/user-attachments/assets/18a87c8b-4b8f-45e4-a6a6-18b0c12f1527">

# Creating Rules in The Elastic SIEM
<img width="116" alt="image" src="https://github.com/user-attachments/assets/89627317-90eb-4f00-89ce-fd7be2f9f4af">

<img width="945" alt="image" src="https://github.com/user-attachments/assets/48478cfc-bbc3-408f-ba75-d2774bcc3e85">

Creating a custom query to have an alert created for detecting Nmap scans

<img width="945" alt="image" src="https://github.com/user-attachments/assets/a558dcb9-488d-49a7-93ba-5038a29722b4">

<img width="473" alt="image" src="https://github.com/user-attachments/assets/c5ae6d89-54ab-4e27-82b6-4a4391194a08">

Adding a name and severity for the rule 

<img width="500" alt="image" src="https://github.com/user-attachments/assets/022d8ad2-3b28-413b-bbd7-fd23c615502b">

Rule Schedule

<img width="504" alt="image" src="https://github.com/user-attachments/assets/e8c52c95-4bf8-49c3-b3f7-123fb14db8b1">

Creating and enabling rule

<img width="502" alt="image" src="https://github.com/user-attachments/assets/5714db11-31d8-4bde-a1e7-7d01a1aeae35">















