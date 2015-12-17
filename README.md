# Eclipse Che
[![Join the chat at https://gitter.im/eclipse/che](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/eclipse/che?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Travis Build Status](https://travis-ci.org/codenvy/che.svg?branch=master)](https://travis-ci.org/codenvy/che)
[![Windows Build status](https://ci.appveyor.com/api/projects/status/ro78pmwomlklkwbo?svg=true)](https://ci.appveyor.com/project/codenvy/che)

[![License](https://img.shields.io/github/license/codenvy/che.svg)](https://github.com/codenvy/che)
[![Latest tag](https://img.shields.io/github/tag/codenvy/che.svg)](https://github.com/codenvy/che/tags)


https://www.eclipse.org/che/

High performance, open source software developer workspaces in the cloud.

### Cloud IDE
Use your browser to program on any machine in any language. Edit, build, debug and deploy projects bound to source repositories.  [Use Che as an IDE] (https://eclipse-che.readme.io/docs/import-a-project)

### Workspace Server
Create developer workspaces with APIs. Add your project types, embed custom commands and host on any infrastructure. [Use Che as a Workspace Server] (https://eclipse-che.readme.io/docs/create-workspaces-and-projects)

### Plug-Ins
Use Che's built-in language plug-ins or write packaged extensions that transform Che's IDE into new tools and assemblies. [Write Che IDE Plug-Ins] (https://eclipse-che.readme.io/docs/extension-development-workflow)



![Eclipse Che](https://www.eclipse.org/che/img/che-autocomplete.png "Eclipse Che")

Che can be installed on any OS that supports Java 1.8 - desktop, server or cloud, and Maven 3.1.1 or higher. It has been tested on Ubuntu, Linux, MacOS and Windows. 

### License
Che is open sourced under the Eclipse Public License 1.0.

### Clone

```sh
git clone https://github.com/codenvy/che.git
```
If master is unstable, checkout the latest tagged version.

### Build and Run
```sh
cd che
mvn clean install

# A new assembly is packaged into:
cd target/eclipse-che-<version>/eclipse-che-<version>

# Executable files are:
bin/che.sh  [ start | stop ]
bin/che.bat [ start | stop ]
```
Che will be available at ```localhost:8080```


### Sub-Projects:
* **che-core**:                [Core components] (http://github.com/codenvy/che-core)
* **che-plugins**:             [Language & tooling extensions] (http://github.com/codenvy/che-plugins)
* **che-depmgt**:              [Maven dependency management POM] (http://github.com/codenvy/che-depmgt)
* **che-parent**:              [Maven parent POM] (http://github.com/codenvy/che-parent)
* **cli**:                     [CLI for interacting with Che remotely] (http://github.com/codenvy/cli)
* **eclipse-plugin**:          [An Eclipse plug-in for running Che projects] (http://github.com/codenvy/eclipse-plugin)

### Engage
* **Contribute:** We accept pull requests. Please see [how to contribute] (https://github.com/codenvy/che/blob/master/CONTRIBUTING.md).
* **Support:** You can report bugs and contribute [che-dev@eclipse.org](email:che-dev@eclipse.org). 
* **Website:** [eclipse.org/che](https://eclipse.org/che)
