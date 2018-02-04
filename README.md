# Dennisdoomen.github.io

The future home of <http://www.continuousimprover.com/>.

## How to Build this Site

### Prerequisites

* Ruby 2.x
* The `bundler` gem (`gem install bundler`)

### Building

* Clone this repository
* `cd` into the root of the repository
* Run `bundle install`
* Run `bundle exec jekyll serve`

## Troubleshooting

* Do you receive an error around `jekyll-remote-theme` and `libcurl`? See [this issue on the pages-gem repo](https://github.com/github/pages-gem/issues/526).
* Do you receive an error `Liquid Exception: SSL_connect returned=1 errno=0 state=error: certificate verify failed`? Check out [this solution in the Jekyll repo.](https://github.com/jekyll/jekyll/issues/3985#issuecomment-294266874)