# ElectraVote

## Short Description
ElectraVote is a voting system built using the Django framework that utilizes JavaScript APIs to create interactive voting results charts. The system includes features such as user login, registration, profile management, and a main screen displaying voting information.

## Features
- **Login**: Allows users and administrators to log into their accounts.
- **Registration**: Enables users to sign up or register their email address before logging in.
- **Update Profile Admin**: Admins can edit or update their information within the database.
- **Logout**: Users and admins can log out of their accounts.
- **Display Results**: Users can view the voting results after casting their votes.

## Packages Used
- **Django**: A high-level Python web framework that encourages rapid development and clean, pragmatic design.
- **SQLite**: A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.
- **JavaScript APIs**: Used for creating interactive voting results charts.
- **asgiref**: A package for managing asynchronous server gateways.
- **django-cleanup**: Automatically deletes files for FileField, ImageField, and subclasses.
- **django-crispy-forms**: The best way to have Django DRY forms.
- **Pillow**: Python Imaging Library (PIL) fork.
- **pytz**: World Timezone Definitions for Python.
- **sqlparse**: A non-validating SQL parser.

## Functional Requirements
1. User Registration and Login: Users must be able to register and log into the system.
2. Profile Management: Users should be able to update their profile information.
3. Voting: Users must be able to cast votes.
4. Result Display: The system should display voting results in an interactive chart.
5. Logout: Users should be able to log out of the system securely.

## Tools Used
- **VS Code**: A source-code editor made by Microsoft for Windows, Linux, and macOS.
- **Python**: A high-level, interpreted programming language.
- **Django**: A high-level Python web framework.
- **SQLite**: A C-language library that implements a small, fast, self-contained SQL database engine.
- **AdobeXd**: A vector-based user experience design tool for web apps and mobile apps, developed and published by Adobe Inc.

## Usage
To use the ElectraVote system, follow these steps:
1. Register a new user account or log in with an existing account.
2. Update your profile if necessary.
3. Participate in the voting process.
4. View the results displayed in an interactive chart.

## How to Configure Django Project
1. **Clone the repository**:
    ```bash
    git clone https://github.com/saeed123991/electraVote.git
    cd electraVote
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment**:
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On MacOS/Linux:
        ```bash
        source venv/bin/activate
        ```

4. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

5. **Apply migrations**:
    ```bash
    python manage.py migrate
    ```

6. **Run the development server**:
    ```bash
    python manage.py runserver
    ```

## How to Create and Run Virtual Environment and Install Requirements
1. **Create a virtual environment**:
    ```bash
    python -m venv venv
    ```

2. **Activate the virtual environment**:
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On MacOS/Linux:
        ```bash
        source venv/bin/activate
        ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## How to Create Superuser
1. **Create a superuser**:
    ```bash
    python manage.py createsuperuser
    ```

2. **Follow the prompts to create a username, email, and password for the superuser.**

3. **Log in to the admin panel**:
    ```bash
    http://127.0.0.1:8000/admin
    ```
4. **Use the superuser credentials to access the admin interface.**

## Contributing
Saeed123991

## License
This project is licensed under the MIT License.
