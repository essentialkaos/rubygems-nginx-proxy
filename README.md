## `rubygems-nginx-proxy` [![License](https://gh.kaos.st/apache2.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
Nginx configuration files for Rubygems caching proxy. This config used for [EK RubyGems Proxy](https://gems.kaos.st) service.

### Usage

If you use [bundler](http://bundler.io), add this line on top of your Gemfile:
```ruby
source 'https://gems.kaos.st'
```

Also, you can use this proxy for downloading gems with `gem` command. For example:

```bash
gem install bundler --source https://gems.kaos.st
```

### Status

Current status of EK RubyGems Proxy you can find on our [status page](http://status.gems.kaos.st).

<p align="center"><a href="https://essentialkaos.com"><img src="https://gh.kaos.st/ekgh.svg"/></a></p>
