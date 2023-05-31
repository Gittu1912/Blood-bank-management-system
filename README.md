# Blood-bank-management-system
                                    Project Report 
                On Blood Bank Mnangement System 
 
                     ITM  University,  Raipur,  Chhattisgarh 
             For the partial fulfilment of the award of the degree  
                                             Of 
                         Bachelor of technology (CSE)    
                                    Submitted by    
 Name of the Student   - Gitesh Pradhan / Shubham Bansal
             Enrollment No.            -H0489 / H0339
                 Roll no.                  – 
                             Under the Supervision of  
                                    Mr. Raktim deb  
          
                              
 
                      School of Engineering and Reserch 
 
          Uparwara, Naya Raipur, Raipur, Chhattisgarh-492002 (2023) 
PREFACE  
  
  
The successful completion of this project was a unique experience for me because by visiting many places and interacting with various 
persons, I achieved a better knowledge about the subject. The experience, which I gained by doing this project, was essential at this turning point of my career. This project is being submitted which 
contains detailed analysis of the research undertaken by me.  
This project is divided in to several parts. First Part contains brief overview of software and topic. Second Part consists of Objectives and primary investigation. Middle Part consists of data analysis and interpretation. Last part contains the observations and findings followed 
	by conclusion.  	 
ACKNOWLEDGEMENT  
  
  
I would like to express my deep sense of 
gratitude to the respectable guide distinguished personalities for their precious suggestions and encouragement during the project.  
 
he experience which is gained by me during this project is essential for me at this turning point of my career.  
 
I am thankful to Mr. Raktim Deb, Faculty In charge for his kind support, supervision and guidance.  
 
Last but not the least I would like to thank all the faculty members, my friends &  
Family members for their constant support.  
  
  
 
  
  
                                                                                                               
                      SELF DECLARATION  
   
This is to declare that project titled “BLOOD 
BANK MANAGEMENT SYSTEM” submitted 
in Partial fulfillment of the requirements for the Degree of Bachelor of Technology of ITM University is my own work and no part of this report has been submitted for the award of any other degree, diploma, and fellowship.The work 
has not been published in any Journal or Magazine.  
                                                                                     
                                                                     
                                                     Gitesh Pradhan  /                                                      Subham Bansal
  
Enrollment No.H0489 / H0339
  
  
 
                 CERTIFICATE OF EVALUATION  
  
  
This is to certify that Mr. Gitesh Pradhan /Subham bansal Enrollment No. H0489 / H0339 student of Btech (Final Year) Session 2019-23 at ITM University Naya Raipur, Raipur  Chhattisgarh, has worked under my supervision for this Independent 
project on “BLOOD BANK MANAGEMENT SYSTEM” submitted to Department of Btech, 
towards partial fulfillment of the requirement of Bachelor Degree – The Bachelor of Technology (Btech). It is only for academic purpose and is a Bona fide work done by the researcher.  
  
  
  
       The above study is dully approved by me and is the candidate’s own contribution.  
  
  
  
  
  
       Project Guide – Raktim Deb 
 
 
 
 
 
 
 
 
 
 
 
Introduction Of Project 
 
 
 
 
 
 
 
 
 
 
        CHAPTER 1: INTRODUCTION  
 
 
 
Blood transfusion safety remains an important  public health concern in Oman. The availability of blood products of all blood types and the provision of its safety ensure public trust of its excellent healthcare system. However, lack of availability of these blood products and provision of unsafe blood products still impact morbidity and mortality in the Sultanate. Through the use of online blood bank management system, blood transfusion safety is expected to be enhanced or improved. Risks on improper blood donors’ documentation, and misplaced records can be minimized or totally avoided. Also, processes involving blood bag collection, storage, and inventory will be systematized and organized, hence, improving the healthcare management. 1.1 Background of the Study For hospitals, a blood bank known as blood collection center, also is an area in which collected blood bags are stored and preserved for future use in blood transfusion services. Blood transfusion is a medical operation where a patient requires blood or blood products as a life saving measure. . In an article1 published in Times of Oman in 2014, it was reported by Ministry of Health (MoH) that the total amount of blood donated annually in Muscat is approximately 25,084 units. MoH further reported that its Department of Blood Services is functioning at full capacity to meet the demands in the Sultanate. Most blood banks are still running manual system in its processes. As such, there is a lack of efficiency because it is still paper-based in collecting information about donors, inventories of blood bags, and blood transfusion services. The lack of proper documentation may endanger patients’ health due to the possibility of having contaminate blood bags. Contamination happened when there is an incomplete donors’ medical history record and the blood bags’ shelf life is not monitored properly. Hence, a web-based blood bank management system might be needed to address these issues and problems encountered to ensure blood transfusion safety. 1.2 Problem Statement Despite advances in technology, nowadays, most blood bank systems are running in manual system. As such, there is a prevalent problem in the availability of needed blood types. For instance, when a person needs a certain type of blood and this type is not available in the hospital, family members send messages through social media to those who can donate to them and this process takes longer than the life of the 
patient to the most dangerous. In addition, it seems that there is lack of proper documentation about blood donors and its medical history. This may lead to blood bag contamination and may affect the blood transfusion safety. Generally, this study aims to determine how the use of online bank management system enhance blood transfusion safety. Subsequently, this study seeks to answer the following specific problems: 1. What is the level of perception among blood bank’s stakeholders on manual-based system? 2. What is the level of perception among blood bank’s stakeholders on online blood bank management system? 3. H0: Is there no significant difference in the level of perception among stakeholders between manual-based and onlinebased blood bank system? H1: Is there a significant difference in the level of perception among stakeholders between manual-based and online-based blood bank system? 1.3 Objective(s), Scope and Limitations 1.3.1 Objective: This applied research aims to design, develop and implement online blood bank management system. This web-based application provides: 
 
 
 
