

fork from https://github.com/michaelbukachi/flask-vuejs-tutorial

## Original author readme

## flask-vuejs-tutorial

A tutorial to integrate Vue.js with flask

### Installation
1. Clone the repo
2. Inside a Python virual env
3. Run `pip install -r requirements`
4. Run `export FLASK_APP=wsgi:app`
5. Run `flask run`

### Build Web App
In order to rebuild the web app (Vue)
1. Navigate to the `web` folder
2. Run `yarn install`
3. Run `yarn build`


The tutorial can be found [here](https://dev.to/michaelbukachi/flask-vue-js-integration-tutorial-2g90).



## Below is my note


## learning source
Flask Vue.js Integration Tutorial
https://dev.to/michaelbukachi/flask-vue-js-integration-tutorial-2g90



## logic
1. Vue app ready
2. setup vue.config.js
3. build vue -> stactic file and html templates goes into folders under flask app
4. write a view.py which creating a flask blueprint named sample_page and adding a route to it
5. you flask server shall server vue FE



## what is different from this learning guid?
1. On Win10 Powershell, change `export FLASK_APP=wsgi:app` to `SET FLASK_APP=wsgi:app` 
2. Updating to Werkzeug==0.16.1 to fixed import issue about Werkzeug



## other similar tutorials 
1. https://www.google.com/search?q=flask+vue+tutorial&oq=flask+vuew+tut&aqs=chrome.1.69i57j0l2.6895j1j1&sourceid=chrome&ie=UTF-8
2. https://blog.logrocket.com/setting-up-an-online-store-with-flask-and-vue/\
3. https://testdriven.io/blog/developing-a-single-page-app-with-flask-and-vuejs/