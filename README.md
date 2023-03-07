<h1 align="center">
  Bunzz Fizz Buzz
</h1>

Fizz Buzz API built using Golang: Gin Framework for routing, Testify for testing, Swagger for Documentation, Viper for configuration, and Go Mod for dependency management.

## 🚀 Quick start

    You can use make to build/ run your app:

        make build
        make run

## 🧐 What's inside?

A quick look at the top-level files and directories you'll see in this project.

    .
    ├── build
    ├── config
    ├── controllers
    ├── docs
    ├── middlewares
    ├── server
    ├── tests
    ├── utils
    ├── Dockerfile
    ├── Makefile
    ├── go.mod
    ├── go.sum
    ├── main.go
    ├── .gitignore
    └── README.md

1.  **`/build`**: This directory contains the binary after a build

1.  **`/config`**: This directory contains the viper configration and the property files.

1.  **`/controllers`**: This directory contains the controllers that the router/handlers are configured to call.

1.  **`/docs`**: Directory for swagger files.

1.  **`/middlewares`**: This directory is used to house the middlewares used by the controllers.

1.  **`/server`**: This Directory houses the router and service files which configure the route and start the server

1.  **`/tests`**: This directory contains all the tests for your application and get kicked off by:

        make test

1.  **`/utils`**: This directory contains all the util classes used throughout the app.

1.  **`Dockerfile`**: This file contains the buildsteps to build your image using a multi stage build. It is currently using a scratch image to keep it lightweight.

1.  **`Makefile`**: This file allows the use of make to run tests, build locally, and is used to build in the pipeline. This can be expanded as needed

1.  **`go.mod/go.sum`**: These files are generated by Go Mod dependency management and can be learned about in the documentation link provided above.

1.  **`main.go`**: This file is the starting point for the application, which starts the server.

1.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

1.  **`README.md`**: A text file containing useful reference information about your project.
