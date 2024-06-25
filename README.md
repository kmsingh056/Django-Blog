
# Django Blog
## Project Overview

This project is a Blog Website where users can create an account, post content, and perform CRUD (Create, Read, Update, Delete) operations on their posts. The website provides a platform for users to share their thoughts, ideas, and experiences with others, offering a simple and intuitive interface for blog management.

### Technologies Used

#### 1. HTML/CSS
These technologies are used for designing and styling the front-end of the website. HTML (HyperText Markup Language) structures the content on the web pages, while CSS (Cascading Style Sheets) enhances the appearance, ensuring a visually appealing and responsive design.

#### 2. Django (Python Framework)
Django is a high-level Python web framework that promotes rapid development and clean, pragmatic design. It is used to build the back-end of the blog website, handling database operations, user authentication, and the overall logic for CRUD operations on blog posts.

### Features

#### 1. User Authentication:

Users can create an account, log in, and manage their profiles.  
Secure authentication ensures that users can safely access and manage their content.

#### 2. CRUD Operations on Blog Posts:

Create: Users can write and publish new blog posts.  
Read: Visitors can read all the published posts.        
Update: Users can edit their existing posts to update content.  
Delete: Users can delete their posts if they no longer wish to keep them.

#### 3. User-Friendly Interface:

The website features a clean and intuitive interface, making it easy for users to navigate and manage their posts.
Responsive design ensures compatibility with various devices, providing a seamless experience on desktops, tablets, and mobile phones.

#### 4. Admin Panel:

Django’s built-in admin panel allows for easy management of users and blog posts.  
Admins can oversee site operations, ensuring the smooth functioning of the blog website.
## Screenshots

### Home Page
![App Screenshot](https://github.com/kmsingh056/django-blog/blob/main/Screenshots/Django%20Blog%20-%20Brave%2025-06-2024%2016_22_47.png?raw=true)

### LogIn Page
![App Screenshot](https://github.com/kmsingh056/django-blog/blob/main/Screenshots/Django%20Blog%20-%20Brave%2025-06-2024%2016_23_54.png?raw=true)

### Register Page
![App Screenshot](https://github.com/kmsingh056/django-blog/blob/main/Screenshots/Django%20Blog%20-%20Brave%2025-06-2024%2016_25_40.png?raw=true)

### Profile Page
![App Screenshot](https://github.com/kmsingh056/django-blog/blob/main/Screenshots/Django%20Blog%20-%20Brave%2025-06-2024%2016_25_16.png?raw=true)

### Post Page
![App Screenshot](https://github.com/kmsingh056/django-blog/blob/main/Screenshots/Django%20Blog%20-%20Brave%2025-06-2024%2016_24_36.png?raw=true)

### Update and Delete Page
![App Screenshot](https://github.com/kmsingh056/django-blog/blob/main/Screenshots/Django%20Blog%20-%20Brave%2025-06-2024%2016_24_18.png?raw=true)



## Run Locally

Clone the project

```bash
  git clone https://github.com/kmsingh056/django-blog.git
```

Go to the project directory

```bash
  cd django-blog
```

Install dependencies

```bash
  pip install django
  pip install crispy-bootstrap5
```

Start the server

```bash
  python manage.py runserver
```

