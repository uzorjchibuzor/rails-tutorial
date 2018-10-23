web: bundle exec puma -C config/puma.rb
heroku run rails db:migrate
heroku ps:scale web=1 