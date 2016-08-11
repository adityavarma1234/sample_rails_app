# Ruby on Rails Tutorial: sample application

    cd /tmp
    git clone https://github.com/railstutorial/sample_app_rails.git
    cd sample_app_rails
    cp config/database.yml.example config/database.yml
    bundle install --without production
    bundle exec rake db:migrate
    bundle exec rake db:test:prepare
    bundle exec rspec spec/

If the tests don't pass, it means there may be something wrong with your system.
