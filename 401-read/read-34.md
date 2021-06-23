# Configuring Django Settings

**Issues :**
- Different environments : 
You can use different environments in Django so You need an approach that allows you to keep all these Django setting configurations.
- Sensitive data : Sensitive data in Django should be kept in a safe place
- Sharing settings between team members : There must be an approach to dealing with third parties and adjust appropriate settings

Setting Configuration approaches :
settings_local.py : Create a local settings file that is ignored and not uploaded to GitHub but You need to have settings_local.example to share the default configurations for developers.

Environment variables are used to protect sensitive data and are used for redundant data


The 12 factors that make it easy to develop your project in the future :
Codebase
Dependencies
Config
Backing services
Build, release, run
Processes
Port binding
Concurrency
Disposability
Dev/prod parity
Logs
Admin processes



# SSH
SSH, or Secure Shell, is a remote administration protocol that allows users to control and modify their remote servers over the Internet  ,  uses cryptographic techniques to ensure that all communication to and from the remote server happens in an encrypted manner

SSH can be used directly in Linux and Mac, while you will need a client like PuTTY to use SSH in Windows

The parties to the connection in SSH :
 Host refers to the remote server you are trying to access
client is the computer you are using to access the host

encryption technologies of SSH:
Symmetrical encryption
Asymmetrical encryption
Hashing.

