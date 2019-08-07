# node-red-contrib-camunda-bpm
CamundaBPM external task nodes for Node-RED 

This module integrates the CamundaBPM external task client https://github.com/camunda/camunda-external-task-client-js.
It will provide the following nodes for Node-RED:

### subscribe
Creates a task worker and subscribes to an external task topic. This node outputs a Node-RED message for each newly received task.
* inputs: 0
* outputs: 1

### complete
When a Node-RED message is received at the input, this node completes a specific CamundaBPM task (with either success or failure).
* inputs: 1
* outputs: 0
