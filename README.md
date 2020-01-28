# devstack
a neat way to manage all of your fivem servers

## Routes I need to setup

### /servers/ (GET)

> /servers (GET)

Returns a list of your servers, their names, statuses and IDs
> /servers/:id (GET)

Returns a full status of a server including resource usage and other stuff
> /servers/:id/resources (GET)

Returns a full list of all resources that are active and or inactive.
> /servers/:id/tasks (GET)

Returns a full list of all tasks that the server has
> /servers/:id/perms (GET)

Allows you to modify the permission sets of groups

### /servers/ (POST)

> /servers/:id/create (POST)
Create a new server

> /servers/:id/resources (POST)

Enable or disable a resource
> /servers/:id/tasks (POST)

Add or remove a task
> /servers/:id/perms (POST)
Add or remove a permset

> /servers/:id/a/stop (POST)

Stop Server
> /servers/:id/a/start (POST)

Start Server
> /servers/:id/a/restart (POST)

Restart server
> /servers/:id/a/sync (POST)

Sync server with git branch
