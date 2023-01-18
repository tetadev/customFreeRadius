# Custom  Freeradius with alpine linux and postgres connection
##fun project Freeradius 

For more info check https://hub.docker.com/r/freeradius/freeradius-server

## NOTE

- Small size
- Postgres Only
- Remove mongo, sqlite, mysql etc

## Getting Started

Pull the image from Docker Hub: `docker pull ibrahimiii/freeradius-bnet:0.1-pg-alpine`

command 

 - `-migrate=true`
<pre>
if set true Environment CON must be set
example CON=postgres://postgres:SomeSecretPassword@postgres:5432/postgres
</pre>
- `-log=true`
<pre>
log can be set false
</pre>

## Command on shell
<pre>
if you want see log on shell
run ./bnetrad -log_only=true
</pre>

## Command on shell
<pre>
create sql config file 
For more info check https://hub.docker.com/r/freeradius/freeradius-server
</pre>

## Example
