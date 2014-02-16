wikiful
=======

wikiful project from thinkful.com

## How to deploy
  
    $ git clone http://github.com/limingth/wikiful.git
    $ cd wikiful
    $ bundle install
    $ rails s

* You can see an error about psql

### start psql server (elephant icon)

### Create database and migrate

    $ createuser -s wikiful
    $ rake db:create
    $ rake db:migrate
  
### start chrome and localhost:3000

    $ rake db:seed
  
## How to use

* view
* log in
* write/edit/delete a wiki
* log out
* sort by categories
