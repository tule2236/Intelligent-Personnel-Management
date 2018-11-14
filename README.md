# Digitization of Government Systems:
## Philippine Navy Seals Special Operations Group

## Motivation
There are two main forms of merit within the Navy Seals Special Operations Group; getting promoted to a higher rank and being awarded scholarship opportunities. Although the group has a quantitative model for rank promotions, they do not have access to decision making tools for scholarship awards. Their current system relies on the discretion of the management committee and is limited by the memories of officers present during the meeting. All soldier information is stored in physical files; leaders and administrators do not have any digital database to perform queries on. Since military education is an important component for the rank promotion model, the management committee wants to make more informed decisions by focusing on updated and accessible soldier data. 

## Goal
Our goal is to develop a personnel information dashboard to aid the management committee in making decisions on scholarship awardees. Their current process involves the physical location of personnel files and sorting qualified records into a pile, which is then analyzed by leadership during committee meetings. 

## Attributes
Through an initial interview, some personnel attributes include the following:
![alt text](https://user-images.githubusercontent.com/30711638/48460744-78108e00-e79e-11e8-9e4e-5d0fd25afc6c.png)

## Development Checklist
1. Analysis of attributes - understand the relative priorities of soldier attributes and how they
relate to scholarship.
2. Initial System Design - develop wireframes of the system.
3. Dashboard Components - justification for dashboard design and components.
4. Sprint Backlogs - detailed schedule of deliverables.
5. Conduct usability studies
6. Iterate and refine product
7. Benchmark project impact

## UI Design
### Product Features
To solve the current problems of the Navy Seals Special Operations Groups, we have developed a basic personnel management system. The product is a cross-platform desktop application that provides the group with three main capabilities; to digitize current records, analyze trends and personnel structure, and comparison of personnel for promotion decision
making.

![alt text](https://user-images.githubusercontent.com/30711638/48460747-7a72e800-e79e-11e8-82d8-602485545430.png)
The login function is used to identify and authenticate users. The initial application will be used by administrative personnel, but we will maintain the ability to assign different access levels to users to protect sensitive information at scale. In addition, it can create an event log for each user to keep tracking their access history for security purpose. The event log file will help us to diagnose problems in the system.

![alt text](https://user-images.githubusercontent.com/30711638/48460753-7d6dd880-e79e-11e8-98d0-12a0e42db495.png)

In order to promote usability and clearly identify the affordances of the Phoenix system, we have developed the main page to directly showcase the capabilities of our application. Links to the four main features are outlined; view personnel, store information, understand their current human resource infrastructure, and make decisions through personnel comparisons. 

Through various interviews, we qualitatively determine the technical skill level and access of the leadership and operating personnel of the Navy Seals Special Operations Group. We have been developing the product under the assumption that the various personnel in the group do not work with technology on a daily basis. Therefore, it was imperative that we designed the application to cater to novice users.

![alt text](https://user-images.githubusercontent.com/30711638/48461071-e144d100-e79f-11e8-9ea4-f7d186fad229.png)

For the view personnel page, we have developed basic functionality to fill tables from local databases. This has two unique and critical benefits for the group; minimized security concerns and easily accessible information. We have also included an image of a pencil to allow administrative personnel to edit information from the page itself. This promotes the usability principle of recognition over recall.

One important feature that we plan to add to this page is a filter that will allow NavSOG’s leadership to divide their workforce into useful subsets that will give them a better understanding of their current workforce. In order to integrate this feature effectively, we have planned to do more research into the various needs of the local leadership. Some useful information we need to move forward include:
●	Relative importance of each tracked feature
●	Other useful attributes outside of our current list
●	Their current evaluation heuristics
●	Post-decision evaluation
From our initial evaluation, we found this area to be the most relevant to reducing their current decision-making process. The main complaint we received from the group involved filtering of personnel by qualification. 

![alt text](https://user-images.githubusercontent.com/30711638/48460759-7fd03280-e79e-11e8-8a2b-3ef86b7e9a25.png)
The “add personnel” interface of our application will be used as the main point of the digitization of current soldier records. 

## Dashboard
For the Dashboard, we focus on the management on the whole squad instead of individual. There is five features for showing you the detail of the squad: Cities, Average Time To Leave, Type Unit, Experience and ratio of officer and enlisted. By clicking on those feature, you can filter those information that you don’t need. 

During our visit to the Navy Seals HQ, we learned that their team was interested in getting a general overview of their teams. Due to the decentralized and varied nature of missions around the country, the management committee 

![alt text](https://user-images.githubusercontent.com/30711638/48460769-88c10400-e79e-11e8-8dab-ea9b1661ef79.png)

The dashboard will have two main filters, located on the top left (map) and mid left (type unit) sections. Since the main purpose of the interface is to provide information on teams, we used a map of the Philippines to display all deployed teams around the country.

![alt text](https://user-images.githubusercontent.com/30711638/48460784-92e30280-e79e-11e8-8034-1a8974eaace0.png)

Clicking on the city of a team will filter the information to show the commanded relevant indicators for the selected team. The filters can be nested, added, and removed based on the immediate specifications of the management committee

![alt text](https://user-images.githubusercontent.com/30711638/48460786-96768980-e79e-11e8-90d3-80215e896b58.png)

## Feature Timeline
Although the initial product focuses on personnel management, we have identified several operational areas that will be useful to the group in the foreseeable future. A natural extension to the current application is related to measuring recruitment strategies and providing the group with insights into how they can efficiently expand their footprint in the country. 

Furthermore, we believe the application can be extended to include various operational information on the group. We plan to integrate various external data sources to help the group improve their decision-making process for broader facets of strategy, such as mission priority development. We also plan to include simulation and optimization capabilities into the application to provide the group’s leadership with both predictive and prescriptive affordances that will allow them to maximize the use of unstructured data sources.

![alt text](https://user-images.githubusercontent.com/30711638/48460791-9a0a1080-e79e-11e8-9ce0-e8b6e0d0eb57.png)