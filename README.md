# Social Website using Django 5

This is a project repository for the Social Website created using Django 5, as demonstrated in the "Django 5 By Examples" book by Antonio Mele.

The application allows users to register, log in, edit their profile, and change or reset their password. The project also includes social authentication to sign in with services such as Google,
functionality to display shared images and a system for users to share images from any website, an activity stream that allows users to see the content uploaded by the people that they follow
and a follow system to allow users to follow each other on the website.

The code in this repository is a step-by-step implementation of the project described in the book, along with some additional enhancements and modifications. It's intended as a learning resource for anyone who wants to get started with Django and build a simple web application.

## Installation and Usage
To run the application, you need to install Python 3.x and Django 5.x on your local machine. Then, clone the repository and navigate to the project directory.

```sh
git clone https://github.com/osman-yasser/Social-Website.git
cd Social-Website
```

Next, create a virtual environment and activate it:

```sh
python3 -m venv env
source env/bin/activate
```

Install the required packages:

```sh
pip install -r requirements.txt
```

Finally, run the application using the following command:

```sh
python manage.py runserver
```

Open your browser and navigate to `http://localhost:8000` to access the social website.

## Contributing
Contributions are welcome! If you find any bugs or issues with the application, feel free to create an issue or submit a pull request.

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.
