# [Command] _neon postgres branch delete_

Delete an existing branch within a Neon Postgres database.

## Versions

### [2025-03-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL25lb24ucG9zdGdyZXMvb3JnYW5pemF0aW9ucy97fS9wcm9qZWN0cy97fS9icmFuY2hlcy97fQ==/2025-03-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/neon.postgres/organizations/{}/projects/{}/branches/{} 2025-03-01 -->

#### examples

- Delete Branch
    ```bash
        neon postgres branch delete --subscription 38a546de-5736-48e8-a69a-5cc636794112 --resource-group rgneon --organization-name org-cli-test --project-id old-frost-16758796 --branch-id br-spring-field-a8vje3tr
    ```
