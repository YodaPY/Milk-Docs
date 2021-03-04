# Roles

Levelling roles reward your members for being active in your server with roles that have nice looking colors or just more permissions. Want to set up your own? _No problem_.

### Adding a levelling role

Let's get started with adding our levelling role. The user should receive the role `Blue` at `1000` XP.

```text
milk.config levelling roles add 1000 Blue
```

There we go, our first levelling role! For the sake of safety we are going to check if Milk _really_ added our role once again.

```text
milk.config levelling roles list
```

You should see your role in the embed's description that Milk outputs.

### Role-Up Messages

Role-Up messages are like Level-Up messages, except they are sent when you get a levelling role rather than when you level up.

Milk supports a bunch of variables for Role-Up messages:

| Variable | Description |
| :---: | :---: |
| {role} | The name of the achieved levelling role |
| {role\_id} | The ID of the achieved levelling role |
| {user} | The username of the user who role-up'd |
| {user\_id} | The ID of the user who role-up'd |
| {guild} | The name of the guild the role-up happened in |
| {guild\_id} | The ID of the guild the role-up happened in |

## Commands

{% hint style="info" %}
**All commands below require you to have the `MANAGE ROLES` permission \(except `list`\).**
{% endhint %}

| Name | Description | Aliases | Example |
| :---: | :---: | :---: | :---: |
| add | Add a levelling role | None | `milk.config levelling roles add 1000 Blue` |
| remove | Remove a levelling role | None | `milk.config levelling roles remove Blue` |
| list | All levelling roles set | list | `milk.config levelling roles list` |



