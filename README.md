# README

This mini app allows you to redirect to a URL via GitHub, particularly useful when dealing with systems that don't allow ports in the URL. It works by taking the URL with the port, splitting it into parts, and then redirecting to the same URL but without the port.

## How to Use

To use this app, simply navigate to https://deriv-experiments.github.io/redirect-to and add your URL with the port to the end of the URL as a path.

For example, if you want to redirect to a URL with the port `8080`, you would navigate to https://deriv-experiments.github.io/redirect-to/your-url-here:8080.

If your URL also contains additional path parts, you can include them after the port, separated by slashes. For example, if your URL is `your-url-here:8080/path/to/resource`, you would navigate to https://deriv-experiments.github.io/redirect-to/your-url-here:8080/path/to/resource.
