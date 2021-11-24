Migrations are useful to generate modifications into your database tables.  
To add structure to an existing model, we need to create a migration directly using the `migration` generator:
```
  rails generate migration AddBalanceToPlayers balance:integer
```

Then we need to modify the migration file generated in order to fulfill our needs
```Ruby
class AddBalanceToPlayers < ActiveRecord::Migration[6.1]
  def change
    add_column :players, :balance, :integer, :default=>10000
  end
end
```
To make the changes, call:
```
rails db:migrate
```
