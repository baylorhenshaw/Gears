# Gears
Gears is a very simple script that allows you to create basic `config.yml` files very easily.
# Dependencies
- Skript 2.6+
- skript-reflect
- skript-storage
- Skent (Version Checking)
# Documentation
### Register Configuration
You can easily register a configuration file using the syntax below.
```
register [a] [new] config with id %string% [and] [with] name %string% [and] [with] path %string%
```
### Register Value
You can register a value with a valid config using the syntax below.
```
register [a] [new] option for [config] [with] [id] %string% named %option% [and] with default [value] %object%
```
### Reload Configuration
Reload a config and delete the old cache.
```
reload config [with] [id] %string%
```
### Get Configuration Value
You can grab a configuration option from the cached variable by using the syntax below.
```
[get] config value %string% from %string%
```
