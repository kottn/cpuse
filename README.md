# cpuse
Checking CPU utilization rate of all machines in the cluster.

## Usage
```
$ cpuse
```

## Requirement
* `rsh` from master-node to slave-nodes without password
* **Advanced:** `parallel` in master-node

## Getting started
Clone this repo, then
```
$ su -
# vi nodelist
# cp nodelist /etc
# cp cpuse /path/to/bin
```
