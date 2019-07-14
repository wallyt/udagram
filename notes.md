# Notes and tips noted during the Udagram project

### Permissions for shell script file execution
`chmod 754 *name*`

### CLI execution of shell script files
`./create.sh udagramInfra udagram-infra.yml infra-params.json`
`./create.sh udagramServers udagram-servers.yml servers-params.json`
`./delete.sh udagramInfra`

### Get a list of completed stacks
`aws cloudformation list-stacks --stack-status-filter CREATE_COMPLETE`