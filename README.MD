# Website Example

A fully responsive site template designed by [HTML5 UP](https://html5up.net).

## Installation

This is a static website. You can simply open the `index.html` file in your browser, or host it on any static web server.

For local development, you can use a simple Python HTTP server:

```bash
python -m http.server
```

Or a similar tool.

## Deployment

Before deployment, you should replace the `DEPLOYREF` placeholder in `index.html`. This is used to track the version of the deployed code.

In `index.html`, find the following line:

```html
<meta name="deployref" content="DEPLOYREF">
```

Replace `DEPLOYREF` with the actual deployment reference, for example, a git commit hash.

## Testing

The project includes a simple test script. To run the tests, execute the following command:

```bash
./test.sh
```
