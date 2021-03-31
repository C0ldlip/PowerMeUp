# PowerMeUp
Add a local admin via a Service running under Administrator or SYSTEM

###Usage
- Change the code in Service1.cs to your situation (See annotation in code);

- Edit Environment of service to location of PowerMeUp.exe;
> sc(.exe) config SERVICE_NAME binPath= "./../../PowerMeUp.exe"

- Then, start and stop the service via net start / net stop;

- Enjoy your new privileges.
