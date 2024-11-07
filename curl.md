# Curl Common Options
## -X, --request
- Specify a custom request method to use when communicating with the HTTP server.
- The specified request method will be used instead of the method otherwise used (which defaults to GET).
- Read more
```bash
curl -X POST http://example.com
```
## -H, --header
- Extra header to include in the request when sending HTTP to a server.
- You may specify any number of extra headers.
- Read more
```bash
curl -H "Content-Type: application/json" http://example.com
```
## -d, --data
- Send specified data in a POST request to the HTTP server.
- Read more
```bash
curl -d "param1=value1&param2=value2" http://example.com
```
## -o, --output
- Write output to a file instead of stdout.
- If you are using {} or [] to fetch multiple documents, you can use {} to refer to the current document.
- Read more
```bash
curl -o output.txt http://example.com
```
## -O, --remote-name
- Write output to a file named as the remote file.
- The remote file name to use for saving is extracted from the given URL, nothing else.
- Read more
```bash
curl -O http://example.com/file.zip
```
## -L, --location
- Follow redirects.
- If the server reports that the requested page has moved to a different location (indicated with a Location: header and a 3XX response code), this option will make curl redo the request on the new place.
- Read more
```bash
curl -L http://example.com
```
## -i, --include
- Include the HTTP response headers in the output.
- The HTTP response headers can include things like server name, cookies, date of the document, HTTP version, and more...
- Read more
```bash
curl -i http://example.com
```
## -v, --verbose
- Make the operation more talkative.
- This option makes curl verbose during the operation.
- Read more
```bash
curl -v http://example.com
```
## -s, --silent
- Silent or quiet mode.
- Don't show progress meter or error messages.
- Read more
```bash
curl -s http://example.com
```
## -S, --show-error
- Show error.
- When used with -s it makes curl show an error message if it fails.
- Read more
```bash
curl -sS http://example.com
```
## -k, --insecure
- Allow connections to SSL sites without certs.
- This option allows curl to proceed and operate even for server connections otherwise considered insecure.
- Read more
```bash
curl -k https://example.com
```
## -u, --user
- Specify the user name and password to use for server authentication.
- Read more
```bash
curl -u username:password http://example.com
```
## -A, --user-agent
- Send User-Agent header to server.
- Some servers don't like requests that are made without a User-Agent header.
- Read more
```bash
curl -A "Mozilla/5.0" http://example.com
```
## -e, --referer
- Send Referer header to server.
- Some servers require the Referer header to be set to allow the request.
- Read more
```bash
curl -e http://example.com http://example.com
```
## -x, --proxy
- Use the specified HTTP proxy.
- If the port number is not specified, it is assumed at port 1080.
- Read more
```bash
curl -x http://proxy.example.com:8080 http://example.com
```
## -h --help
- Display help information.
- Read more
```bash
curl --help
```
