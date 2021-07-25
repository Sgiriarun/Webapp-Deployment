# cloudformation script for **Web-application**

## Task
 Used to **deploy** high availability web-application, which in _public bucket_ and logging information through **ssh by bastion instances** using AWS cloud.

## Installation
just 
 clone this project [https://github.com/Sgiriarun/Webapp-Deployment.git]
  requires 
  * Editor for _YAML and Json_ script(**VScode**)
  * **Git-bash** for terminal
  * here two variant instances are used(**LINUX and UBUNTU**) so loging to be done with its own command line 

## How to USE

* Git-bash for launching stacks using command(before using command, ensure you have copied file create.sh and update.sh) and script is based on specific high availability location
  * ./create.sh first network.yml parameters.json
  * ./update.sh Bastion jumpbox.yml parameter.json

* _Create and use_ your **own Key** for logging instances

* Git-bash for ssh-client terminal 
 * _use your IPv4 address for ssh in script_(**MyIP parameter value**)


