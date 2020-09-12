# Initial Setup

Ruby 2.7.1  
Rails 6.0.3.2  
Node 12.18.3

```
bundle install
rails db:create
rails db:migrate
rails db:fixtures:load
```

# Running Locally

```
foreman start
```

# Tests

## Test Suite

`rails t`

## System Tests

`rails test:system`

## References

[Rails Code Along](https://www.youtube.com/playlist?list=PLT3ExXbnzYymL4cjPQIYprQ9CmT0kIUfx)

[Setup Bootstrap Video](https://gorails.com/episodes/how-to-use-bootstrap-with-webpack-and-rails)  
[Setup Bootstrap Text](https://stevepolito.design/blog/rails-6-bootstrap-4-webpacker-tutorial/)

## Notes

<details>
  <summary>See Notes</summary>
- Rails uses yarn to install node packages.
- Boostrap has JQuery and Popper dependencies
</details>
