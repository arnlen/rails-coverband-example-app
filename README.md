## Rails Example App for [Coverband](https://github.com/danmayer/coverband)

### Requirements

- [Redis](http://redis.io/)

### Installation

```
git clone git@github.com:arnlen/rails-coverband-example-app.git
```

### Usage

```
# Start your redis server
redis-server

# Engine start!
rails s
```

Navigate to [localhost:3000/users](http://localhost:3000/users) and click few links.
Then to see the coverage:

```
rake coverband:coverage
```

### Thanks

Huge thanks to [Dan Mayer](https://github.com/danmayer), creator of this very useful gem!