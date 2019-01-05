# FSE 2019 project: Basura smart trash can
This project bundles the components of the Basura smart trash can demonstrator project used by Full Stack Embedded.
The full architecture of the Basura system is described in its [architecture document](https://goo.gl/AqpBBp).

# Deploying Basura
Optimally, two Raspberry Pis are used for the deployment of Basura.
In the FSE 2019 standard configuration, one is configured with hostname `basura-server`, the other with hostname `basura-trashcan`.

1. Connect the Raspberry Pis to the ([wireless](https://fullstackembedded.com/tutorials/configuring-a-raspberry-pi-for-wifi/)) network you want them to work in.
1. Download the basura-trashcan and basura-server repositories to the Pis you want to deploy them onto.
1. Make sure that the hardware is properly wired, as described in the [board description](https://github.com/freaf87/FSEDevBoard/blob/master/03_Docs/Documentation/FSEDevBoardDoc.pdf).
1. Install the server and trashcan as described in their README files.
