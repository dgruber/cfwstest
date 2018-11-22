# Simple test of WebSocket functionality for Cloud Foundry

Origin: https://github.com/gorilla/websocket/tree/master/examples/echo

## Usage

> cf push

PWS: Point your browser to URL *but use port 4443*.

Example: https://my-ws.cfapps.io:4443/

Note that Amazon ELB does not support websocket upgrade hence TCP is 
the required protocol for the load balancer.
