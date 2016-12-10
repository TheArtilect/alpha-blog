# Personal Blog

#### This repo is for a personal blog

### Quick Start
Clone the repo:
```
git clone https://github.com/ianagpawa/alpha-blog.git
```

### Installation of Dependencies
In order to run the app locally, `Ruby` and `Rails` must be installed on your system.  Then, while the terminal is in the project folder, execute the following commands to install the necessary gems:
```
bundle install --without production
```
Then execute the following command to perform appropriate migrations:
```
bin/rake db:migrate RAILS_ENV=development
```

### Viewing the app locally
In order to view the app locally, with the terminal in the project folder, execute command `rails s`, then point your browser to `http://localhost:3000`



### What's included
Within the project folder, you will find the following files:

```
alpha-blog/
    ├───  app/
    |       ├── assets/
    |       |       ├── images/
    |       |       |      ├── btlc-title.jpg
    |       |       |      └── NYC.jpg
    |       |       ├── javascripts/
    |       |       |      └── application.js
    |       |       |
    |       |       └── stylesheets/
    |       |               ├── application.css.scss
    |       |               └── custom.css.scss
    |       |
    |       ├─── controllers/
    |       |       ├── application_controller.rb
    |       |       ├── articles_controller.rb
    |       |       ├── categories_controller.rb
    |       |       ├── pages_controller.rb
    |       |       ├── sessions_controller.rb
    |       |       └── users_controller.rb
    |       |
    |       ├─── models/
    |       |       ├── article_category.rb
    |       |       ├── article.rb
    |       |       ├── category.rb
    |       |       └── user.rb
    |       |       
    |       └─── views/
    |               ├── articles/
    |               |       └── _article.html.erb
    |               |       └── _form.html.erb
    |               |       └── edit.html.erb
    |               |       └── index.html.erb
    |               |       └── new.html.erb
    |               |       └── show.html.erb
    |               ├── categories/
    |               |       └── _category.html.erb
    |               |       └── _form.html.erb
    |               |       └── edit.html.erb
    |               |       └── index.html.erb
    |               |       └── new.html.erb
    |               |       └── show.html.erb
    |               ├── layouts/
    |               |       ├── _footer.html.erb
    |               |       ├── _messages.html.erb
    |               |       ├── _navigation.html.erb
    |               |       └── application.html.erb
    |               ├── pages/
    |               |       ├── about.html.erb
    |               |       └── home.html.erb
    |               ├── sessions/
    |               |       └── new.json.jbuilder
    |               ├── shared/
    |               |       └── _errors.html.erb
    |               └── user
    |                       ├── _form.html.erb
    |                       ├── edit.html.erb
    |                       ├── index.html.erb
    |                       ├── new.html.erb
    |                       └── show.html.erb
    ├──  bin/
    |       ├── bundle
    |       ├── rails
    |       ├── rake
    |       ├── setup
    |       └── spring
    ├── config/
    |       ├── environments/
    |       |       ├── development.rb
    |       |       ├── production.rb
    |       |       └── test.rb
    |       ├─── initializers/
    |       |       ├── assets.rb
    |       |       ├── backtrace_silencers.rb
    |       |       ├── cookies_serializer.rb
    |       |       ├── filter_parameter_logging.rb
    |       |       ├── inflections.rb
    |       |       ├── mime_types.rb
    |       |       ├── session_store.rb
    |       |       └── wrap_parameters.rb
    |       ├─── locales/
    |       |       └── en.yml
    |       ├─── application.rb
    |       ├─── boot.rb
    |       ├─── database.yml
    |       ├─── environment.rb
    |       ├─── routes.rb
    |       └─── secrets.yml
    ├── public/
    |     ├── 404.html
    |     ├── 422.html
    |     ├── 500.html
    |     ├── favicon.ico
    |     └── robots.txt
    ├── .gitignore
    ├── config.ru
    ├── Gemfile
    ├── Gemfile.lock
    ├── Rakefile
    └── README.md
```

## Creator

**Ian Agpawa**


[Github](https://github.com/ianagpawa)

 agpawaji@gmail.com
