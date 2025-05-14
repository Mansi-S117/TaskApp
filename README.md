# TaskApp 📝

TaskApp is a simple and effective task management application. This project is built with Django and uses PostgreSQL for data storage.

## 🚀 Getting Started

Follow the steps below to set up and run the project locally.

---

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/taskapp.git
cd taskapp
```

### 2.  Create virtual environment
```bash
python -m venv venv
```
# Activate the environment
# On Windows:
```bash
venv\Scripts\activate
```
# On macOS/Linux:
```bash 
source venv/bin/activate
```

### 3.  Install Requirements
```bash
pip install -r requirements.txt
```

### 4.  Install PostgreSQL
If you don’t already have PostgreSQL installed, download it from:

🔗 https://www.postgresql.org/download/

### 5. Set Up the PostgreSQL Database
Once PostgreSQL is installed, create a database and user for the project:


-- Open the PostgreSQL shell and run the following:

-- Create a database
```bash
CREATE DATABASE taskapp_db;
```

-- Create a new user with a password
```bash
CREATE USER taskapp_user WITH PASSWORD 'yourpassword';
```

-- Give the user full access to the database
```bash
GRANT ALL PRIVILEGES ON DATABASE taskapp_db TO taskapp_user;
```
Replace taskapp_db, taskapp_user, yourpassword with your database name, user name and password respectively

### 6.  Create a .env File
In the root directory of the project, create a file named .env and add the following configuration details:

```bash
NAME=taskapp_db
PASSWORD=your_db_password
EMAIL_HOST_USER=your_email@example.com
EMAIL_HOST_PASSWORD=your_email_password
DEFAULT_FROM_EMAIL=your_email@example.com
```

### 7. Run Database Migrations
```bash
python manage.py migrate
```

### 8.  Start the Development Server

```bash
python manage.py runserver
```

## This is the signup page where the users can register themselves to use the taskapp

![task_register](https://github.com/user-attachments/assets/853b22ff-c0ef-4607-9696-7d72ccdaad25)

## This is the login page for the taskapp

![task_login](https://github.com/user-attachments/assets/2c43746a-7a9e-47b8-a147-5352964d3909)

## As the user signin they are redirected to the homepage where they can see the task they have assigned to others also they can see the options to edit, delete and view the tasks 



![assigned_task_list](https://github.com/user-attachments/assets/cec2439b-bfba-47f0-b055-f4d3be6aa652)


## The users can assign new task to others 

![assign_task](https://github.com/user-attachments/assets/4cbc76ed-cfa0-413a-8198-9be3747cddec)

## The user can see the task assigned to them by others in the my tasks section

![my_tasks](https://github.com/user-attachments/assets/9f002ee9-5d04-4c8d-a688-140361cd0acf)

## The users also has the option to view all the tasks in the all task section

![all_tasks](https://github.com/user-attachments/assets/967bcbfe-b75c-406c-be1b-06f48b4ac608)


## They can also view the task details 

![task_detail_1](https://github.com/user-attachments/assets/7b21c569-5898-4559-9514-cb8f23071f50)


## The users can also comment on the tasks 

![comment1](https://github.com/user-attachments/assets/d52ee509-c247-4a8e-84ad-5bb7cbd7c18d)

![comments_2](https://github.com/user-attachments/assets/c0172c52-2a56-419e-8dbd-627668b27d17)


## The user can update the status of the tasks assigned to them which indicates if the task is completed or inprogress

![update_task_status](https://github.com/user-attachments/assets/88eb8f8c-869e-460b-b225-21aba6ab65d6)


## The user can only update the task status if the previous task assigned to them is completed 

![update_restriction](https://github.com/user-attachments/assets/a095a591-2e73-43aa-aafb-781687581a54)


## The user can search any task based on the assignee or assigned to or the task name

![search_task](https://github.com/user-attachments/assets/7d63c60e-4d06-42b9-876c-0b411ec6afea)


## The user recieves an email as soon as they are assigned any task

![task_email](https://github.com/user-attachments/assets/9ee47885-83ee-408d-84a9-aaa6d8bc2680)