•	To ensure hospital to have good supply or inventories of blood bags. 
•	To check the availability of blood bags anytime. 
•	To manage the information of its blood donor. 
•	Function to check if the person donate blood for the last 3 months. 
•	To allow good documentation about the donor and its blood donation activities. 
•	Support fast searching to find match blood bags for the right person. 
 
 1.3.2 Scope: This research study covers the three (3) basic operations of blood banks, namely:  donor registration, monitoring of blood bags or products’ inventories, and monitoring of blood bags or products’ issuance. Also, due to timeconstraint, respondents will be from hospitals from North Batinah Region in the Oman, though the research study talks about blood banks in the Sultanate of Oman. In addition, the study considers three (3) possible users of the system, namely: hospital administrator, doctors, and blood receptionists. 
 
 
 
 1.3.3 Limitation: This research study does not cover the actual blood collection activity, and actual blood transfusion operation. Blood donors and patients or recipients of blood donation are not system users, their registration or information will be encoded by the blood bank receptionists. 
1.4. Assumptions and Hypothesis: The researchers assume the following assumptions: 1. Internet connectivity is needed for the online blood management system. Internet speed may affect the perception of the systems users with regards to the system effectiveness and efficiency. 2. Blood transfusion should be performed by medical or professional doctors only. The over-all safety depends on the success of the medical operation. 
 
 
 The researchers identify the following hypotheses: 
1.	There is a significant difference in the level of blood transfusion safety between manual-based and online blood bank systems. 
  
2.	There is an increased level of blood transfusion safety in using online blood bank management systems while there is an increased risk when using manual-based one. 
 
 5 Significance of the problem The findings of this study will benefit blood banks in managing blood donation donors, activities, and blood bags. 
 
 This will allow the hospital to take decision if a particular type of blood is needed and currently unavailable in the hospital, however, available in another nearby hospitals. Furthermore, managing the blood bags in the blood bank will be much easier because each blood bag has an information about the donor, donation activity details, and the expiration date. 
 
 Also, doctor can use this system to serve blood bags to their patient and monitor the details of the donor. The main advantages of the system are: 
•	Blood bank staff can find and manage the donor details on the system easily.  
 
•	The expiration date of blood bags can be viewed in the system. 
 
•	Hospital can be alerted about issued blood bags and its availability. 
 
•	The system is systematized, and organized in managing blood donor records and blood donation activities. 
 
 
 
 1.6 Definition of terms  Blood bags are designed for the collection, processing and storage of whole blood and blood components They help in providing aseptic conditions for the separation of blood components. It acts as a closed system reducing the chances of contamination. Blood bank is a place where blood bag that is collected from blood donation events is stored in one place. Which refers to a division of a hospital laboratory where the storage of blood product occurs and where proper testing is performed to reduce the risk of transfusion related events. Donor is someone who gives a part of their body or some of their blood to be used by doctors to help a person who is ill.  Transfusion: transfusion is done as a lifesaving maneuver to replace blood cells or blood products lost through severe bleeding. Transfusion of one's own blood (autologous transfusion) is the safest method, but it requires advanced planning, and not all patients are eligible. 
   
           





             CHAPTER 2: REVIEW OF LITERATURE  
 
