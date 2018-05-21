---
name: Azure SQL Database
x-slug: azure-sql-database
description: Make building and maintaining applications easier and more productive.
  With built-in intelligence that learns app patterns and adapts to maximize performance,
  reliability, and data protection, SQL Database is a cloud database built for developers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
x-kinRank: "10"
x-alexaRank: ""
tags: Pools
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/apis.md
specificationVersion: "0.14"
apis:
- name: Azure SQL Database API Elastic Pools Create Or Update
  x-api-slug: azure-sql-database-api
  description: Creates a new elastic pool or updates an existing elastic pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/elasticPools/{elasticPoolName}
  tags: Elastic Pools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolname-put-openapi.md
- name: Azure SQL Database API Elastic Pools Delete
  x-api-slug: azure-sql-database-api
  description: Deletes the elastic pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/elasticPools/{elasticPoolName}
  tags: Elastic Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolname-delete-openapi.md
- name: Azure SQL Database API Elastic Pools Get
  x-api-slug: azure-sql-database-api
  description: Gets an elastic pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/elasticPools/{elasticPoolName}
  tags: Elastic Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolname-get-openapi.md
- name: Azure SQL Database API Elastic Pools List By Server
  x-api-slug: azure-sql-database-api
  description: Returns a list of elastic pools in a server.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/elasticPools
  tags: Elastic Pools Server
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpools-get-openapi.md
- name: Azure SQL Database API Elastic Pools List Activity
  x-api-slug: azure-sql-database-api
  description: Returns elastic pool activities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/elasticPools/{elasticPoolName}/elasticPoolActivity
  tags: Elastic Pools Activity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolnameelasticpoolactivity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolnameelasticpoolactivity-get-openapi.md
- name: Azure SQL Database API Elastic Pools List Database Activity
  x-api-slug: azure-sql-database-api
  description: Returns activity on databases inside of an elastic pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/elasticPools/{elasticPoolName}/elasticPoolDatabaseActivity
  tags: Elastic Pools Database Activity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolnameelasticpooldatabaseactivity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolnameelasticpooldatabaseactivity-get-openapi.md
- name: Azure SQL Database API Elastic Pools Get Database
  x-api-slug: azure-sql-database-api
  description: Gets a database inside of an elastic pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/elasticPools/{elasticPoolName}/databases/{databaseName}
  tags: Elastic Pools Database
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolnamedatabasesdatabasename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolnamedatabasesdatabasename-get-openapi.md
- name: Azure SQL Database API Elastic Pools List Databases
  x-api-slug: azure-sql-database-api
  description: Returns a list of databases in an elastic pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/elasticPools/{elasticPoolName}/databases
  tags: Elastic Pools Databases
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolnamedatabases-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolnamedatabases-get-openapi.md
- name: Azure SQL Database API Recommended Elastic Pools Get
  x-api-slug: azure-sql-database-api
  description: Gets a recommented elastic pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools/{recommendedElasticPoolName}
  tags: Recommended Elastic Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolname-get-openapi.md
- name: Azure SQL Database API Recommended Elastic Pools Get Databases
  x-api-slug: azure-sql-database-api
  description: Gets a database inside of a recommented elastic pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools/{recommendedElasticPoolName}/databases/{databaseName}
  tags: Recommended Elastic Pools Databases
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamedatabasesdatabasename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamedatabasesdatabasename-get-openapi.md
- name: Azure SQL Database API Recommended Elastic Pools List By Server
  x-api-slug: azure-sql-database-api
  description: Returns recommended elastic pools.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools
  tags: Recommended Elastic Pools Server
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernamerecommendedelasticpools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernamerecommendedelasticpools-get-openapi.md
- name: Azure SQL Database API Recommended Elastic Pools List Databases
  x-api-slug: azure-sql-database-api
  description: Returns a list of databases inside a recommented elastic pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools/{recommendedElasticPoolName}/databases
  tags: Recommended Elastic Pools Databases
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamedatabases-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamedatabases-get-openapi.md
- name: Azure SQL Database API Recommended Elastic Pools List Metrics
  x-api-slug: azure-sql-database-api
  description: Returns a recommented elastic pool metrics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools/{recommendedElasticPoolName}/metrics
  tags: Recommended Elastic Pools Metrics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamemetrics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamemetrics-get-openapi.md
- name: Azure SQL Database API
  x-api-slug: azure-sql-database-api
  description: Make building and maintaining applications easier and more productive.
    With built-in intelligence that learns app patterns and adapts to maximize performance,
    reliability, and data protection, SQL Database is a cloud database built for developers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com//
  tags: Pools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/azure-sql-database/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/sql-database/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/sql-database/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/sql-database/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/sql-database/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---