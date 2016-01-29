# grafana-cli
Simple Command Line Interface (CLI) wrapper around the Grafana API

Grafana CLI simplify manipulation of organisations and datasources by using the
Grafana API.

```
$ grafana-cli --help 
Usage: grafana-cli [OPTION] [COMMAND]

OPTIONS:
  -c, --credentials=<filename> 
  -h, --help                Print help information

COMMANDS
  get_org                    Get the current organisation for the current user
  rename_current_org <name>  Rename the current organisation to <name>
  change_org <orgname>       Change current organisation to <orgname> for the current user
  list_datasources           List the datasources for the current org. 
  delete_datasource <name>   Delete datsource with <name> from current org.       
  add_datasource <file>      Add datsource from json <file> to current org.       
  create_org <name>          Create new organisation with <name>
  delete_org <name>          Delete organisation with <name>
  list_orgs                  List all organisations in this grafana instance
  
There is no default behavior. 
```
