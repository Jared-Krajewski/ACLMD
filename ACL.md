# How Access Control Lists (ACL) work for Solid Pods

Access control is used in managing Solid Pods as it allows users to control who can access and modify their data. Solid Pods use ACLs to manage access to resources stored within them.

## What are Access Control Lists (ACLs)?

ACLs are a way of specifying who can access a resource and what actions they can perform on that resource. In Solid Pods, ACLs are represented as files that contain a list of agents and their corresponding permissions for a specific resource. They can be located at https://ACCOUNTNAME.PROVIDERURL/DIRECTORY/.acl -- replacing ACCOUNTNAME with your account name, PROVIDERURL with the host url and DIRECTORY with the directory the ACL is responsible for.
Example: https://testorg.solidcommunity.net/inbox/.acl

## Understanding ACL Modes

Solid Pods support three different ACL modes that allow users to control the level of access granted to different agents. These modes include:

1.  `Read`: Allows agents to read the contents of a resource.
2.  `Write`: Allows agents to modify the contents of a resource.
3.  `Append`: Allows agents to add new data to a resource without modifying existing data.

## Specifying Access Control

Access control for a resource in a Solid Pod is specified using an `.acl` file that is located in the same folder as the resource. The `.acl` file contains a list of agents and their corresponding permissions for the resource. The following is an example of an `.acl` file:

![Inbox ACL example](Screenshot1.png "inbox ACL example")
<img src = "Screenshot1.png" >
![img](https://drive.google.com/file/d/1_e2Na4iokR9R1WAswYvcnNyYo9fByDmN/view?usp=share_link)

## Conclusion

Access Control Lists (ACLs) are an important aspect of managing access to resources in Solid Pods. ACLs allow users to specify who can access their data and what actions they can perform on that data. By understanding how ACLs work in Solid Pods, users can ensure that their data is kept safe and secure.
