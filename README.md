## Sensu-Plugins-dhcp

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-dhcp.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-dhcp)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-dhcp.svg)](http://badge.fury.io/rb/sensu-plugins-dhcp)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-dhcp/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-dhcp)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-dhcp/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-dhcp)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-dhcp.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-dhcp)

## Functionality

## Files
 * bin/check-dhcp

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-dhcp -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-dhcp`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-dhcp' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-dhcp' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
