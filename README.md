# puppet-ramstatus

## Purpose
Can boost Puppet agent performance significantly, especially if used on a system with slower disk IO and large catalogs with many resources. Seen run time savings > 40%.

## What it does
Wraps original Puppet agent init script. Mounts (and unmounts) a ramdisk to Puppet's ```status``` directory defaulting to ```/var/lib/puppet/state```

## Usage
Like a normal init script.
