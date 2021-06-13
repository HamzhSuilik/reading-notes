# Django

### Django
**Django** is a high-level Python Web framework that encourages rapid development and clean, pragmatic design , It is open source, meaning the code is available for free on Github and you can be downloaded Django for free .

Python organizes the URL better than other languages ​​like PHP, so to create new Url in Django create a Python module called a URLconf which contains a simple mapping between URL patterns and views

```urlpatterns = [
 path('bands/', views.band_listing, name='band-list'),
 path('bands/<int:band_id>/',views.band_detail, name='band-detail')]
```

Django’s template is away to write python code inside html file , it is easy to use and flexible
`{% for band in bands %}`

Django contains forms library that help you to mange and transfer data from frontend to backend .
To import forms library : 
`from django import forms`

Python has an authentication system that allows you to design login interfaces and create an account securely

If you want a powerful and secure admin interface for managing content, Django provides us a ready interface so there is no need to design admin interface for your app

Django includes a library for handling texts  :translating text into different languages, deal with locale-specific formatting of dates, times, numbers, and time zones

**Types of Funding in Open Source Projects  :**

- Corporate Sponsor : An organization sponsors the open source app and pay a fixed salaries to developers
- Solo : This is related to a single developer who takes over the application development process
- Non-profit : for example Django’s organization is managed by a non-profit organization the DSF
