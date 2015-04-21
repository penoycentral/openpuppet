####PE Console
```
  - manage node request
  - assign puppet classes to nodes and groups
  - view reports and activity graphs
  - trigger puppet run on demand
  - browse and compare resources
  - view inventory data
  - invoke orchestation
  - manage console users and privileges
```

###Nodes
```
 - displays the Daily run status
 - state: Total/Failed/Pending/Changed/Unchanged
```

###Groups
Collection of nodes

###Special Groups
```
 default : automatically add node to default group
 mcollective 
 no mcollective - manually added by admin
 puppet_master
 puppet_console
 puppet_db - contains db support node
```

###Classes
main unit of Puppet configuration

###Report
Provide for each node for each Puppet run
```
Metrics - rough summary
Log - logged messages table
Events - list of resources the run managed
```

###Inventory 
Inventory facts
```
1. search by Fact name & value
2. Located on the node detail page
```

###Live Management
Interface to PE Orchestation Engine ie. Mcollective

3 Main tabs
```
1. Browse Resources
2. Control Puppet
3. Advanced Tasks
```

###Events
Current State of the Infrastructure

Type of Events
```
Change 
Failure
Noop
Skip
``` 

