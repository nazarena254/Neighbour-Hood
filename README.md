# Neighbourhood

## Description
Django web application where users will be creating, searching, deleting and editing businesses, neighborhoods and posts.

## Author
Nazarena Wambura.</br>
[Github Account](https://github.com/nazarena254)

<!-- ### Homepage
![nazawwards](./awwardsapp/static/images/awwards.png)
### Admin panel
![nazawwards](./awwardsapp/static/images/adminawwards.png) -->


## User Story
- A user can sign in with the application to start using.
- A user can set up a profile about me and a general location and my neighborhood name.
- A user can find a list of different businesses in my neighborhood.
- A user can create posts that will be visible to everyone in my neighborhood.
- A user can change their neighborhood when I decide to move out.
- A user can find contact information for health department and Police authorities near my neighborhood.
- A user can only view details of a single neighborhood.


## Setup/Installation Requirements
1. Create a folder and cd to it.
2. Clone the repository below with the command `git clone <https option url> .`  <br>
    https://github.com/nazarena254/Neighbour-Hood  
3. Install dependencies in the requirements.txt file `pip install -r requirements.txt` .
4.  Type code . or atom . based on the text editor you have and work on it.   

## Database
1. Set up Database(postgresql),and put your username and password in the code
2. Make migrations
    python3 manage.py makemigrations
3. Migrate
   python3 manage.py migrate 
       
## Running the Application
1. Run main aplication locally on http://127.0.0.1:8000/ local host<br>    
   * python3.9 manage.py runserver<br>
    Note: python version will vary in future

## Creating Admins
1. Creating Admin Locally<br>
     python manage.py createsuperuser. Then set username, email & password

2. Creating Django Admin   
     heroku run python manage.py createsuperuser. Then set username, email & password

## Technologies Used
* Python3.9.2 - as backend language
* Django4.0.5 - as a Framework
* Bootstrap4 - for responsiveness & styling 
* PostgreSQL - as database
* Cloudinary - as cloud-based image storage server
* Heroku - for deploying app

## Support & Contact Information
For any further inquiries, bugs, contributions or comments, reach me at:<br>
Email:<nancyngunjiri1@gmail.com>

## License
[MIT License](https://github.com/nazarena254/Neighbour-Hood/blob/master/LICENSE)<br>
Copyright (c) 2021 **Nazarena Wambura**