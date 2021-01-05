
This package is still under development.
Currenlty, it's missing the power-on button. This will come thbrough broadlink learn IR-function, but that function isn't available yet.
Will follow once broadlik is running in meta

This package delivers support for Samsung TV's with older protocols (2012 and earlier) to be controlled wit a NEEO-remote through HTTP.

For this, you need to have:

Preferably, a complete NEEO eco system can run on a rooted NEEO-brain, configured by installmeta.sh (see https://github.com/jac459/neeo2021onward/tree/main/Meta%20running%20in%20Brain)
and the files in this package.
 
Alternatively, it can run on:
- the metadriver installed at an arbitrary location of your own choice (see https://github.com/jac459/metadriver)
- an mqtt-installation (tested with mosquitto)
- a node-red installation.


This flow has two types of nodes:
1) MQTT as the default communication-method with the Metadriver running on the NEEO Brain.
2) Target-nodes which represent the equipment; in this case they are called SamsungTV.

Use these two types that are also used in the generic description found at https://github.com/jac459/neeo2021onward/blob/main/Instructions_for_Flows_Node-RED_FLOW.MD