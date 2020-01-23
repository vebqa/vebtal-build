# vebtal-build

[![Build Status](https://travis-ci.org/vebqa/vebtal-build.svg?branch=master)](https://travis-ci.org/vebqa/vebtal-build)

# create an opental solution

* check out build project and copy the project to a new one, e.g. "opental-solution"
* open pom.xml and remove the adapter you dont need in your solution by comments
* resolve the configuration by updating the maven project
* create a /conf folder
* create a file "manager_user.properties" inside the /conf folder

# global configuration

* activate the REST server: use the key "server.port" in your manager_user.properties
* setup the size of the manager dialog:
  * manager.width= <pixel, e.g. 800>
  * manager.height= <pixel, e.g. 600>

# configure adapter

The following adapter doesn't need a user configuration

* pdf
* msg

Configure selenium adapter

* download the specific webdriver driver, you can find the links to the different implementations here: https://selenium.dev/downloads/

* create a folder /driver in your solution project and copy the driver to this place

Configure imagecompare adapter

Configure telnet 3270 adapter

Configure telnet 5250 adapter