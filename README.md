# Test Connect to Azure Cloud

get secrets credentials by running 

az ad sp create-for-rbac --name "myApp" --role contributor \
                            --scopes /subscriptions/{subscription-id}/resourceGroups/{resource-group} \
                            --sdk-auth


from your terminal. 

and copy this into git repo/secrets/AZURE_CREDENTIALS
