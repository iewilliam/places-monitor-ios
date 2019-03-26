# Getting started with ACPPlacesMonitor for iOS

Table of Contents

1. [About this project](#about-this-project)
2. [Current version](#current-version)
3. [Contributing to the project](#contributing-to-the-project)
4. [Environment setup](#environment-setup)
    - [Open the Xcode workspace](#open-the-xcode-workspace)
    - [Command line integration](#command-line-integration)    

## About this project

The ACPPlacesMonitor for iOS library is used to manage the integration between iOS's CLLocationManager and the [ACPPlaces extension](https://cocoapods.org/pods/ACPPlaces) for the [Adobe Experience Platform SDK](https://github.com/Adobe-Marketing-Cloud/acp-sdks).

## Current version

[![Cocoapods](https://img.shields.io/cocoapods/v/ACPPlacesMonitor.svg?color=orange&label=ACPPlacesMonitor&logo=apple&logoColor=white&style=flat-square)](https://cocoapods.org/pods/ACPPlacesMonitor)

## Contributing to the project

Adobe is not currently accepting external contributions for this project, as it is still in the process of being fully set up. It is our desire to open this project to external contributions in the near future.

We look forward to working with you!

## Environment setup

The first time you clone or download the project, you should run the following from the root directory to setup the environment:

~~~~
make setup
~~~~

Subsequently, you can make sure your environment is updated by running the following:

~~~~
make update
~~~~

#### Open the Xcode workspace

Open the workspace in Xcode by running the following command from the root directory of the repository:

~~~
open ACPPlacesMonitor.xcworkspace
~~~

#### Command line integration

From command line you can build the project by running the following command:

~~~~
make build
~~~~

You can also run the unit test suite from command line:

~~~~
make test
~~~~