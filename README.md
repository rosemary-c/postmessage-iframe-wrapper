# PostMessage iFrame Wrapper
Wrapper for iframe postMessage testing. Must have iframe src running on localhost:3000. Once python server is up and running append the following to the url `?iframeUrl=http://localhost:3000`.
Ex: `http://localhost:5500/?iframeUrl=http://localhost:3000`

## How to start server (localhost:8000)
If Python version returned above is 3.X
On Windows, try "python -m http.server" or "py -3 -m http.server"
- `python3 -m http.server 5500`

If Python version returned above is 2.X
- `python -m SimpleHTTPServer 5500`
