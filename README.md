Recipe Box
===================

Project
-------------------
Build a recipe box application utilizing nested forms (each recipe has multiple ingredients and multiple steps), image uploading, and using HAML instead of ERB.

Utilized the following project specific gems:
- `gem 'haml'`
  - [Haml](https://github.com/haml/haml) is a templating engine for HTML.
- `gem 'simple_form'`
  - [Simple Form](https://github.com/plataformatec/simple_form) is Rails forms made easy, used for recipes.
- `gem 'bootstrap-sass'`
  - [Bootstrap-Sass](https://github.com/twbs/bootstrap-sass) is a Sass-powered version of Bootstrap, ready to drop right into your Sass powered applications.
- `gem 'paperclip'`
  - [Paperclip](https://github.com/thoughtbot/paperclip) is intended as an easy file attachment library for Active Record, used here for recipe images.
- `gem 'cocoon'`
  - [Cocoon](https://github.com/nathanvda/cocoon) makes it easier to handle nested forms, used for ingredients and directions.
- `gem 'devise'`
  - [Devise](https://github.com/plataformatec/devise) is a flexible authentication solution for Rails based on Warden.


App Features
-------------------
- A user can sign up/sign in and out.
- A user can submit a recipe.
- A recipe can include ingredients, directions and an image.

