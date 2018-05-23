# Database
A database is a set of structured information. The information contained depends entirely on your subject. For a taxi comapany the information, contained within, would consist of names, addresses, pricing, ect. Whereas for a game, you would have statistics such as HP (Health Points), AT (Attack Damage), Level and so on. The information is contained in various 'Tables'. Within these 'Tables' of columns called 'Field's'. The 'Field's' house the specified statistic information that makes up the table.    


## Entity Relationship Diagram (ERD)


### What is it?
ER-modeling is a data modeling technique used in software engineering to produce a conceptual data model of a information system. Diagrams created using this ER-modeling technique are called Entity-Relationship Diagrams, or ER diagrams or ERDs. So you can say that Entity Relationship Diagrams illustrate the logical structure of databases.


**Below is the ERD I made for my database:**


![](https://i.imgur.com/5vEVdFi.png)


## Data Dictionary


![](https://i.imgur.com/7kqx1X9.png)


## User Stories


"As a user I would like to see a list of BLUETEAM's characters"


"As a user I would like to see a list of REDTEAM's characters"


"As a user I would like to see the damage statistic for each character in BLUETEAM"


"As a user I would like to see the damage statistic for each character in REDTEAM"


"As a user I would like to see a list of Weapon's"


"As a user I would like to see the overall damage of Characters, combined with their associated weapon"


## System Requirements


"I need to be able to see a list of BLUETEAM's characters"


"I need to be able to see a list of REDTEAM's characters"


"I need to be able to see the damage statistic for each character in BLUETEAM"


"I need to be able to see the damage statistic for each character in REDTEAM"


"I need to be able to see a list of Weapon's"


"I need to be able to see the overall damage of Characters, combined with their associated weapon"



## Forms and Validation


**Form**

Form showing a 'BLUETEAM' Character 'NAME', 'DAMAGE', and 'HP'.


![](https://i.imgur.com/HRf9BED.png)


Form showing the 'OVERALL DAMAGE' of 'BLUETEAM_ID' + 'WEAPON_ID' 


![](https://i.imgur.com/tGHVygs.png)


**Validation** 


![](https://i.imgur.com/Zs2PO62.png)
![](https://i.imgur.com/azOmQ8s.png)


## Reports

Report showing all 'BLUETEAM' Character's 'NAME', 'DAMAGE', and 'HP'.


![](https://i.imgur.com/PmlRXEd.png)


Report showing the 'OVERALL DAMAGE' of 'BLUETEAM_ID' + 'WEAPON_ID'


![](https://i.imgur.com/Rue1B61.png)



## Test Plan


![](https://i.imgur.com/kiTTOht.png)


## SQL Commands

**Create**
To create a 'Table' in 'Microsoft Access' i used SQL code. I used the following command to produce the desired result:

```SQL
CREATE TABLE BLUETEAM (
  ID INT NOT NULL PRIMARY KEY,
  NAME VARCHAR(50) NOT NULL,
  HP FLOAT NOT NULL,
  DAMAGE FLOAT NOT NULL
  );
```

**Insert**
To insert information into my newly created table I used the following SQL command:

```SQL
INSERT INTO BLUETEAM VALUES(
1, '
```

**Update**


**Delete**


**Select**
