# Coin Flip Game

Pick heads or tails, the server flips a coin, and you find out if you called it. Served by a handmade Node server with just the http and fs modules.

![Coin Flip Game screenshot](screenshot.png)

The fun challenge: HTTP doesn't remember anything. Every flip is a brand new request, so the whole game, guess, flip, and result, has to happen inside a single request-response cycle.

Run it with `node server.js`. My code is on the `answer` branch.
