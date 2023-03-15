# [Command] _devcenter admin devcenter create_

Create a dev center

## Versions

### [2022-11-11-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kZXZjZW50ZXIvZGV2Y2VudGVycy97fQ==/2022-11-11-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.devcenter/devcenters/{} 2022-11-11-preview -->

#### examples

- Create
    ```bash
        devcenter admin devcenter create --location "eastus" --tags CostCode="12345" --name "Contoso" --resource-group "rg1"
        devcenter admin devcenter create --identity-type "UserAssigned" --user-assigned-identities "{\\"/subscriptions/00000000-0000-0000-0000-000000000000/resourcegroups/identityGroup/providers/Microsoft.ManagedIdentity/userAssignedIdentities/testidentity1\\":{}}" --location "eastus" --tags CostCode="12345" --name "Contoso" --resource-group "rg1"
    ```