# Go App
This is a simple Todo App copied from [here](https://github.com/NeuraLegion/go-todoapp-demo)
It is built with Go and the [chi router](https://github.com/go-chi/chi). The app uses [Vue](https://vuejs.org/) to render the HTML.

## Usage

> If you prefer to skip the installation process, you can download the prebuilt binaries directly: https://github.com/NeuraLegion/go-todoapp-demo/releases/latest

Clone this repository to your local machine:

```bash
$ git clone https://github.com/NeuraLegion/go-todoapp-demo.git
```

Install the necessary dependencies:

```bash
$ go mod download
```

Then you just need to start the server:

```bash
$ go run main.go
```

> By default, the server in this example listens on port 9000. If you wish to use a different port, you can specify the `-p` option to configure the desired port.

While having the server running, open a browser and type `http://localhost:9000/`, and hit enter to explore the application.

> To access the comprehensive API documentation in the OpenAPI Specification (OAS) format, you can find the specification at the following path: [./docs/openapi3.yaml](./docs/openapi3.yaml).
