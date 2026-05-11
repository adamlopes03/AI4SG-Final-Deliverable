# Problem 
##### Our project seeks to address the issue of overfilled trash cans on the SJSU campus. A San Jose State student by the name of Bob is noticing the prevalence of overflowing trash cans on campus. He wants to use an AI tool to quickly make a report of the trash can to the campus maintenance team, so that it can be cleaned.
# AI Capability 
##### The AI uses both image recognition and text generation to assist the user. The image recognition is the key functionality, as it allows the user to generate a report by simply taking a picture. The text generation creates a friendly face for the user to interact with, as well as explaining what to do.
# Workflow
##### Input → A student uploads an image of an overflowing trash can on campus. The student may also provide a short description of the location. 
###### Figure 1. The student uploads a photo of the overflowing trash can.
![Alt text](path/to/image.png)
##### AI Processing → The AI analyzes the image to identify the trash issue, estimate severity, and determine urgency. It also checks whether the location can be identified from the image. If the location is unclear, the system asks the student for more details, such as the building, floor, room number, or nearby landmark. 
###### Figure 2. The AI analyzes the trash can image and gives an urgency rating.
![Alt text]([path/to/image.png](https://github.com/adamlopes03/AI4SG-Final-Deliverable/blob/main/fill%20status.png?raw=true))
##### Output → The system creates a report that includes the trash issue, severity, urgency, recommended action, and whether more location detail is needed. 
##### Real-World Action → The report is sent to SJSU custodial or facilities staff so they can locate and empty the trash can. If the location is unclear, the report should be flagged for follow-up before staff are sent out.
###### Figure 3. The system creates a facilities report for staff.
![Alt text](path/to/image.png)
# Failure Case
##### One failure that the AI experienced was that it incorrectly guessed the location of the trash can. It also hallucinated a random, inaccurate date associated with the picture.
# Oversight and Tradeoff
##### Human review plays into the system by asking the user for clarification on the location of a trash can. It does this when the trash can’s location is not immediately obvious from the picture. The tradeoff in this functionality is that it makes the process less automated. The user experience would be more seamless if this step were foregone. 
