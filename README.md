# nginx, docker, vueJS, nodeJS
Configs and sample files for vueJS and expressJS apps running on nginx.
I collected the for me most meaningful snippets. Most of them i use in production apps or for development.

## Examples

[vueJS app with expressJS and mongoDB](https://github.com/peterklein/nginx-docker-vue-node/blob/master/examples/vuejs-nodejs-mongo)

## Config

After changing the config files run `nginx -t` to check if the syntax is ok and there are no errors. Otherwise the server will not be reloaded or restarted.
