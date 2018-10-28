# bauglir-websocket 2

Funktionsfähige Kopie der WebSocket-Bibliothek von Bauglir
(Original: https://code.google.com/archive/p/bauglir-websocket/)

Der Quelltext der Beispiele (Server, Client) wurde leicht angepasst, damit alles unter Lazarus (1.6.2) inkl. FPC (3.0.0) funktioniert.

# Working Version
See the Fork made by MFernstorm:
https://github.com/MFernstrom/Bauglir-WebSocket-2

+++

WebSocket server/client implementation in Pascal and C#
WebSocket - Pascal and C# implementations

Project contains implementation of clients and servers using WebSocket protocol.

SECOND VERSION OF BAUGLIR WEBSOCKET - HyBi 7-17 AND RFC WEBSOCKET SPECIFICATION

Current version: 2.0.4 (2012-01-30) #Changelog

For Hixi versions of specification (75, 76) use Bauglir WebSocket 1.1.0.

If you are using Bauglir WebSocket in production, please let me know (Bronislav.Klucka@bauglir.com)

If you are getting garbage from Chrome19: T problem is caused by x-deflate-frame extension in WebSocket implementation in Chrome see http://code.google.com/p/bauglir-websocket/issues/detail?id=37#c1 to refuse it from server
Implementations

    Pascal client and server implementation (source code documented). Support for non-secure and secure (SSL) connection.
    C# .NET client and server implementation (source code documented). Support for non-secure and secure (SSL) connection.

Implementation notes

There is Wiki page with [http://code.google.com/p/bauglir-websocket/wiki/Libraries interface description] '>
Demos

Check out the demos on YouTube! (Excuse my English...)

    Pascal
        Delphi client and server demos (Windows) - based directly on Pascal sources
        Lazarus client and server demos (Linux (Kubuntu)) - based directly on Pascal sources
    C# .NET
        C# .NET client and server demos (Windows & Linux) - based directly on C# sources
    HTML5 web pages for WebSocket compatible browsers (client) for testing server (e.g. Pascal demo).

Support

Supported HyBi versions: 7-17

Supported RFC versions: RFC6455

Supported browsers: * FireFox 11 * Aurora 11.0a2 (2012-01-11) supports binary data and close reason and code * Chrome 16 and up

Browser issues * Chrome * current stable release (16) and up should follow RFC * Firefox * does not support SSL with non-authorized keys
Notes

    Documentation on WebNt.eu WebSocket is in progress. See source code for documentation, it's fully documented.
    If you are still using 1st version, you should check its introduction page
