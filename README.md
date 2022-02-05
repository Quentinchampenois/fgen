# Fgen (Faker Generator)

`fgen` is a simple CLI written using [Thor](https://github.com/rails/thor) and [Faker.rb](https://github.com/faker-ruby/faker). It aims to provide a simple way to create Fake data.

With `fgen` you can easily create fake data like email, or list of emails and also copying it instantly in clipboard.

## Getting started

### Requirements
* Ruby (> 3)

1. Install dependencies

```bash
gem install thor
gem install faker
gem install os
```

2. Execute Ruby script `fgen`

```bash
./fgen 
```

### Available for now

This is the fake data generable for now, it will grow in future


```bash
Commands:
  fgen email           # Returns a fake email
  fgen help [COMMAND]  # Describe available commands or one specific command
  fgen image           # Returns a fake image
  fgen name            # Returns a fake name
  fgen profile         # Returns a fake profile
  fgen question        # Returns a fake question
  fgen text            # Returns a fake text
```

## Features

For now, fgen only allows to create for example : 

* A unique email
* A list of `n` emails
* Copying output (only for Macos and Linux users), help wanted since I can't have access to a windows environment.
