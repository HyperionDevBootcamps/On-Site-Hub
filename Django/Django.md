## Django

- **Django Dockerfile:** [Django Capstone on Docker Hub]
    1. ######   Does the file have a python environment (`FROM`)?
    2. ######  Have you set the WORK directory?
    3. ######  Have you COPIED the requirements.txt?
    4. ######  `RUN` pip install for above requirements?
    5. ######  `COPY` everything in the working directory
    6. ######  Optionally `EXPOSE` the port 8000
    7. ######  `CMD` to run django development server?

- **Custom Form (Registration):**
    - [Stack Overflow: Django UserCreationForm Custom Fields](https://stackoverflow.com/questions/48049498/django-usercreationform-custom-fields#:~:text=You%20don%27t%20need%20to%20define%20fields%20unders%20widgets.%20Define%20them%20as%20static%20at%20class%20level.)

    - [Django Forum: Customizing User Registration](https://forum.djangoproject.com/t/django-user-authentication-customizing-user-registration/23611)
    
---