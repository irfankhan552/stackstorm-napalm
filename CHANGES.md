# Change Log

## 0.2.15

- Version bump to fix tagging issues, no code changes

## 0.2.14

- Support `key_file` for SSH key authentication

## 0.2.13

- Support `secret` parameter for IOS devices that need password to enter enable mode

## 0.2.11

- Added "config_text" parameter to loadconfig action to be able to specify a command to set to device as text

## 0.2.8

- Removes unnecessary exception handling in each action. Was suppressing useful information about the problem
- Catch KeyError when referencing certain config items and provide useful message - clear indicator that config needs provided/reloaded

## 0.2.7

- Added "port" parameter to configuration (sensor now able to set port, actions use this as secondary)

## 0.2.5

- Added missing "credentials" section to `config.schema.yaml`
