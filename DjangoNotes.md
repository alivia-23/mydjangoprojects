# Django Setup

## Step 1: Create a Project Directory
Begin by creating a directory for your Django project:

```python
mkdir my_django_project
cd my_django_project
```
## Step 2: Initialize a Virtual Environment
Create a virtual environment in your project directory using Python’s venv:

`python -m venv myenv`
This command initializes a virtual environment named myenv.

## Step 3: Activate the Virtual Environment
Activate the virtual environment based on your operating system:

**On Windows:**
`myenv\Scripts\activate`

**On macOS and Linux:**
`source myenv/bin/activate`

The virtual environment is now active.

## Step 4: Install Django
With the virtual environment active, you can install Django using pip:

`pip install django`

## Step 5: Create a Django Project
Create a Django project within the virtual environment:

`django-admin startproject projectname`

## Step 6: Navigate to the Project Directory
Change your working directory to the newly created Django project:

`cd projectname`

By following these steps, you have successfully set up a Django project using Python’s built-in venv. This approach provides a basic yet effective way to isolate your project's environment.