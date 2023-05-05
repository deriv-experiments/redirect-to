# redirect-to

This is a small web application that allows you to redirect to a URL with a port in it, especially useful when dealing with systems that do not allow ports in the URL. The application is hosted at [https://deriv-experiments.github.io/redirect-to](https://deriv-experiments.github.io/redirect-to).

## Usage

To use this application, simply append the target host, port, and any additional path or query parameters to the base URL:

```
https://deriv-experiments.github.io/redirect-to/PROTOCOL/HOST/PORT/ADDITIONAL_PATH?QUERY_PARAMETERS
```

Replace `PROTOCOL`, `HOST`, `PORT`, `ADDITIONAL_PATH`, and `QUERY_PARAMETERS` with the desired values.

For example, to redirect to `http://example.com:8080/some/path?param=value`, you would use:

```
https://deriv-experiments.github.io/redirect-to/http/example.com/8080/some/path?param=value
```

## How it works

The application uses JavaScript to parse the URL and extract the host, port, additional path, and query parameters. Then, it redirects the user to the target URL by updating the `window.location` property.
