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

## Command

{% hint style="info" %}
**All commands below need to be invoked with the `config levelling roles` and require you to have the `MANAGE ROLES` permission \(except `list`\).**
{% endhint %}

| Name | Description | Aliases | Cooldown | Example |
| :--- | :--- | :--- | :--- | :--- |
| add | Add a levelling role | None | None | `milk.config levelling roles add 1000 Blue` |
| remove | Remove a levelling role | None | None | `milk.config levelling roles remove Blue` |
| list | All levelling roles set | list | None | `milk.config levelling roles list` |



