# Simplilearn Chat App
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.5.

## Development server

First run `npm install` to install the neccesary dependencies.

Run `ng serve ` for a dev server. Navigate to `http://localhost:8000/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Dockerized

This repo has been Dockerized for use in creating a Docker image. To do so, simply run `docker build . -t quiz` to compile the application into a Docker image. To run, use a command such as `docker run -p 3000:80 quiz` that would allow access via port 3000 to the running application.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
