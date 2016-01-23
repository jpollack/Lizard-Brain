# Lizard Brain

A computer assisted brain stem.

# Configuration

Configuration is managed entirely by environment variables.  The list of
configuration fields are as follows:

## `PUSHOVER_USER`

The user token to send pushover messages to

## `PUSHOVER_API`

The api token to use when sending pushover messages

## `LB_PASS`

The crypt formatted password that (at least) Twilio will use when authentication
with Lizard Brain.

## `MY_CELL`

The [E.164](https://http://en.wikipedia.org/wiki/E.164) cell that is authorized
to interact with the Lizard Brain via Twilio.

## `LB_GH_SECRET`

The secret to use for Github authentication.  Maybe just use `LB_PASS` for this?

## `LB_TASKS`

The directory where tasks are located.  Default is `./tasks`.