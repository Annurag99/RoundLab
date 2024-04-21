# <img width="227" alt="Screenshot 2024-04-18 at 1 17 56 PM" src="https://github.com/Annurag99/RoundLab/assets/157478528/9b54e12f-4958-4efa-897d-e22518090a59"> : Unveiling a New Era in Beauty Retail

By using Amazon Web Services (AWS) cloud computing resources, my project aims to build a robust cosmetics e-commerce website.

# Tech Stack
```python
Django==3.0.5
django-widget-tweaks==1.4.8
sqlparse==0.3.1
xhtml2pdf
```
# Instructions for installation

```python
git clone https://github.com/Annurag99/RoundLab.git
```

```python
cd RoundLab
```

```python
virtualenv env
```
or
```python
python3 -m venv env
```

# Mac/Linux

```python
source env/bin/activate
```

```python
pip install -r requirements.txt
```

```python
python3 manage.py makemigrations
```

If the above command throws an error update Pip and Setuptools
```python
pip install --upgrade pip setuptools
```

```python
python3 manage.py migrate
```

```python
python3 manage.py runserver 8080
```

To resolve the Invalid HTTP_HOST header error. You may need to add a host header 
example - 'd003a56484c942d88af2e1fc366a3f01.vfs.cloud9.eu-west-1.amazonaws.com'
to ALLOWED_HOSTS and CSRP_TRUSTED_ORIGINS inside the demo folder in the settings.py file.

# Admin Login

```python
python3 manage.py createsuperuser
Username: anuragsingh
Password: Admin@123
```

# Demo & Static Pages

# Deploy URL
http://x23180013-cpp-project-env.eba-vbitjavb.eu-north-1.elasticbeanstalk.com/




