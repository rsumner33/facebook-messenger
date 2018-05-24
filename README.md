<p align="center">
  <img src="https://rawgit.com/hyperoslo/facebook-messenger/master/docs/logo.png">
</p>

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'facebook-messenger'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install facebook-messenger

## Usage

### Subscribe your Application (bot) to a Page

Once you've created an Application on Facebook, select the Facebook Page you want to
install it on and use the corresponding Page Access Token to subscribe it:

```ruby
Facebook::Messenger::Subscriptions.subscribe('<token>')
```

*This is a work in progress; more features and documentation to follow.*

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run
`bin/console` for an interactive prompt that will allow you to experiment.

Run `rspec` to run the tests, `rubocop` to lint, or `rake` to do both.

To install this gem onto your local machine, run `bundle exec rake install`. To
release a new version, update the version number in `version.rb`, and then run
`bundle exec rake release`, which will create a git tag for the version, push git
commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at
https://github.com/hyperoslo/facebook-messenger.

## Hyper loves you

[Hyper] made this. We're a bunch of folks who love building things. You should
[tweet us] if you can't get it to work. In fact, you should tweet us anyway.
If you're using Facebook Messenger, we probably want to [hire you].

[Hyper]: https://github.com/hyperoslo
[tweet us]: http://twitter.com/hyperoslo
[hire you]: http://www.hyper.no/jobs/engineers
[MIT License]: http://opensource.org/licenses/MIT
[rubygems.org]: https://rubygems.org
