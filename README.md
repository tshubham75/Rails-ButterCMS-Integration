

https://github.com/tshubham75/Rails-ButterCMS-Integration/assets/142473715/627b9105-17c7-4efc-ad82-f30ed063f0d5



# Ruby on Rails + ButterCMS Starter Project

This Rails starter project fully integrates with dynamic sample content from your ButterCMS account, including main menu, pages, blog posts, categories, and tags, all with a beautiful, custom theme with already-implemented search functionality. All of the included sample content is automatically created in your account dashboard when you sign up for a free trial of ButterCMS.

You can view a [live demo hosted on Heroku](https://rails-starter-buttercms.herokuapp.com/), or you can click the button below to deploy your own copy of our starter project to the provider of your choice.

[![Heroku Deploy Button](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ButterCMS/rails-starter-buttercms/tree/main&env%5BRAILS_BUTTER_CMS_API_KEY%5D=check%20https://buttercms.com/settings)

## 1. Installation
Make sure you have ruby version 3.1.0 installed. Otherwise, follow the official [instructions](https://www.ruby-lang.org/en/documentation/installation/) on how to set up ruby on your machine.
```
$ ruby -v
```

If you're all set, clone the repo and install dependencies
```
$ git clone https://github.com/ButterCMS/rails-starter-buttercms.git
$ cd rails-starter-buttercms
$ bundle install
```

### 2. Set API Token

To fetch your ButterCMS content, add your API token as an environment variable.

```bash
$ echo 'RAILS_BUTTER_CMS_API_KEY=<Your API Token>' >> .env
```

### 3. Run local server

To view the app in the browser, you'll need to run the local development server:

```
$ bundle exec rails s
```

Congratulations! Your starter project is now live. To view your project, point your browser to [localhost:3000](http://localhost::3000).

## 4. Deploy to Heroku

Deploy your Rails app using Heroku. With the click of a button, you'll create a copy of your starter project in your Heroku account, instantly deploy it, and institute a full content workflow connected to your ButterCMS account. Smooth.

[![Heroku Deploy Button](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ButterCMS/rails-starter-buttercms/tree/main&env%5BRAILS_BUTTER_CMS_API_KEY%5D=check%20https://buttercms.com/settings)

## 5. Previewing Draft Changes

By default, your starter project is set up to allow previewing of draft changes saved in your ButterCMS.com account. To disable this functionality, set the following value in your .env file: `RAILS_BUTTER_CMS_PREVIEW=false`
