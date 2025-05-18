ibmcloud cli commands

ibmcloud login --apikey <your-api-key>
ibmcloud login --sso
ibmcloud target
ibmcloud resource groups -> get all the resource groups
ibmcloud resource group-create <resource-group-name> -> Create resource group
ibmcloud resource group-delete <resource-group-name> -f   -> Deletes resource group
ibmcloud resource service-instances -> get all the resources
ibmcloud plugin repo-plugins -r 'IBM Cloud'


CLI plugin management - 

ibmcloud plugin list -> list available plugins
ibmcloud plugin update <plugin-name> -> updates a particular plugin
ibmcloud plugin update --all -> updates all the plugins
ibmcloud plugin repo-plugins -> shows all the plugins that you can install
ibmcloud plugin install <plugin-name> -> installs a particular plugin
ibmcloud plugin show <plugin-name> -> this shows all the commands registered with the plugin name


CLI catalogs commands - (needs catalogs-management plugin)

ibmcloud catalog list -> lists all the catalogs
ibmcloud catalog search --catalog "<catalog-name>" -> see services inside the catalog
ibmcloud catalog offering list --catalog "<catalog-name>" -> much detailed view of the service inside catalog

Ibmcloud catalog search <search-keyword> -> searches the catalog and outputs matches



Resource commands -

ibmcloud resource service-instances -> shows all the services currently deployed
ibmcloud resource service-instances -g <Resource-group-name> -> shows services deployed in a particular resource group
ibmcloud resource service-instance "<service-instance-name>" -> shows deployed service instance's details
ibmcloud resource search <search-keyword-for-instance-name> -> searches for keyword in service instances
