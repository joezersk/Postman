# Postman for ACI
Repo for my various ACI Postman scripts so I can share with others.  Note that all collections will first begin with ACI Fabric Login, as it assumes you have not yet done so.  This does not hurt anything if you are already logged in.

Each of the collections here refers to an existing Postman environment with APIC IP, Username and Password variables already set.
<BR><BR>
<B>You should first import the Postman environment provided here as file <I>AMS-ACI.postman_environment.</I></B>
<BR><BR>
Note that after you import this enviroment, that you will have to modify the variable values to match your own ACI setup.
<BR><BR>
If you prefer, I have recorded a series of short 5-minute videos on using Postman with ACI. <a href="https://www.youtube.com/channel/UCN_MNVF3e05YntJqdldGnvA"> You can view them on YouTube by clicking here.</a>
<BR>
<BR>
<HR>
<B>Postman Collections:</B>
<HR>
<B>Collection #1:  REGISTER ACI NODES</B>
<BR>
  -This will register a series of nodes as part of initial fabric discovery, based on serial number, and sets node name and node number.  Note that each environment is unique, so change the serial number and node values in the body of the POST to your own values.  
<BR><BR>
<B>Collection #2:  SET OOB IP ON NODES</B>
<BR>
  -This will set the OOB IP addresses for all leafs and spines.  This collection requires the use of an associated CSV file used in the Runner Window of Postman.  You can use the CSV file here and modify it to use your own values.  Please note that for some reason MS Excel CSV files contain some mystery formatting in the file structure and thus break in Postman.  Instead use Libre Office, Google Docs, or Numbers on a Macintosh to make or modify your CSV file.  
  <BR><BR>
