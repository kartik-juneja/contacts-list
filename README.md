# contact-list 
# If you want to see the working of project you can directly go to [kartikjuneja.pythonanywhere.com](https://kartikjuneja.pythonanywhere.com/)

# Running the Django Phonebook Application

To run the Django Phonebook Application, follow these steps:

## Prerequisites

1. Make sure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).

2. Clone the project repository to your local machine:

    ```bash
    git clone https://github.com/kartik-juneja/contacts-list
    ```
## Installing Dependencies

3. Install django using pip:

    ```bash
    pip install django
    ```

## Creating a Superuser (Admin User)

4. Create a superuser to access the Django admin interface:

    ```bash
    python manage.py createsuperuser
    ```

    Follow the prompts to set up your admin user.

## Running the Development Server

5. Start the development server:

    ```bash
    python manage.py runserver
    ```

    The project will be accessible at [http://localhost:8000/](http://localhost:8000/).

## Accessing the Admin Interface

6. Open the Django admin interface in your browser:

    [http://localhost:8000/admin/](http://localhost:8000/admin/)

    Log in with the superuser credentials you created earlier.

## Using the Phonebook Application

7. Access the phonebook application at:

    [http://localhost:8000/phonebook/](http://localhost:8000/phonebook/)

    Here, you can add, list, edit, delete records, and search for contacts by name.



