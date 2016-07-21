# Postman
Repo for my various Postman scripts so I can share with others.  Note that all collections will first begin with ACI Fabric Login, as it assumes you have not yet done so.  This does not hurt anything if you are already logged in.

You should first import the Postman environment provided here as file <I>AMS-ACI.postman_environment.</I>
<BR><BR>
Each of the collections refers to an existing evironment with APIC IP, Login and Password variables already set.
<BR><BR>
Note that after you import this enviroment, that you will have to modify the variable values to match your own ACI setup.
<BR>
<HR>
<B>Postman Collections:</B>
<HR>
<B>Collection #1:  REGISTER ACI NODES</B>
<BR>
  -This will register a series of nodes as part of initial fabric discovery, based on serial number, and sets node name and node number.  Note that each environment is unique, so change the values in the body of the POST to your own values.  
<BR><BR>
<B>Collection #2:  SET OOB IP ON NODES</B>
<BR>
  -This will set the OOB IP addresses for all leafs and spines.  Note that each environment is unique, so change the values in the body of the POST to your own values.  
  <BR><BR>
