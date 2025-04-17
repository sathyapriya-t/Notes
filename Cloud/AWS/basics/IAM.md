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

![image.png](attachment:c41f0d52-a0fa-4a13-ae0a-878979350b7c:image.png)

There are totally 2 account:

→ one used to create account(Root user)

→ one used to created with alias in IAM(IAM user)

→ Always use the IAM user to do hand on(best practice)

https://sathya-aws-developer.signin.aws.amazon.com/console

**IAM Group:**

![image.png](attachment:68627f41-d15a-4ffc-add2-cae2e256ac3e:image.png)

**IAM User:**

![image.png](attachment:644677d2-0f75-4af7-80f3-5cd4dec9b0e9:image.png)

Root IAM Dashboard where user is created :

![image.png](attachment:fa447d44-870a-4663-9750-bff728b100c8:image.png)

IAM user created using the root account:

![image.png](attachment:fa09f19e-64c9-4071-9e94-2d8886e839ec:image.png)