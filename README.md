# Physical-Therapy-Database
SQL Database Final Project for Database Design and Management Class

Introduction
=====================

Enterprise Overview
------------
The Bergenfield Physical Therapy & Pain Management is a physical therapy clinic based in Bergenfield, New Jersey that has an extended facility in Bloomfield, New Jersey. The facility offers physical therapy programs for patients who have suffered from injuries and impairments. Some of the services include spine rehab, sports rehab, orthopedic therapy, manual therapy, laser therapy, balance rehab, and neurological rehabilitation. 

Bergenfield Physical Therapy & Pain Management has its own website that patients can browse to get information on conditions that the clinic treats and how they treat them. With the website, patients can also fill out forms to conveniently help both staff and patient to hasten the process of the first appointment. A patient can register to either the Bergenfield facility or the Bloomfield facility depending on whichever is convenient for them. Insurance plays a role too and patients may view which medical plans are accepted at the facilities.

The company uses MediGraph, which is a Physical Therapy Software that provides a web-based documentation for patients making it convenient for finding patients’ information online. By using MediGraph, physicians can enter and modify patient information such as their basic information, diagnoses, insurance, charges, invoice and payments, history, and other important documents. It is an excellent tool for the job of keeping track of numerous patient logs and physicians can easily modify any information with ease. However, since MediGraph is proprietary, there are certain limitations for physicians when collecting information from patients.

Problems to Tackle
------------
The MediGraph software is not flexible and cannot add additional criteria if needed to. It would be more convenient if a personally-constructed database was created to run in the background and perform queries as needed by the physicians. The database administrator can add, modify, or delete certain fields which would ultimately give the Bergenfield Physical Therapy facilities more control over their data. 

Because of the vast amount of information that needs to be collected for each patient, it is important to be flexible and be coordinated with physician, lawyers, and patients. There is a heavy emphasis in communication between physicians and lawyers regarding patient information. A physical therapy database will help speed up the process by retrieving valuable information readily. Registration forms also tend to be long and tedious, but with a database, time spent writing papers will be time spent treating patients.

In addition, if the company ever wanted to create their own software, they can do freely without having to depend on MediGraph. By creating a backbone database and link it with any program that they choose, they have the capabilities to create their own mobile application that would help their business grow. Patients and physicians both can use the application and retrieve user information rather readily.
Furthermore, Bergenfield Physical Therapy tends to give out personalized letters to each and every patient. With a database and a constructed program, they can retrieve queries efficiently and print the user information rapidly. An independent database will basically give Bergenfield Physical Therapy more opportunity to expand and develop their customer service. Finally, if Bergenfield Physical Therapy ever wanted to switch to a new DBMS, then they can utilize the already developed database until the switch is done. It’s a win-win scenario for them either way.

Objective
=====================
The goal of this project is to create a functional database to be used by physicians of the Bergenfield Physical Therapy & Pain Management facilities. The database will implement any criteria physicians need along with the basic mandatory requirements. Data from the already existing MediGraph will be used to help transition in storing important data and documents. With the creation and development of this database, it will also make it easier for physicians to write letters to every patient by making queries of patient’s contact information in a convenient and organized manner. 

Description of the System
=====================

Software
------------
The University of Pittsburgh at Bradford lets the students use SQL Server Management 2017 for the Database Project. The choice of software will make the creation of the database easy to execute. Management Studio allows the user to select, modify, and delete data with ease and also enables connectivity with Visual Studio applications for retrieval of any types of data from the database.
System Functionality

A SQL Server database will store information on the following major entities: patient, physician, diagnosis, facility, insurance, and bill. Each entities have their own corresponding attributes. With the database, a physician can view important patient’s information relevant to their proper treatment. Some of the basic information are their first and last name, phone number, and place of residence. Physicians will also share the same attributes with patients. Diagnosis data will be collected by the database and will help physicians understand what the patient’s complications are. Bergenfield Physical Therapy and Pain Management only have two facilities and the database will keep track of which patient and physicians are in which ones. Insurance and bill will also play hand in hand together because insurance will be the one to pay the patient’s bills.

Business Rules
--------------
![BusinessRules](https://user-images.githubusercontent.com/54923059/71388777-bd210980-25c7-11ea-824c-57624ed0fc74.PNG)

Attribute Rules
------------------
![AttributeRules](https://user-images.githubusercontent.com/54923059/71389027-bcd53e00-25c8-11ea-8590-4175ca60041a.PNG)

Logical Data Model
------------
![LogicalDataModel](https://user-images.githubusercontent.com/54923059/71388728-80eda900-25c7-11ea-985c-c0b0d75942a7.png)