2.1	Introduction This section discusses findings and observations done by some research works on webbased blood bank management system. The gathered information on these related papers strengthens and supports the research study. 
 
 
2.2	Literature Studies According to 2Teena, C.A, Sankar, K. and Kannan, S. (2014) in their study entitled “A Study on Blood Bank Management”, they defined Blood Bank Information System as an information management system that contributes to the management of donor records and blood bank. Their system allowed an authorized blood bank administrator to sign in with a password to manage easily the records of donors and patients who need blood. The system provided many features including the central database, quick access to the system content through the login, includes the search code to find donors on a given basis, and the ease of adding and updating donor data. The main aim of the system was to complete the process of the blood bank. This system was designed to suit all types of blood banks. Once successful in the implementation of the application, it can be applied and rolled out in several blood banks. This application contains User Login Screen, Blood Management, Menu Form, Blood Stock, Donor 
Management, Donor Registration, Blood 
Reservation, Donor Blood Test, Recipient Management and Blood Reservation. In similar manner, the researchers planned in their application to have hospital administrator, doctors, and blood bank receptionists as users. The authors did not mentioned the research method they used, and failed to provide screenshots of the system prototypes, making difficult for the researchers to visualize their application. No discussion also for their respondents, samples and sampling techniques used. Subsequently, the researchers planned to provide figures to explain the system, screenshots of system prototypes, and other diagrams that can help other researchers to visualize the development of web-based blood bank management system. Also, the researchers will explicitly discuss its research methods, sampling procedures, and statistical treatment to be used for analyzing the gathered data. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
CHAPTER 3: METHODS & 
PROCEDURES  
 
3.1 Introduction This section presents the research methodology used in the study, the research design, and the data collection process. This section also presents the theoretical or conceptual framework of the study, the sampling plan, and tools to be used for data analysis. 
 
 3.2 Theoretical/ Conceptual  
 
 
  
 
 
 
 
 
 
 
 
 
 
 
 
Conceptual Framework The conceptual framework served a mental window of the researchers because it depicted the research design and the relationships of the variables involved. Based on the figure above, the usage or utilization of the online blood bank management system can lead to the enhancement or improvement of blood transfusion safety. 3.3 Methods and Procedures The researchers used both descriptive research and experimental research design methods. The study was descriptive because it describes the nature of situation as it exists at the time of the study. Also, it was a systematic and scientific approach to research in which the researchers manipulate one or more variables, and control and measure any change in other variables. It involves collection of data in order to test hypotheses or to answer questions concerning current status of the subject of the study. The study was also experimental because it has an assumption of a cause-and-effect relationship, and the researchers introduce online blood bank management system as intervention that caused the change. In this study, the researchers used questionnaire to collect information and to obtain the perception of the various stakeholders on how they perceive the manual-based system and the online system. The questionnaire was administered to hospital administrators, doctors, and blood bank receptionists. In sampling, the researchers used cluster sampling in which respondents were grouped according to their roles and responsibilities. The questionnaire includes 18 questions. There were many strategies to analyze data after collected. The researchers counted the frequency of each question, and computed the mean as a measure of central tendency. Also, standard deviation and variance were calculated to perform the t-test. From the mean or average of both manual based system and online system, the researchers compared the computed mean to see if the use of online system is much better than manual system. Also, from the result of t-test, the researchers decided if the null hypothesis will be accepted or not.  
 
 
 
 
 
 
 
 
 
 
 
                
 
 
 
                       
 
 
 
 
 
 
 
 
 
 
                       CHAPTER 4: PROPOSED SYSTEM     
 
The researchers were able to design, and develop an online blood bank management system using PhP and MySQL for the back-end database. Below are sample screenshots of the developed system 
 
 
 
 
 
 
 
 
 
 
 
  
 
 
 
  
CHAPTER 5: SUMMARY, CONCLUSIONS & 
RECOMMENDATIONS 
 
 
 
                        Summary  
 
 
The researchers conducted this applied research to examine and evaluate on how online blood bank management system (OBBMS) can enhance blood transfusion safety. The researchers aimed to design, design, and implement this OBBMS. The researchers used both descriptive and experimental design methods. The researchers floated and administered questionnaire through online to hospital administrators, doctors, and blood bank receptionists from the various hospital in the North Al-Batinah Regions. Further, based on the gathered data, means, standard deviations, and t-value were computed. These computed values were analyzed and interpreted. Based on the findings and results, conclusions and recommendations were made.  
 
 
 
 
 
 
 
                      
  Conclusion 
 
 
 
 Based on results, this study concluded that online blood bank management system is much better than the manual system. The findings showed that respondents prefer to use online blood bank management system rather than the manual system because it offers many advantages and benefits that lead to its effectiveness, and efficiency. Because of the increased confidence on the users on the system, it can be concluded that the online blood bank management system enhances blood transfusion safety because it provides better ways of handling the various processes in blood bank.  
 
 
 
 
 
 
 
 
 
 
 
 
 
 
                  
 Recommendations  
 
 
In view of the findings, the researchers recommend that implementation of online blood bank management system. Further, the researchers recommend that further studies on how online blood bank management system enhances blood transfusion safety can be undertaken to strengthen this study’s findings. This requires actual implementation of the online system and evaluates how the users respond after implementation. This study recommends that it should be roll out across the Sultanate of Oman. Likewise, to ensure that there will be better user engagement, user manuals and proper user training should be given. Lastly, this study recommends that the system can be expanded by allowing donors to register online and be a system user, and these donors will be informed about the planned blood donation activities through the online. 
