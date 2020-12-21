Bosh CLI
========

Download the latest `bosh cli <https://github.com/cloudfoundry/bosh-cli/releases/>`__ for your OS (Linux and version 6.4.1 examples used here).

`curl -LO https://github.com/cloudfoundry/bosh-cli/releases/download/v6.4.1/bosh-cli-6.4.1-linux-amd64`{{execute}}

Rename and move the file to '/usr/local/bin'

`sudo mv bosh-cli-6.4.1-linux-amd64 /usr/local/bin/bosh`{{execute}}

Set the execute bit for owner, group and other

`sudo chmod +x /usr/local/bin/bosh`{{execute}}

Validate bosh

`bosh --version`{{execute}}