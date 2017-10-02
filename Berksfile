source 'https://supermarket.chef.io/'

metadata

cookbook 'yum-epel', '~> 2.1.2'
cookbook 'ubuntu', '~> 2.0.1'
cookbook 'apt', '~> 6.1.4'
cookbook 'build-essential', '~> 8.0.3'
cookbook 'dpkg_autostart', '~> 0.2.0'

group :integration do
  cookbook 'setup', path: 'test/fixtures/cookbooks/setup'
end
