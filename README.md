# Microsoft Azure SOC Lab

<img width="931" alt="image" src="https://github.com/user-attachments/assets/a2ff592b-b82c-4a53-aab7-f8887109ff91" />

*Project Infrastructure*

## Objective

The Microsoft Azure SOC Lab project aimed to establish a controlled environment for detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system. This hands-on experience was designed to deepen understanding of log analysis, SIEM configuration and network security. 

### Skills Learned

- Understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting SIEM logs.

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- KQL for querying logs regarding Windows Security Events.
- MS Azure VM for honeypot creation.

## Steps

<img width="931" alt="image" src="https://github.com/user-attachments/assets/3e50cf54-dfb4-4d7d-ac0d-a033392beccb" />


*Ref 1: Infrastructure creation with VM, VNET, NSG, and Log Analytics Workspace.*



<img width="300" alt="image" src="https://github.com/user-attachments/assets/6be48b83-49a4-490f-b297-880522031cae" />


*Ref 2: Disabling local firewall on honeypot.*



<img width="931" alt="image" src="https://github.com/user-attachments/assets/20057970-2eec-4cb1-af71-e4f3c2d29fa6" />


*Ref 3: Creating NSG inbound rule to allow any traffic so attackers can start attempting to connect to our honeypot.*



<img width="300" alt="image" src="https://github.com/user-attachments/assets/18f0230e-e1a2-47a6-9674-e6fcb88b9450" />


*Ref 4: Microsoft Sentinel Data connector creation to start collecting logs on VM.*



<img width="900" alt="image" src="https://github.com/user-attachments/assets/8577b976-3b26-4ba7-be59-44278c7cde6c" />


*Ref 5: KQL query ran to view unsuccessful login attempts to honepot.*



<img width="800" alt="image" src="https://github.com/user-attachments/assets/bace2cb8-57f3-4bc8-917c-1c3f7a611071" />


*Ref 6: KQL query ran against newly added watchlist to provide geo location data about attacker IP address.*



<img width="800" alt="image" src="https://github.com/user-attachments/assets/b750c12a-4a5c-4efc-8b5f-e57b2709ae28" />



*Ref 7: Attack map created through Sentinel Workbooks to visualize attacker data on our honeypot.*


