# Code Climate Rubocop Engine

[![Code Climate](https://codeclimate.com/github/codeclimate/codeclimate-rubocop/badges/gpa.svg)](https://codeclimate.com/github/codeclimate/codeclimate-rubocop)

`codeclimate-rubocop` is a Code Climate engine that wraps the [RuboCop](https://github.com/bbatsov/rubocop) static analysis tool. You can run it on your command line using the Code Climate CLI, or on our hosted analysis platform.

RuboCop helps you enforce many of the guidelines outlined in the community [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide). Most aspects of its behavior can be tweaked via various [configuration options](https://github.com/bbatsov/rubocop/blob/master/config/default.yml), which are set in a **.rubocop.yml** file.

You can find some basic setup instructions and links to the RuboCop OSS project below. For additional Code Climate-specific config details, check out our [RuboCop engine documentation][cc-docs-rubocop].

### Installation

1. If you haven't already, [install the Code Climate CLI](https://github.com/codeclimate/codeclimate).
2. Run `codeclimate engines:enable rubocop`. This command both installs the engine and enables it in your `.codeclimate.yml` file.
3. You're ready to analyze! Browse into your project's folder and run `codeclimate analyze`.

### Need help?

For help with RuboCop, [check out their documentation](https://github.com/bbatsov/rubocop).

If you're running into a Code Climate issue, first check out [our RuboCop engine docs][cc-docs-rubocop] and look over this project's [GitHub Issues](https://github.com/codeclimate/codeclimate-rubocop/issues), as your question may have already been covered. If not, [go ahead and open a support ticket with us](https://codeclimate.com/help).

[cc-docs-rubocop]: https://docs.codeclimate.com/docs/rubocop
