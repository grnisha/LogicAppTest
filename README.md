Logic app test

create ad app

 az ad sp create-for-rbac --name "myApp" --role contributor \
                            --scopes /subscriptions/{subscription-id}/resourceGroups/{resource-group} \
                            --sdk-auth
save output to AZURE_CREDENTIALS
also populate AZURE_SUB, RG_CON & RG_LA secrets