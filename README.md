# Demo
ServiceNow, VMWare for AnsibleFest/Summit 2023 luncheon.

# Premise
We have some important web app. It is vital that this app be up and available. Additionally, humans like to sleep and do other things besides watch for 404's. How many administrators enjoy getting a call at 2am that the important app is down? 

We have monitoring for this app but human interaction is not required. When the app is down, `ansible-rulebook` attempts to auto-remediate. This demo attempts two kinds of auto-remediation. The fist is at the application layer, `ansible` contacts the server and deploys the app. If the server cannot be reached `ansible` uses VMWare virtualization to restore the server from snapshot. Since `ansible` can integrate with ServiceNow IT Service Management, `ansible` updates operational status in real time as issues are detected and remediated. 

# ToDo
1. get this working with a VMWare open environment.
1. replace Gerald's dog with a cute kitty cat

