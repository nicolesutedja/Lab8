# Lab8-Starter

Name: Xuanye Wang, Nicole Sutedja

How are graceful degradation and service workers related?

Graceful degradation is the design principle of starting with a full-featured experience and ensuring the app still works reasonably under nonideal conditions, such as lack of network connection. Service workers are a tool that makes this possible on the web. By intercepting network requests and serving cached responses, they let an app continue to function (loading HTML, CSS, JS, images, and previously-fetched data) even when the user is offline or on a slow connection. In this way, service workers implement graceful degradation on the network layer by allowing the app degrades from "fresh data from the server" down to "cached data from the browser," instead of failing entirely.