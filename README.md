# Books Store

## Installation

Before start application you need

```console
bundle install
```

Then seed the database with command

```console
rails db:seed_fu
```

Also you can run test with command

```console
bundle exec rspec spec
```

This create 2 users and 12 books, 6 - free and 6 - close

User №1

```ruby
email: 'first@mail.ru', password: '123123'
```

User №2

```ruby
email: 'second@mail.ru', password: '123123'
```

3 coupons for books: book 4 - **aaabbb**, book 5 - **123456**, book 12 - **free**

For more information see

```ruby
app/db/fixtures/3_coupons.rb
```
