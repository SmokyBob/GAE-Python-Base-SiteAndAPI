# GAE-Python-Base-SiteAndAPI
Base structure for a site on App Engine with "static site" folder and api folder with python

Put your "static" html files inside `site`.

By accessing the root address (Ex. http://mySite.com/) the file index.html will be served

Put the python code inside the `api` folder and configure `app.yaml` accordingly (if needed)

All the requests to http://mySite.com/api will be redirected to the main.py code