# basic-django-user-register

<p>This is a just a basic django setup with user-registration-redux ready to roll
Here's how to get going: </br>
<ol>
	<li> Fire up a virtualenv </li>
	<li> Fork this repository </li>
	<li> cd into 'basic-django-user-register'</li>
	<li> Run:<code>pip install -r requirements.txt</code></li>
	<li> Update the db settings in settings.py <br>
		<code>DATABASES = {<br>
    'default': {<br>
        'ENGINE': 'django.db.backends.postgresql_psycopg2',<br>
        'NAME': 'django_basic_db',<br>
        'USER': 'basic',<br>
        'PASSWORD': 'password',<br>
        'HOST': 'localhost',<br>
        'PORT': '',<br>
    }<br>
}<br></code>

	</li>
	<li>run: <code>python manage.py migrate</code></li>
	<li>start the server: <code>python manage.py runserver</code></li>
</ol>
# Thankyou's
<ul>
	<li> The Django People </li>
	<li> The Django User Redux People </li>
<ul>
</p>
