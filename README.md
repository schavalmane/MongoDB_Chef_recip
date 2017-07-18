# MongoDB_Chef_recip
Chef node that can configure  Data , Config and router node on a  given server

#Assumption
  1) Make sure yum repo is setup . We can do this via Chef also
  2) First node will be the master and any subsequient node you add will be a replica but capable on becoming master
  3) There will only be one master and rest all replicas . So if you want to have more Shards then make sure you host group and push the receiped based on your requirement.
  
