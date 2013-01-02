# Rails 3.2.8 Forward slash issue?

The purpose of this repo is to reproduce the double forward slash appearing in root_url when this line is set in application.rb

`config.action_controller.default_url_options = { trailing_slash: true }`

[Rails Issue](https://github.com/rails/rails/issues/8700)