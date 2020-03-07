# greeter

This project contains the code created by following the RSpec learning pill from the Makers Academy precourse. It is a simple tutorial demonstrating the basics of how to set up and use the behavioural driven development tool rspec.

## Getting started

Cloning the project:
```ruby
# from the directory above where you want the project to be created
# if you're using SSH
git clone git@github.com:PhilipVigus/greeter.git
# if you're using https
git clone https://github.com/PhilipVigus/greeter.git
```

Project dependencies:
```ruby
# the only dependency is the ruby gem rspec
# to install
gem install rspec
```

## Usage

There is no usage as such. The project contains the most basic set up to demonstrate how to use RSpec to run tests on Ruby code.

## Running tests

```ruby
# from the project's root directory
# to run all tests
rspec
```

## File manifest

| Filename | Contents |
| ------------ | ----------- |
| README.md | This file |
| lib/greeter.rb | Contains a simple method named greet, which is the code tested by RSpec |
| spec/greeter_spec.rb | Contains the two tests that demonstrate how to use the basics of RSpec |