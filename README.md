# PSDataAccessPlugin
The PSDataAccessPlugin is used, along with an API client (like [SwiftyPSCore](https://github.com/dougpenny/SwiftyPSCore) or [PyPowerSchool](https://github.com/dougpenny/PyPowerSchool)), to interact with PowerSchool API. The plugin does a couple of things:
1. Provides the credentials needed to connect with the PowerSchool API using an API client.
2. Allows you to use core [PowerQueries](https://support.powerschool.com/developer/#/page/powerqueries). Please note that for any core PowerQueries you would like to use, you will need to update the <[access-request](https://support.powerschool.com/developer/#/page/access-request)> element accordingly.

You can use the plugin as is, or you can modify and add to it as you see fit. To install the plugin, simply navigate to the Plugin Managment Dashboard in PowerSchool and upload the `plugin.xml` file.