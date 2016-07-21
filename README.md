# Postman
Repo for my various Postman scripts so I can share with others.  Note that all collections will first begin with ACI Fabric Login, as it assumes you have not yet done so.  This does not hurt anything if you are already logged in.

Note that all collections also assume that you have already setup a Postman Environment with the following variables already declared and values set (otherwise your login won't work):
<BR><BR>
<I>apic
<BR>
username 
<BR>
password 
<BR></I>
<BR>
If you don't have one, you can import that environment provided here as file <I>AMS-ACI.postman_environment<\I>.  Note that after you import this enviroment, that you will have to modify the variable values to match your own ACI setup.
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
