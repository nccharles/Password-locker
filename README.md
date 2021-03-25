# Password Locker

## Built By [Charles](https://github.com/nccharles250/)

## Description
Password Locker is a python application runs in terminal that helps us manage our passwords and even generate new passwords for us.

## User Stories
These are the behaviours/features that the application implements for use by a user.

As a user:
* I want to create a password locker account with my details, a login username and password.
* I want to store my already existing account credentials in the application. Assuming I already have a twitter account, I want to store my already existing twitter username and password in the application.
* I want to create new account credentials in the application. For example, if I have not yet signed up for Instagram, I would want to create a credentials account for Instagram in the application and the application generates a password for me to use when I sign up for Instagram.
* I want to have the option of putting in a password that I want to use for the new credential account. For example, when creating my Instagram credential account, I want to have an option of putting in the password I want to use instead of having the application generate a password for me.
* I also want to view my various account credentials and their passwords in the application.
* I want to delete a credentials account that I no longer need in the application.

## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display codes for navigation | **In terminal: $./password_locker.py** | Welcome, choose an option: ca-Create Account, li-Log In, ex-Exit |
| Display prompt for creating an account | **Enter: ca** | Enter your first name, last name and password |
| Display prompt for login in | **Enter: li** | Enter your account name and password |
| Display codes for navigation | **Successful login** | Choose an option: cc - Create Credential, dc - Display Credentials, copy - Copy Credential, ex - exit |
| Display prompt for creating a credential | **Enter: cc** | Enter the site name, your username and password |
| Display a list of credentials | **Enter: dc** | Prints a list of saved credentials |
| Display prompt for which credential to copy | **Enter: copy** | Enter the site name of the credential you wish to copy. |
| Exit application | **Enter: ex** | Exit the current navigation stage |

## SetUp / Installation Requirements
### Prerequisites
* python3.8
* pip
* pyperclip
* xclip

### Cloning
* In your terminal:
        
        $ git clone https://github.com/marynganga/Password-Locker/
        $ cd Password-Locker

## Running the Application
* To run the application, in your terminal:

        $ chmod +x password_locker.py
        $ ./password_locker.py
        
## Testing the Application
* To run the tests for the class file:

        $ python3.8 user_credentials_test.py
        
## Technologies Used
* Python3.8

## License
MIT &copy;2021 [Charles NDAYISABA](https://github.com/nccharles250/)

