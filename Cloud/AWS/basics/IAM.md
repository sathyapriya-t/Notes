# Identity Access and Management

**IAM: Users and Group:**

1. Identity Access and Management
2. Root account created by default , shouldn’t be shared or used
3. Users are people within our organization and can be grouped
4. Group contains only group not other groups
5. User can be part of multiple groups
6. User don’t need to belong to a group.

example:

| Developers | Operations | Common |  |
| --- | --- | --- | --- |
| sathya | Arun | sathya | Prithvi |
| priya | jeeva | Arun |  |

**IAM permission:**

→ each groups or used can be assigned JSON documents called policies.

→These policies define the permissions of the user

→ In aws, you can apply the least privilege principle: don’t give more permission then the user needs.

![IAM_Permissions.png](https://github.com/sathyapriya-t/Notes/blob/bcd8479add66264ae412f32d80a463d03ca3140b/Cloud/AWS/resources/IAM_Permissions.png)

There are totally 2 account:

→ one used to create account(Root user)

→ one used to created with alias in IAM(IAM user)

→ Always use the IAM user to do hand on(best practice)

https://sathya-aws-developer.signin.aws.amazon.com/console

**IAM Group:**

![IAM_GROUP.png](https://github.com/sathyapriya-t/Notes/blob/bcd8479add66264ae412f32d80a463d03ca3140b/Cloud/AWS/resources/IAM_GROUP.png)

**IAM User:**

![IAM_USER.png](https://github.com/sathyapriya-t/Notes/blob/bcd8479add66264ae412f32d80a463d03ca3140b/Cloud/AWS/resources/IAM_USER.png)

Root IAM Dashboard where user is created :

![ROOT_IAM_DASHBOARD.png](https://github.com/sathyapriya-t/Notes/blob/bcd8479add66264ae412f32d80a463d03ca3140b/Cloud/AWS/resources/ROOT_IAM_DASHBOARD.png)

IAM user created using the root account:

![IAM_USER_ACCOUNT.png](https://github.com/sathyapriya-t/Notes/blob/bcd8479add66264ae412f32d80a463d03ca3140b/Cloud/AWS/resources/IAM_USER_ACCOUNT.png)