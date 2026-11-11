# Load Balancer

This project improves the web infrastructure by adding redundancy through multiple web servers.

## Task 0: Double the number of webservers

The script `0-custom_http_response_header`:

- Installs Nginx on a new Ubuntu server.
- Configures a custom HTTP response header called `X-Served-By`.
- Uses the server hostname as the header value.
- Tests the Nginx configuration.
- Restarts Nginx.

## Usage

Run the script with root privileges:

```bash
sudo ./0-custom_http_response_header
```

## Expected result

The HTTP response should contain a header identifying the server:

```text
X-Served-By: 7107-web-01
```
