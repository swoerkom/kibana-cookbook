# frozen_string_literal: true

source 'https://supermarket.chef.io/'

metadata

solver :ruby, :preferred

cookbook 'compat_resource'
cookbook 'chef-sugar'

group :vagrant do
  cookbook 'ark'
  cookbook 'apt'
  cookbook 'apache2'
  cookbook 'build-essential'
  cookbook 'elasticsearch', '~> 3.4'
  cookbook 'java'
  cookbook 'netstat'
  cookbook 'ohai'
  cookbook 'nginx', '>= 7.0'
end
