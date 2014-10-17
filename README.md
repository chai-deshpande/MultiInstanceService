Muti Instance Service
=====================

Utility class for allowing windows service implemented in .NET to have multiple instances on the same machine.

Ideally the ServiceInstaller and the ServiceBase classes that are provided in the .NET framework should have been implemented to read the service name from a config file. But, the default Windows Service project template hard codes the service name and hence when we install it using InstallUtil.exe you cannot specify a name.

There are a few variants available on StackOverflow.com that show you how to achive this, and all of them work. Then why the hell did I put this together?! Just so that it becomes quick and easy for people to either copy paste this code and use it in their service. Or simply reference the assembly from NuGet so that you can automatically take advantage of any updates to this utility class.
