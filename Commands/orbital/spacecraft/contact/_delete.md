# [Command] _orbital spacecraft contact delete_

Delete a specified contact.

## Versions

### [2022-03-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5vcmJpdGFsL3NwYWNlY3JhZnRzL3t9L2NvbnRhY3RzL3t9/2022-03-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.orbital/spacecrafts/{}/contacts/{} 2022-03-01 -->

#### examples

- Delete Contact
    ```bash
        orbital spacecraft contact delete -g <resource-group> --spacecraft-name <spacecraft-name> --name <contact-name>
    ```
