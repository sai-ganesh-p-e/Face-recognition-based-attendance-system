# Face-recognition-based-attendance-system
A Desktop application for generating a list of absentees and mailing it to the concerned faculty from a live photo of the classroom.

Project structure :
- DBmanager_dlib.py : script for managing database, each time database is updated, classifier is trained and saved.
- sendList.py : script for loading the saved classifier, taking image of classroom and generating and sending mail after identifying absentees.

Technologies used :
- Programming language : Python
- Database : MongoDB
