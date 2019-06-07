# AWS Snippets

## Installation
In order to be able to run these from bash like so:
```bash
ecs-logs --cluster <cluster> --service-name <service-name>
```
Please add the 'scripts' directory to your $PATH


In order to provide scripts with some sort of default values
Please add ~/.{script_name}-defaults file that contains the defaults definitions
For instance for the script 'ecs-logs'
```bash
cluster=ai-unit-microservice-cluster
```
will default the --cluster parameter to 'ai-unit-microservice-cluster'
