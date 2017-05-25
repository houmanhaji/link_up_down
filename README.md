  # link_up_down
  A case study of Deterlab's MAGI framework. link between two nodes in a network goes down and comes back live.  https://montage.deterlab.net/magi/index.html

  # files
  test_up_down.aal : description of the order and length of link status changes and the information about the destination node(server node)
  
  link_up_down.py : contains class link_up_down agent which has a method(link_down((self,message,dst)) to disrupt a link from the host computer to a server node (the dst input) and a method(link_up(self,message,dst)) bring it back up.
  
  link_up_down.idl : description of class link_up_down agent 


  # description
  This example could be run for any two PCs swapped in from Deterlab. The PCs have to be named 'clientnode' and 'servernode'.
  Specified in test_up_down.aal, the link between the nodes is disrupted for 10 seconds and comes back alive.


  # to run
  /share/magi/current/magi_orchestrator.py --experiment [yourExp]  --project [yourProj]  --events test_up_down.aal
  
  # screenshot
  
  ![screenshot](https://github.com/houmanhaji/link_up_down/blob/master/screenshot2.png)

  
