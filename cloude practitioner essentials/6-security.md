# Shared Responsibility

![Screenshot from 2021-07-03 07-33-51](https://user-images.githubusercontent.com/73107656/124345532-6a1f0e00-dbd1-11eb-9233-d4ffb2452acb.png)

# User Permissions and Access

- **AWS Account Root User** > Owner of account

![Screenshot from 2021-07-03 08-29-41](https://user-images.githubusercontent.com/73107656/124346812-d3eee600-dbd8-11eb-8763-e5510e492e7c.png)

- **IAM** - **Identity and Access Management** > used to manage the permissions of different `Users`, `Groups` and `Roles`. This is done via `IAM Policies`.

**IAM policies** are JSON documents:

![Screenshot from 2021-07-03 08-28-50](https://user-images.githubusercontent.com/73107656/124346792-b752ae00-dbd8-11eb-89f2-318ebedc7921.png)

`Users` can be assigned policies individually or added to a `group`. In this case the policies are assigned to the group and the user inherits that groups policies.

Policies can also be assigned to `Roles` giving a role specific access and permissions. Similar to groups, Users can be assigned to roles and assume the policies associated with that role. Users are not the only `identity` that can be assigned to roles though, roles can be assigned to:

- Users
- AWS Resources
- External Identities
- Applications
- AWS Services
