Author_Book                                                                                                                              
Project name - Library                                                                                                                                 
Api - This Django app provides a REST API for managing Author and Book in the Library platform                                                                             

INSTALLATION                                                                                

Clone the repository:   https://github.com/sharuhaasan/Author_Book                                                                                                            
Navigate to the project directory:   cd Author_Book                                                                                   
Create a virtual environment:   python3 -m venv venv                                                                           
Activate the virtual environment:   venv\Scripts\activate                                                                                                  
Install the dependencies:   pip install -r requirements.txt                                                                                              
Set up the database:   python manage.py makemigrations and python manage.py migrate                                                                            

USAGE

settings.py                                                                                             
models.py                                                                                                    
serializers.py                                                                                                                
views.py                                                                                                                    
urls.py (Api)                                                                                                                     
urls.py (Library)                                                                                                          

Start the development server:          python manage.py runserver                                                                         

Access the API endpoints:

Create New author: POST /api/authors/                                                                        
List All authors: GET /api/authors/                                                                                      
Retrieve details of a specific author by ID: GET /api/authors/<int:id>/


Create New book: POST /api/books/                                                                               
List All books: GET /api/books/                                                                                       
Retrieve details of a specific book by ID: GET /api/books/<int:id>/                                                                    

SAMPLE API

http://127.0.0.1:8000/api/authors/ -- (POST) To create new author                                                                                     
http://127.0.0.1:8000/api/books/ -- (GET) Lists all existing books                                                                   
http://127.0.0.1:8000/api/authors/1/ -- (GET) To retrieve the details of existing author using author_id                       


