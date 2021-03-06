# [GE 14293](https://byjasco.com/ge-z-wave-plus-wall-smart-switch-light-almond-toggle-500s)

### Run actions on either single *or* double press events from a GE/Jasco in-wall toggle switch.

This blueprint should only be used for single press events if you need to act on "on" presses while the switch is already on or "off" presses while the switch is already off. Otherwise, simply act on changes of the switch's switch entity instead.

## Configuring the switch:

1. Select your switch in the Z-Wave Node Management interface
2. Under "Node Group Associations," select either "2: Basic - Local Load" or "3: Basic - Double Tap" for single or double press events, respectively
3. For the node to control, select your Z-Wave controller (Node 1)
4. Click "Add to Group"

Refresh the configuration page and repeat selecting the node group to confirm that the association was successfully created.