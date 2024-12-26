# Sideloadly MACOS
Fix errors related to sideloadly

//
E1. Could not listen: listen tcp: lookup localhost: no such host
means the application is unable to connect to the localhost address.

1. try verify the localhost domain: [ ping localhost ] 
-> If you don't get a response, there might be an issue with the localhost domain or your network configuration.

2.Check the Hosts File
Open Terminal and type: [ sudo nano /etc/hosts ] 

Make sure the following line exists in the file: { 127.0.0.1   localhost }

3. Update Sideloadly

4. Segmentation Fault (invalid memory address)
Check system logs using the Console app under Utilities for Sideloadly-related errors.

//
E2.
