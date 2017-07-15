# Finance Tracker Application

This is a US stock tracker application made with Ruby on Rails during The Complete Ruby on Rails Developer Course

# Functionalities

- Sign Up
- Log In
- Log Out
- My portfolio
  - Search stock from ticker symbol
  - Listing stocks
  - Add and Remove stocks
- My profile
  - Show profile
  - Edit and update profile
- My friend
  - Search friends
  - Listing friend
  - Add and remove friends

# Model Associations

```
User **many_to_many** Stock, Through: :User_Stock
User **many_to_many** Friend, Through: :Friendship
Friend **belongs_to** User
```

# Technologies

- Ruby 2.3.0
- Rails 4.2.5
- gem will_paginate 3.0.7
- gem devise
- gem twitter-bootstrap-rails
- gem devise-bootstrap-views
- gem stock_quote

# Demo

Running demo at: https://finance-trackers.herokuapp.com/
