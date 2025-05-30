# [Django Charts via DRF](https://blog.appseed.us/django-charts-via-drf-and-charts-js/)

Sample project crafted with `Django`, `Chart.JS`, and `DRF` to showcase how to plot different charts **Pie, Line and Bar Charts**. Frontend uses `Bootstrap5` for styling and `Chart.js` for dynamic charts. The dataset is loaded from `data` directory.

- 👉 [Charts via DRF](https://blog.appseed.us/django-charts-via-drf-and-charts-js/) - Related blog article
- 👉 More [Django apps](https://appseed.us/apps/django/) and [dashboards](https://appseed.us/admin-dashboards/django/)

<br /> 

> Features:

- ✅ `Up-to-date dependencies`
- ✅ `Stack`: Django
- ✅ `API` via DRF
- ✅ `Charts`: Chart.js
- ✅ `Styling`: BS5 (via CDN)

<br />

![Django Charts via DRF and Charts.js - provided by AppSeed](https://user-images.githubusercontent.com/51070104/165535311-3968e507-df70-4121-891a-e83d867315ac.jpg)

## ✨ How to use it

> 👉 **Clone Sources** (this repo)

```bash
$ git clone https://github.com/app-generator/sample-django-charts-js.git
$ cd sample-django-charts-js
```

<br />

> 👉 **Install Modules** using a Virtual Environment

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

Or for **Windows-based Systems**

```bash
$ virtualenv env
$ .\env\Scripts\activate
$
$ # Install modules - SQLite Database
$ pip3 install -r requirements.txt
```

<br />

> 👉 **Migrate Database**

```bash
$ python manage.py migrate
$ python manage.py runserver
```

<br />

> 👉 **Create Superuser**

```bash
$ python manage.py createsuperuser
```

<br />

> 👉 **Start the APP**

```bash
$ python manage.py runserver
```

<br />

> The bootstrap flow

- Access the `admin` section 
  - Load `data/users.csv` in users table (using import/export feature)
  - Load `data/products.csv` in users table (using import/export feature)
- Access the HOMEpage 
  - Charts should be displayed with data

<br />

![Django Charts via DRF and Charts.js - provided by AppSeed](https://user-images.githubusercontent.com/51070104/165535311-3968e507-df70-4121-891a-e83d867315ac.jpg)

<br />

---
[Django Charts via DRF](https://blog.appseed.us/django-charts-via-drf-and-charts-js/) - provided by [AppSeed](https://appseed.us)
