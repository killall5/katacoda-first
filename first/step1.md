First IP is ?

`echo [[HOST1_IP]] > whoami`{{execute HOST1}}

`echo [[HOST2_IP]] > whoami`{{execute HOST2}}

`ssh -o StrictHostKeyChecking=no [[HOST2_IP]] cat whoami`{{execute HOST1}}

`echo [[HOST_IP]] [[HOST1_IP]] [[HOST2_IP]]`{{execute HOST2}}
