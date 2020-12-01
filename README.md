# Ecommerce site
An e-commerce website 
# Tech-Used
### Frontend-HTML/CSS/BOOTSTRAP/JAVASCRIPT/JQUERY
### Backend-DJANGO(PYTHON)

# About
This is an ecommerce website where a user can buy any product and checkout it an order id will be given to the user , which user can use to track their order 
### Tracking-
A graph is made in the javascrt connecting around 30-35 destinations user can select any destination near toi their location , and the product will be transported from the main center to the center user has selected, there are three main centers Mumbai, Kolkata, Delhi , the user is able to track the path which will be taken by the deleivery company to deliver their product , The path will be the shortest path  so as to save the uer time

## Algorithm Used-
Dijakstra Algorithm is used to find the shortest path between the main center and the selected center by the user , dijakstra algorithm works in o(v2) time and o((E+V)logv)) if priority queue is used , At first The main center which is near to the user's center is selected then the path will be calculated using dijakstra algorithm and will be displayed to the user interface using library in javascript

# How to Run Website Locally On your machine
1.Download Pyhton <br />
2.Download Django <br />
3.Clone the repository in ann directory <br />
4.In your terminal Move into the directory <br />
5.Move into the mac folder inside CODE folder <br />
6.Run Command python manage.py runserver <br />
7.Move to the url localhost:8000 in your browser <br />
