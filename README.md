# ChalengeAccepted

The Idea: Amine has just arrived in a new city, he has a lot of questions and only people close to his location can answer it.

My Task: Build a full-stack application that allows people to:

Post location-based questions

Get answers from nearby users

Sort questions by distance

Save favorite questions

# Project Requirements

#  Required Technologies : 

Backend: Ruby on Rails + MongoDB

Frontend: Angular + Bootstrap

Authentication: Email/Password based

Location: Geolocation integration

# Required Features : 

User registration & login

Post questions with location

Post answers to questions

Display questions sorted by distance

Like/favorite questions

(Optional) Manage favorites

(Optional) Google Maps integration


The Latest Angular version got Installed 

The Latest Ruby on rails version got Installed 


current structure : 

```
├── 📁 BackEnd
│   ├── 📁 app
│   │   ├── 📁 assets
│   │   │   ├── 📁 config
│   │   │   │   └── 📄 manifest.js
│   │   │   ├── 📁 images
│   │   │   │   └── ⚙️ .keep
│   │   │   └── 📁 stylesheets
│   │   │       └── 🎨 application.css
│   │   ├── 📁 channels
│   │   │   └── 📁 application_cable
│   │   │       ├── 💎 channel.rb
│   │   │       └── 💎 connection.rb
│   │   ├── 📁 controllers
│   │   │   ├── 📁 concerns
│   │   │   │   └── ⚙️ .keep
│   │   │   └── 💎 application_controller.rb
│   │   ├── 📁 helpers
│   │   │   └── 💎 application_helper.rb
│   │   ├── 📁 javascript
│   │   │   ├── 📁 controllers
│   │   │   │   ├── 📄 application.js
│   │   │   │   ├── 📄 hello_controller.js
│   │   │   │   └── 📄 index.js
│   │   │   └── 📄 application.js
│   │   ├── 📁 jobs
│   │   │   └── 💎 application_job.rb
│   │   ├── 📁 mailers
│   │   │   └── 💎 application_mailer.rb
│   │   ├── 📁 models
│   │   │   ├── 📁 concerns
│   │   │   │   └── ⚙️ .keep
│   │   │   └── 💎 application_record.rb
│   │   └── 📁 views
│   │       └── 📁 layouts
│   │           ├── 📄 application.html.erb
│   │           ├── 📄 mailer.html.erb
│   │           └── 📄 mailer.text.erb
│   ├── 📁 config
│   │   ├── 📁 environments
│   │   │   ├── 💎 development.rb
│   │   │   ├── 💎 production.rb
│   │   │   └── 💎 test.rb
│   │   ├── 📁 initializers
│   │   │   ├── 💎 assets.rb
│   │   │   ├── 💎 content_security_policy.rb
│   │   │   ├── 💎 filter_parameter_logging.rb
│   │   │   ├── 💎 inflections.rb
│   │   │   └── 💎 permissions_policy.rb
│   │   ├── 📁 locales
│   │   │   └── ⚙️ en.yml
│   │   ├── 💎 application.rb
│   │   ├── 💎 boot.rb
│   │   ├── ⚙️ cable.yml
│   │   ├── 📄 credentials.yml.enc
│   │   ├── ⚙️ database.yml
│   │   ├── 💎 environment.rb
│   │   ├── 💎 importmap.rb
│   │   ├── 📄 master.key
│   │   ├── 💎 puma.rb
│   │   ├── 💎 routes.rb
│   │   └── ⚙️ storage.yml
│   ├── 📁 db
│   │   └── 💎 seeds.rb
│   ├── 📁 lib
│   │   ├── 📁 assets
│   │   │   └── ⚙️ .keep
│   │   └── 📁 tasks
│   │       └── ⚙️ .keep
│   ├── 📁 log
│   │   └── ⚙️ .keep
│   ├── 📁 public
│   │   ├── 🌐 404.html
│   │   ├── 🌐 422.html
│   │   ├── 🌐 500.html
│   │   ├── 🖼️ apple-touch-icon-precomposed.png
│   │   ├── 🖼️ apple-touch-icon.png
│   │   ├── 📄 favicon.ico
│   │   └── 📄 robots.txt
│   ├── 📁 storage
│   │   └── ⚙️ .keep
│   ├── 📁 test
│   │   ├── 📁 channels
│   │   │   └── 📁 application_cable
│   │   │       └── 💎 connection_test.rb
│   │   ├── 📁 controllers
│   │   │   └── ⚙️ .keep
│   │   ├── 📁 fixtures
│   │   │   └── 📁 files
│   │   │       └── ⚙️ .keep
│   │   ├── 📁 helpers
│   │   │   └── ⚙️ .keep
│   │   ├── 📁 integration
│   │   │   └── ⚙️ .keep
│   │   ├── 📁 mailers
│   │   │   └── ⚙️ .keep
│   │   ├── 📁 models
│   │   │   └── ⚙️ .keep
│   │   ├── 📁 system
│   │   │   └── ⚙️ .keep
│   │   ├── 💎 application_system_test_case.rb
│   │   └── 💎 test_helper.rb
│   ├── 📁 vendor
│   │   ├── 📁 javascript
│   │   │   └── ⚙️ .keep
│   │   └── ⚙️ .keep
│   ├── ⚙️ .dockerignore
│   ├── ⚙️ .gitattributes
│   ├── ⚙️ .gitignore
│   ├── 🐳 Dockerfile
│   ├── 📄 Gemfile
│   ├── 📝 README.md
│   ├── 📄 Rakefile
│   └── 📄 config.ru
├── 📁 FrontEnd
│   ├── 📁 .angular
│   ├── 📁 public
│   │   └── 📄 favicon.ico
│   ├── 📁 src
│   │   ├── 📁 app
│   │   │   ├── 📁 components
│   │   │   │   ├── 📁 layout
│   │   │   │   │   ├── 📁 footer
│   │   │   │   │   │   ├── 🌐 footer.component.html
│   │   │   │   │   │   ├── 🎨 footer.component.scss
│   │   │   │   │   │   └── 📄 footer.component.ts
│   │   │   │   │   └── 📁 navbar
│   │   │   │   │       ├── 🌐 navbar.component.html
│   │   │   │   │       ├── 🎨 navbar.component.scss
│   │   │   │   │       └── 📄 navbar.component.ts
│   │   │   │   └── 📁 shared
│   │   │   ├── 📄 app.config.server.ts
│   │   │   ├── 📄 app.config.ts
│   │   │   ├── 🎨 app.css
│   │   │   ├── 🌐 app.html
│   │   │   ├── 📄 app.routes.server.ts
│   │   │   ├── 📄 app.routes.ts
│   │   │   ├── 📄 app.spec.ts
│   │   │   └── 📄 app.ts
│   │   ├── 🌐 index.html
│   │   ├── 📄 main.server.ts
│   │   ├── 📄 main.ts
│   │   ├── 📄 server.ts
│   │   └── 🎨 styles.css
│   ├── ⚙️ .editorconfig
│   ├── ⚙️ .gitignore
│   ├── 📝 README.md
│   ├── ⚙️ angular.json
│   ├── ⚙️ package-lock.json
│   ├── ⚙️ package.json
│   ├── ⚙️ tsconfig.app.json
│   ├── ⚙️ tsconfig.json
│   └── ⚙️ tsconfig.spec.json
└── 📝 README.md
```




