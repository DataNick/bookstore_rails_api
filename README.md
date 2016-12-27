Following tutorial from https://emberigniter.com/modern-bridge-ember-and-rails-5-with-json-api/ to hook up an Ember app with Rails backend using the Rails 5 API.

To use on local machine:

* Clone repo
* Run migrations and rake db:seed
* Run rails server --binding 0.0.0.0
* Clone bookstore_client repo and follow instructions on readme and run in separate terminal ember server --proxy http://localhost:3000


Learning goals for the Bookstore-api:

* Familiarize myself with Rails 5 api

* Deeper dive into active model serializers

* Reaffirm understanding of polymorphic associations

Next steps:

* Deploy on AWS and have a live working ember front end

* When deploying, use Capistrano

