forge 'https://forgeapi.puppet.com/'

# We're not ready for version 9
mod 'puppetlabs/stdlib',               '< 9'
mod 'puppetlabs/apt',                  '< 9.1.0'

# HTTP/2 and SSL support for settings in Hiera
mod 'puppetlabs/apache',               '>= 8.3'

# Ensure Debian 11 support
mod 'puppetlabs/postgresql',           '>= 7.4.0'

# Dnfmodule support for Redis 6+ support
mod 'puppet/redis',                    '>= 8.5.0'

# Dependencies
mod 'theforeman/dhcp',                 :git => 'https://github.com/theforeman/puppet-dhcp'
mod 'theforeman/dns',                  :git => 'https://github.com/theforeman/puppet-dns'
mod 'theforeman/git',                  :git => 'https://github.com/theforeman/puppet-git'
mod 'theforeman/puppetserver_foreman', :git => 'https://github.com/theforeman/puppet-puppetserver_foreman'
mod 'theforeman/tftp',                 :git => 'https://github.com/theforeman/puppet-tftp'

# Katello dependencies
mod 'katello/candlepin',               :git => 'https://github.com/theforeman/puppet-candlepin'
mod 'theforeman/pulpcore',             :git => 'https://github.com/theforeman/puppet-pulpcore'
mod 'katello/qpid',                    :git => 'https://github.com/theforeman/puppet-qpid'

# Top-level modules
mod 'theforeman/foreman',              :git => 'https://github.com/theforeman/puppet-foreman'
mod 'theforeman/foreman_proxy',        :git => 'https://github.com/theforeman/puppet-foreman_proxy'
mod 'theforeman/puppet',               :git => 'https://github.com/theforeman/puppet-puppet'

# Top-level katello modules
mod 'katello/foreman_proxy_content',   :git => 'https://github.com/theforeman/puppet-foreman_proxy_content'
mod 'katello/certs',                   :git => 'https://github.com/theforeman/puppet-certs'
mod 'katello/katello',                 :git => 'https://github.com/theforeman/puppet-katello'
