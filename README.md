# Node.js Server Hang

This repository demonstrates a common issue in Node.js applications: a server hanging due to a long-running synchronous operation in the request handler.  The synchronous `while` loop blocks the event loop, preventing the server from responding to further requests.  The solution showcases how to address this using asynchronous operations or worker threads.