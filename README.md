# RatTracker

The RatTracker is a C# WPF tool designed to assist rats in tracking their active cases.
Using NetLog parsing, it detects your interaction with the client, on such things as receiving 
and accepting their friend request, winging with them, and arriving in their system. It can even
see when you succesfully get a Normalspace instance with the client, which is where you need
to be to give them All The Fuel!

## Building the solution

The solution is written in VS2015, under .NET Framework 4.5.2. You should be able to just clone
the repository, open the solution, and build it.
NuGet requirements are:
* Newtonsoft.JSon
* Websocket4Net
* Ookii.Dialogs


