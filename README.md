# puppet-ramstatus

## sketch
- set env vars: SIZE=100M, STATE_DIR=/var/lib/puppet/state, TRY_LAZY=true
- wrapper init script
 - start': mount+start
 - stop': stop+umount
