# rubygems-nginx-proxy
Nginx configuration files for Rubygems caching proxy. This config used for [gems.kaos.st](https://gems.kaos.st) service.

## Usage

If you use [bundler](http://bundler.io), add this line on top of your Gemfile:
```ruby
source 'https://gems.kaos.st'
```

Also, you can use this proxy for downloading gems with `gem` command. For example:

```bash
gem install bundler --source https://gems.kaos.st
```

## Status

Current status of EK Rubygems Proxy you can find on our [status page](http://status.gems.kaos.st).
