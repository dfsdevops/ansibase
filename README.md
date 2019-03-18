# ansibase

### Goals
* Written in Golang
* Redis back-end
* generic enough for any kind of ansible supported data structures (lists, dictionaries)
* Able to unmarshall YAML inventory into Key/Value structure
* Import and export YAML inventories
* Simple to operate from CLI. Add new host, add host to group, add variable to host, delete variable from host. Manipulate variables
* `--list` creates ansible dynamic inventory compatible output.

### Longer term goals
* Run in server mode. Add Web UI/API.
* Docker/K8s support
* Use database as a vars source for Helm, dynamically apply vars to Charts. 
