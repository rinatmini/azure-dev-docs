#### [Windows (PS)](#tab/windows)

```azurecli
# Change these values to the ones used to create the App Service.
$RESOURCE_GROUP_NAME='msdocs-python-webapp-quickstart'
$APP_SERVICE_NAME='msdocs-python-webapp-quickstart-123'

az webapp deployment source config-local-git `
    --name $APP_SERVICE_NAME `
    --resource-group $RESOURCE_GROUP_NAME `
    --output tsv
```

#### [macOS/Linux (Bash)](#tab/mac-linux)

```azurecli
# Change these values to the ones used to create the App Service.
RESOURCE_GROUP_NAME='msdocs-python-webapp-quickstart'
APP_SERVICE_NAME='msdocs-python-webapp-quickstart-123'

az webapp deployment source config-local-git \
    --name $APP_SERVICE_NAME \
    --resource-group $RESOURCE_GROUP_NAME \
    --output tsv
```

---