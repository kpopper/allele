# Allele

A Ruby on Rails app template for even rapid-er prototyping. Based on Made By Many's generously open-sourced template.

## Get started

To create a fresh app from the Allele template with a remote environment on Heroku, simply run:

`rails new app_name -d mysql -m https://raw.github.com/sidekickstudios/allele/master/allele.rb`

## What's included

- Authentication from [Devise](https://github.com/plataformatec/devise)
- A front-end framework in the shape of [Bootstrap](http://twitter.github.io/bootstrap/)
- Image uploads with [Carrierwave](https://github.com/carrierwaveuploader/carrierwave) and file storage on S3 via [Fog](https://github.com/fog/fog)
- Save time on basic CRUD methods with [Inherited Resources](https://github.com/josevalim/inherited_resources)
- Neat and easy to code forms with [Simple Form](https://github.com/plataformatec/simple_form)
- [Premailer](https://github.com/fphilipe/premailer-rails) and [MailView](https://github.com/37signals/mail_view) takes a lot of hassle out of handling HTML emails
- [ExceptionNotifier](https://github.com/rails/exception_notification) lets you know when a user breaks something
- Free server ops from [Heroku](http://heroku.com) and application mailers from [SendGrid](http://sendgrid.com)

*Note: we add a `nofollow, noindex` tag and and `disallow` in robots.txt by default*

## Need more?

For basic authorisation with `cancan` and content management with `activeadmin` run:

```bash
rails generate allele_admin
```

Check out the Wiki for some more quick 'n' dirty functionality.

## Rails 4

While Rails 4 is now a stable release, many of the gems we rely on are not, roadmap:

- Move to Rails 4 once ActiveAdmin and SimpleForm cut reliable releases

## To Do

* Replace mxm-layout.css with Sidekick appropriate one
* Replace Bootstrap with Bourbon and Neat
* Replace ActiveAdmin with RailsAdmin