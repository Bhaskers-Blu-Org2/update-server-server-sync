# Microsoft.UpdateServices Server Sync

This code library provides a C# implementation (.NET Core) of the Microsoft Update Server-Server sync protocol, for both the client and server roles.

Use the [client implementation](api/index.html#the-upstreamserverclient) to programmatically browse the Microsoft Update catalog, sync updates locally and run advanced queries on update metadata.

Use the [server implementation](api/index.html#the-upsteam-server) to distribute updates to downstream servers, like [WSUS](https://docs.microsoft.com/en-us/windows-server/administration/windows-server-update-services/get-started/windows-server-update-services-wsus) or server clients built with this library.

To deploy Microsoft updates fetched with this library to Windows client PCs, use the [Microsoft Update Client Sync library](https://microsoft.github.io/update-client-server-sync/) and [GitHub repo](https://github.com/microsoft/update-client-server-sync).

See [MS-WSUSSS](https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-wsusss/f49f0c3e-a426-4b4b-b401-9aeb2892815c) for the complete technical documentation of the protocol.

See [Windows Server Update Server](https://docs.microsoft.com/en-us/windows-server/administration/windows-server-update-services/get-started/windows-server-update-services-wsus) for an introduction to WSUS.
