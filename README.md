# Nutanix PRISM and APIs

PRISM is a powerful tool to manage Nutanix clusters via GUI, but is also very powerful in exposing full set of APIs to let the system to be integrated with external entities.

in this example a Slack bot is used to send command to a Prism Central using APIs.
the ask program will list VMs, Images and Blueprints registered

detail program will give providers registered to a particular blueprint that must be the input of the script

run script will let you launch a blueprint after checking that it exist on the cluster and the provider is assigned to it

above 3 are just some examples on how to interact with APIs, potential is quite high.

A video of the interaction is published here: https://youtu.be/guTBBtlA7uA

Python scripts are not quite elegant, I started programming Python 3 months ago... last code I wrote was in Fortran in 1996 for my degree (I'm rather old) :-)
