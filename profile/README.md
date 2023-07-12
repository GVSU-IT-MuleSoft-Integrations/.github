## Put Mulesoft related information here.

# Using the mule-development-template
Unless updating the template do not pull code from this repository. When creating a new repository here use the mule-development-template as the template during creation.

# CICD Pipeline GitHub environment secrets:
Test and Prod values will differ:
- ANYPOINT_PLATFORM_API_CLIENT_ID = AnyPoint MQ client ID from Anypoint platform -> MQ -> Client Apps
- ANYPOINT_PLATFORM_API_CLIENT_SECRET = AnyPoint MQ client secret from Anypoint platform -> MQ -> Client Apps
- ANYPOINT_PLATFORM_CONNECTED_APP_CLIENT_ID = CICD from the Anypoint platform -> Access management -> Connected Apps (Mule Admin required)
- ANYPOINT_PLATFORM_CONNECTED_APP_CLIENT_SECRET = CICD from Anypoint platform -> Access management -> Connected Apps
- GVSU_NEXUS_PASSWORD = Given by MuleSoft Support (if need arises to get new password), for GVSU users currently shared via lastpass
- MULE_ENCRYPTION_KEY = Created by GVSU IT staff, stored currently via lastpass
