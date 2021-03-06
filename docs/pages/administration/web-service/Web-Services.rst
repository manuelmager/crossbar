:orphan:

Web Services
============

Crossbar.io has a built-in Web server that provides various configurable
Web services and
`scales <https://github.com/crossbario/crossbarexamples/tree/master/benchmark/web>`__
to 100k's requests per second on multi-core.

To use these Web services, configure a Crossbar.io :doc:`Router
Worker <../worker/Router-Configuration>` with a :doc:`Web
Transport <../router/transport/Web-Transport-and-Services>`, and then configure the
Web services you want to run on that transport:

-  :doc:`Path Service <Path-Service>`
-  :doc:`Static Web Service <Static-Web-Service>`
-  :doc:`File Upload Service <File-Upload-Service>`
-  :doc:`WebSocket Service <WebSocket-Service>`
-  :doc:`Long-poll Service <Long-Poll-Service>`
-  :doc:`Web Redirection Service <Web-Redirection-Service>`
-  :doc:`Reverse Proxy Service <Reverse-Proxy-Service>`
-  :doc:`JSON Value Service <JSON-Value-Service>`
-  :doc:`CGI Script Service <CGI-Script-Service>`
-  :doc:`WSGI Host Service <WSGI-Host-Service>`
-  :doc:`Resource Service <Resource-Service>`
-  :doc:`Node Info Service <Node-Info-Service>`

The following features of the :doc:`HTTP Bridge <../http-bridge/HTTP-Bridge>` are also
run as Web services on a Web transport of a router:

-  :doc:`HTTP Bridge Publisher <../http-bridge/HTTP-Bridge-Publisher>`
-  :doc:`HTTP Bridge Subscriber <../http-bridge/HTTP-Bridge-Subscriber>`
-  :doc:`HTTP Bridge Caller <../http-bridge/HTTP-Bridge-Caller>`
-  :doc:`HTTP Bridge Callee <../http-bridge/HTTP-Bridge-Callee>`
-  :doc:`HTTP Bridge Webhook <../http-bridge/HTTP-Bridge-Webhook>`
