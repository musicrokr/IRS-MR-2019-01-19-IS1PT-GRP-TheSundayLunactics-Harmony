---

## SECTION 1 : PROJECT TITLE
## Harmony: Enhancing DoReMi's Order and Inventory Management process

<img src="Miscellaneous/HarmonyHeader.png"
     style="float: left; margin-right: 0px;" />

---
## SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
The pervasive shift of retail towards e-commerce is threatening the existence of traditional  brick and mortar businesses. DoReMi, a specialized music retailer, faces an uphill challenge in dealing with the forces of change and finds itself in a precarious situation. Several factors, namely its lack of product diversification, limited channels of purchase and its limited adoption of technology exacerbates DoReMi’s current situation. If DoReMi fails to address existing internal challenges, it will be ill equipped to survive in the digital era.

The Sunday Lunatics (TSL) is engaged to provide consultancy services to identify areas of improvements for DoReMi and solutions to help propel DoReMi into the ecommerce space. Through extensive information gathering with the staff of DoReMi, TSL has converted years of tacit knowledge into documented knowledge models. TSL has proposed new business workflows leveraging on the Knowledge Models developed, to enable faster decision making and more timely delivery of orders. The completion of the entire project can help DoReMi achieve cost savings through value creation from process automation and upskilling of workforce as well as value add in productivity from the overall enhanced efficiency and supply chain management.

Due to the diverse nature and complexity of implementation, TSL recommends a phased approach towards the implementation of Harmony. The challenges related to Sales & Pricing and Logistics & Supply Chain Management are assessed to be more critical and TSL recommends prioritizing these challenges. The remaining challenges relating to Point-of-Sale system and detailed Project Management will be addressed in subsequent phases of the consultancy.

The objective of Harmony, the Proof of Concept (POC) solution for the Order Handling and Inventory Restock processes in the initial phase is to demonstrate the implementation of the knowledge models and seek validation from DoReMi management to proceed with the next phase. Through the proposed workflows, TSL is able to execute sophisticated business rules, incorporating a multitude of factors, in automated and efficient manner. Through this, manual intervention is significantly reduced as complex decision making is offloaded to our system. This means that DoReMi staff is able to focus on higher order thinking tasks. The proposed business processes also seek to prepare DoReMi for new Inventory management concepts such as ‘Just In Time’ inventory, where no or limited inventory to stored,allowing DoReMi to save on warehousing costs. 

The technologies used in our POC solution are a combination of Angular, Drools and java Business Process Model (jBPM).

---
## SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name  | Student ID  | Work Items | 
| :------------ |:---------------:| :-----| 
| Tan Jun Khiang | A0195169N | Project Report, Knowledge Modelling and Drools| 
| Tan Wei Lian | A0048135J | Angular Web Application, Environment Set Up, JBPM|
| Tang Meng | A0137099U | Angular Web Application,JBPM| 
| Leong Jun Hun, Darryl | A0195318X | Project Report, Knowledge Modelling and Drools| 

---
## SECTION 4 : VIDEO OF SYSTEM MODELLING & USE CASE DEMO

[![Sudoku AI Solver](https://www.youtube.com/watch?v=vooP6BmJ4l4&feature=youtu.be)](https://www.youtube.com/watch?v=vooP6BmJ4l4&feature=youtu.be "Sudoku AI Solver")


---
## SECTION 5 : USER GUIDE

`<Github File Link>` : <https://github.com/musicrokr/IRS-MR-2019-01-19-IS1PT-GRP-TheSundayLunactics-Harmony/blob/master/UserGuide/The%20Sunday%20Lunatics%20%20-%20Harmony%20User%20Guide.pdf>

### [ 1 ] To run the system in Linux Server

> open terminal/git bash

> $ git clone //todo:git_url

> unzip folder

> $ cd folder_location/DoRemi-service

> make sure jdk 1.8 installed

> make sure maven installed

> $ chmod 777 launch.sh

> $ ./launch.sh clean install

> **Go to URL using web browser** Should be able to see a page with content "DoReMi-service-1.0-SNAPSHOT" via http://localhost:8090 

> **Install Node.js** https://websiteforstudents.com/install-the-latest-node-js-and-nmp-packages-on-ubuntu-16-04-18-04-lts/

> $ sudo apt install curl

> $ curl -sL https://deb.nodesource.com/setup_10.x | sudo bash -

> $ sudo apt install nodejs

> $ cd folder_locatioin/ang-doremi

> $ npm install -g @angular/cli

> $ npm install

> $ ng serve --open

> **Go to URL using web browser** http://localhost:4200

**The default configuration is running under h2 in-memory database**

**Once the backend application is stopped, all the data will be lost**

**To persist the data, the backend application support running on actual database server**

### [ 1 ] To run the backend application in PostgreSQL

**Refer to** https://docs.jboss.org/jbpm/release/7.17.0.Final/jbpm-docs/html_single/#_run_your_business_application **for more details**

> install postgreSQL 11.1

> $ cd folder/location/DoReMi-service

> $ psql -U postgres -f psql-script/create-user-db-grant.sql

> ** change application configuration **

> $ rm src/main/resources/application.properties

> $ mv src/main/resources/application-postgres.properties src/main/resources/application.properties

> $ ./launch.sh clean install -Ppostgres
---
## SECTION 6 : PROJECT REPORT / PAPER

`<Github File Link>` : <https://github.com/musicrokr/IRS-MR-2019-01-19-IS1PT-GRP-TheSundayLunactics-Harmony/blob/master/ProjectReport/The%20Sunday%20Lunatics%20%20-%20Harmony%20Project%20Report.pdf>

---
## SECTION 7 : MISCELLANEOUS

N.A.

---

**This [Machine Reasoning (MR)](https://www.iss.nus.edu.sg/executive-education/course/detail/machine-reasoning "Machine Reasoning") course is part of the Analytics and Intelligent Systems and Graduate Certificate in [Intelligent Reasoning Systems (IRS)](https://www.iss.nus.edu.sg/stackable-certificate-programmes/intelligent-systems "Intelligent Reasoning Systems") series offered by [NUS-ISS](https://www.iss.nus.edu.sg "Institute of Systems Science, National University of Singapore").**

**Lecturer: [GU Zhan (Sam)](https://www.iss.nus.edu.sg/about-us/staff/detail/201/GU%20Zhan "GU Zhan (Sam)")**

[![alt text](https://www.iss.nus.edu.sg/images/default-source/About-Us/7.6.1-teaching-staff/sam-website.tmb-.png "Let's check Sam' profile page")](https://www.iss.nus.edu.sg/about-us/staff/detail/201/GU%20Zhan)

**zhan.gu@nus.edu.sg**
