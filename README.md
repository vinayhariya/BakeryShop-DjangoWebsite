# E-Commerce Website
### Created by Vinay Vinod Hariya
#### finished on 1<sup>st</sup> April, 2021
<br>

For Demo, click [here]().

On the localhost (local machine)

Follow the steps perfectly for successful installation:

- Ensure python is installed on your system. (Version 3.9 and above)
- Open the command promt (or equivalent) on the system.
- Navigate inside to the outer folder housing the project folders and files.
- Type the following command (instead of ```.env```, you can give any name)
    
    ```
    python -m venv .env
    ```

- Activate the ```.env``` virutal environment
    - For Windows, type the following
        ```
        .\.env\scripts\activate
        ```
    - For Mac and Linux, type the following
        ```
        source .env/bin/activate
        ```
- To install all the related packages, type ```pip3```:
    
    ```
    pip3 install -r requirements.txt
    ```

- Run the following 2 commands to make sure the db is connected properly and no errors will occur
    
    ```
    python manage.py makemigrations
    python manage.py migrate
    ```

- To make a superuser (to access the admin panel), type: 
    
    ```
    python manage.py createsuperuser
    ```
  And, fill in the details

- Run the following command to start up the website: (```python3``` for mac and linux users)
    
    ```
    python manage.py runserver
    ```