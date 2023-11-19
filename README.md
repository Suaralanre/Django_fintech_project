# Fintech Application 

This is a fintech application written with the django framework that allows users to save, send and receive money . It includes:
- A robust authentication and permission with a mandatory KYC on signup
- An customized django admin section that gives the super user control over user accounts.
- A dashboard for the user that displays every individual transactions.
- Notifications for every transaction.
- Stripe integration
- A simple, easy to use,front end built with bootstrap V5.0
- And many more features.

## Usage
> To run this project on your local machine (**assuming you have python3.9+ installed**):
- Create a directory for the project on your local machine(e.g.fintech_app)
- Navigate to the folder on your terminal(e.g. cd ~/Document/fintech_app)
- clone the project:  ###########
- create a virtual environment: ```python3 -m venv .venv```
- run the following commands:
> - ```pip -r install requirements.txt```
> - ```python manage.py makemigrations``` 
> - ```python manage.py migrate``` 
- start your [localhost](http:127.0.0.1:8000)

### Possible Add-ons
 I still hope to keep working on this project. Features I hope to add include:
- Robust unit testing
- Change all views to class-based views/generic class-based views
- Cryptocurrency integration 
- 2FA/MFA Authentication
- Improve the look of the front-end.


> Please feel free to create an issue to make contributions/criticisms of the project. If you prefer to be anonymous, please feel free to leave a message via [my email](mailto:lanresuara@gmail.com) Cheers.