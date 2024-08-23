# Module Federation Demo

A simple demo on Microfrontend with Module Federation in React

<img src="https://user-images.githubusercontent.com/19681625/221417269-59fb9cb9-2d8a-4e05-8a54-562679aec22b.png" width="500" />

## Getting started

In the project directory, run:

> ```
> cd header-app && yarn && yarn start
> cd home-app && yarn && yarn start
> ```

Open [http://localhost:3000](http://localhost:3000) to view module federated Home App\
Open [http://localhost:3001](http://localhost:3000) to view module federated Header App


## Managing versions

To manage versions as a solution git could be used. When a new release is ready - in git a new flag could be added witha new version number.
Another approach is to create a new branch to each release and keep it to revert changes in case something went wrong.
Of course these techniques could be combined.

## CI/CD

Regarding CI/CD  it depends on applications. CI/CD pipeline could be triggered separately for one or more projects, that allow flexible approach in creating independant applications or an application that consists of several applications
