# unravel
if wanting to add any new items
- go to the admin site ( the code for admin site is in the core section)
- create more categories and add more items within the category 
- the data for the web page and the connection between the codebase and the webserver database is managed in urls.py. 
- when making changes to the code base please make sure the urls.py is configured to show the changes in the web page.

## Future Improvements
- Real-time messaging using WebSockets  
- Payment gateway integration  
- AI-based recommendation system  
- Notification system  
- Cloud deployment (AWS / Heroku)  

---

## Setup Instructions

1. Clone the repository  
2. Navigate to the project folder  
3. Install dependencies:
   ```bash
   pip install -r requirements.txt

   python manage.py migrate

   python manage.py runserver

   This project demonstrates the development of a full-stack web application with integrated user interaction, database relationships, and backend logic. It focuses on building a scalable and practical marketplace system rather than just basic CRUD functionality.
