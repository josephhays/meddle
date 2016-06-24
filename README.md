# Meddle | A Rails CMS for Radio, Webradio and Television

### What is Meddle?

Meddle is a new CMS and soon to be full-featured ERP built in rails and tailored specifically for the digital broadcaster.
It is also my own personal learning project and notes and discussion can be found at http://joseph.tsimastudios.com.

### Download and Installation

Meddle is not specifically made for any server host and is built with the assumption that the user is familiar with installing Rails programs. Even if that isn't the case, most server hosts have step-by-step instructions on setting up a rails app.

Meddle is configured for Postgres and Unicorn in PRODUCTION (production refers to an end-users installation of a rails app) for the sake of DigitalOcean installation, but that is easily changed by editing the section

```ruby
group :production do
  gem 'pg'
  gem 'unicorn'
end
```
of the `Gemfile` and setting up the database in the `config/database.yml` file.

This README will be updated soon!
