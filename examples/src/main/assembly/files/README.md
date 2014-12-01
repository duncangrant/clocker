Clocker
====

Entities and sample code to allow Brooklyn to deploy and manage a Docker cloud infrastructure.

## Getting Started

To get started, run the `clocker.sh` script. This will launch Brooklyn and the Clocker
console UI, with persistence and other useful default settings configured. You can also
use the `brooklyn.sh` script with the `clocker` command and alternative options.

    % ./bin/clocker.sh
    % ./bin/brooklyn.sh clocker

The Clocker catalog contains a blueprint for a Docker Cloud and some example
applications. To start a Docker Cloud using the provided `docker-cloud.yaml` blueprint
and its default options, use the following command:

    % ./bin/clocker.sh jclouds:aws-ec2:us-east-1

Other blueprints are provided in the `blueprints` directory to illustrate different
application configuration mechanisms.

## More Information

More details are available at the Clocker website and GitHub repository.

- http://clocker.io/
- http://github.com/brooklyncentral/clocker/

----
Copyright 2014 by Cloudsoft Corp[oration Limited

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
