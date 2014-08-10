# -*- mode: ruby; coding: utf-8; -*-

source 'https://api.berkshelf.com'

metadata

cookbook 'java', github: 'socrata-cookbooks/java'
cookbook 'ark', '0.7.0'
cookbook 'tomcat', '0.15.12'
cookbook 'application_java', github: 'uranium/application_java', tag: '3.0.2'
cookbook 'mongodb', github: 'edelight/chef-mongodb'

group :integration do
  cookbook 'apt', '~> 2.0'
end
