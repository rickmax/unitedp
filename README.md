## UnitedP

United Pentecost is a social networking app built to Members by United Pentecostal Church. It's completely free.

### What it uses?

* [Ruby on Rails](https://github.com/rails/rails)
* [Bootstrap](https://github.com/twbs/bootstrap-sass)
* [Devise](https://github.com/plataformatec/devise)
* [Public Activity](https://github.com/chaps-io/public_activity)

### How do I get set up?

To set it up on your local machine here is what you need to do. Install Ruby & Rails. Clone this repo using the following command:

```
git clone https://github.com/rickmax/unitedp
cd unitedp
```
Then resolve dependencies using bundler:

```
bundle install
```

Run Migrations:

```
rake db:migrate
```

Run rails using

```
rails server
```

### Populate Mock data
To test the app with mock data by running the following rake task:

```
rake fill:data
```

This will create records with values from faker & populator gems. Also here are the test user credentials:

* email: test@test.com
* password: 12345678

### License
This project is Licensed under the [MIT](http://rickmax-unitedp.mit-license.org/)
