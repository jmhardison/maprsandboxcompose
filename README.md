# MapR Sandbox
## ComposeFile Deployment

This is a reductionist take on making a mapr dev sandbox. The source for this effort is [here](https://mapr.com/docs/61/MapRContainerDevelopers/MapRContainerDevelopersOverview.html).

### Executing
To launch an instance, your environment will need at least 8GB available to the engine. If you are executing on desktop, adjust your docker desktop preferences and restart the engine.

* Clone the repository.
* Execute `docker-compose up -d` to run headless.
* Wait... and wait some more. First launch will take a while.

### Default user

* username: mapr
* password: mapr

### Troubleshooting

* The container maps a large amount of host ports, and as such may have a conflict. Review the docker-compose file and adjust as required. Or if you choose, convert them all to dynamic port mappings.