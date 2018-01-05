# Glossary	


### Organization
The business using the Layer XDK within their application or website.

### User
A `user` is any person who is able to sign into the application.

- **Agent:** This is a stateful term to describe any `user` who is responding to a `customer`.


### Customer
A `customer` is any person engaging with an agent via Layer from the `organization's` application or website.

### Permissions
`Users` possess one of several permissions levels within the application.

- **Read-only:** unable to respond to tickets
- **User:** user assigned to a team and able to respond to tickets
- **Admin:** manage teams, manage queues, system level settings and able to respond to tickets

### Team
A team is a group of `users` that can be assigned to a `queue`.

### Team Roles
Within a team, `users` are given discreet roles with additional privileges.

- **Team member:** Any `user` that belongs to a given team.
- **Team lead:** Can access the team lead dashboard, view all team conversations, and able to respond to all team conversations, manage their team's assignment limit, and view their team member list.

### Assignment limit
The `assignment limit` is a value specifying the number of concurrent `conversations` the system should automatically designate to a given user. This value can be set globally for the `organization`, for a `team`, or for an individual `user`.

### Conversation
A conversation is a set of `messages` being sent between an `agent` and a `customer`.

- **ID:** 
- **Status:** A `conversation` has a status associated with it.
	- **Open:** A new, unassigned conversation.
	- 	**Assigned:** A `conversation` that has been designated to a specific `user` to address. This is handled either automatically via a `queue` or manually by a `team lead`.
	- **Closed:** After a `user` has has completed the conversation, either temporarily or permanently.  
- **Participants:** A `conversation` contains multiple `participants`
	- `Agents`
	- `Customers`
- **Messages:**  Discrete text or rich media being sent between the `partipants`. 

### Queues 
A `queue` routes `open conversations` to specific `teams`.

### Inbox
The `inbox` is where a `user` is able to see and participate in any `conversations` assigned to them.

