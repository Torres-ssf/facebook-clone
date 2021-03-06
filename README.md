[![Maintainability](https://api.codeclimate.com/v1/badges/47dde54b3f4fddb0b16e/maintainability)](https://codeclimate.com/github/bolah2009/facebook-clone/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/47dde54b3f4fddb0b16e/test_coverage)](https://codeclimate.com/github/bolah2009/facebook-clone/test_coverage)
[![Build](https://travis-ci.org/bolah2009/facebook-clone.svg?branch=master)](https://travis-ci.org/bolah2009/facebook-clone)

# PROJECT: Facebook Clone

This is the final project of the Main Rails curriculum at [Microverse](https://www.microverse.org/) - @microverseinc

- The objective is to build a facebook clone with core features of the platform – users, profiles, "friending", posts, news feed, and “liking”. The ability to sign-in with a user's real Facebook account by using OmniAuth and Devise has also been implemented.

#### [Assignment link](https://www.theodinproject.com/courses/ruby-on-rails/lessons/final-project)

#### [View in browser](https://f-b-clone.herokuapp.com/)

## Prerequisites

> Ruby: 2.6.3  
> Rails: 5.2.3

## Usage (Development)

- Clone the repo and run the app.

```
   git clone https://github.com/bolah2009/facebook-clone.git
   cd facebook-clone
   bundle install
   rails db:create
   rails db:migrate
   rspec #run tests
   rails server #run server
   open localhost:3000 on browser
```

## How to run the test suite

- run tests:
  > `rpsec --format documentation`
- view test coverage:
  > `open coverage/index.html`

## Contributing

If you are working on adding features, PRs, or bugfixes, this section should help get you going.

1. Fork it
2. Create your feature branch
   > `git checkout -b my-new-feature`
3. Make sure all tests are passing
   > `bundle install`  
   > `rspec`
4. Commit your changes
   > `git commit -am 'Add some feature'`
5. Push to the branch
   > `git push origin my-new-feature`
6. Create new Pull Request

## Authors

👤 **Sérgio Torres**

- Github: [Torres-ssf](https://github.com/Torres-ssf)
- Twitter: [@torres_ssf](https://twitter.com/torres_ssf)
- Linkedin: [torres-ssf](https://www.linkedin.com/in/torres-ssf/)

👤 **Bolah Ahmed**

- [@bolah2009](https://github.com/bolah2009/)
- Twitter: [@bolah2009](https://twitter.com/bolah2009)
- Linkedin: [bolah2009](https://www.linkedin.com/in/bolah2009/)
