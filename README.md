#Task Description:

##Backend (Python or NodeJS with MongoDB):
· Load some default information cards into the DB. It can also include Social Media Profiles (e.g., Facebook, Twitter, Instagram, etc.).
· These cards should include a title, content, timestamp, and details.
· Implement a mechanism to monitor the information added to DB for specific keywords, location or attribute. When a hit occurs, the keyword is found in a document, an alert should be shown in real-time in UI.
· Store the Information Card and alerts in the MongoDB.

##Frontend (React):
· Develop an Icon Based User interface (UI) using React to Create and View Alerts as a base component.
· Each type of Alert is a component with parameters. Users can drop different types of alerts onto an Alert Component. The Type of Alert Components are Keyword, Location and Attribute components.
· Each Component has fields or attributes that can be added for creating Alerts. For example, when a keyword is added for an alert, you can also add attributes or other keywords. The system should monitor the documents associated with that keyword or attributes.
· Implement a real-time alerting system in the UI. When a document is added and contains any of the keywords associated, an alert should be displayed to the user. Including the associated document in a drill down.
· Ensure that the UI is user-friendly and responsive, and that it updates in real-time when new alerts are generated.

## Submission:

Please dockerize the app and provide us with the source code for both the backend and front-end components of the Alert Management System. You can host your project on a platform like GitHub or provide a compressed file with the code and relevant assets. Additionally, include any instructions for setting up and running the system.
