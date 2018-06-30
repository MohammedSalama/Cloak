# Cloak
Cloak

Cloak is an intelligent python backdoor framework*.
What it exactly does?
Cloak generates a python payload via msfvenom and then intelligently injects it into the python script you specify.

To evade basic detection, Cloak breaks the payload into several parts and places it in different places in the code. If you want the victim to run your injected script as root, Cloak can handle that too. Cloak will be further upgraded in future to support a wide range of payloads, platforms and evasion techniques.



Compatibility
Cloak works best on Linux and is compatible with both python2 and python3. Dependencies:

msfvenom
Contribute
For now, Cloak can backdoor python scripts but I am looking forward to do the same for C, bash and perl scripts. Currently, the default connection method is https and Cloak creates a staged and reverse payload. So, of course the I will try to extend its capabilities which also includes bypassing lowkey AV solutions in windows.
If you like the idea, help me achieve the goals. The code is well documented so if you want to contribute you are not going to face any problems. Modify the code, add and improve and start a pull request.
If you find a bug in the code don't hesitate to start an issue.

Email: mohamed96salama@gmail.com
