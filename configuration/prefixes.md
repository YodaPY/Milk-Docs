# Prefixes

Milk also allows the use of multiple prefixes or should I say: **UNLIMITED** multiple prefixes

{% hint style="warning" %}
**Prefixes can not be longer than 10 characters.**
{% endhint %}

Run the following command to add the prefix `m!`.

```text
milk.configure prefixes add m!
```

You successfully added your first prefix!

To be on the safe side, let's check if Milk added the prefix.

```text
milk.configure prefixes list
```

You should now see an output similar to: List of valid prefixes: `milk.`, `m!`

{% hint style="warning" %}
**The default `milk.` prefix will be a valid prefix until you remove it manually.**
{% endhint %}

## Commands

{% hint style="info" %}
**All commands below require you to have the `MANAGE SERVER` permission \(except `list`\).**
{% endhint %}

| Name | Description | Aliases | Example |
| :---: | :---: | :---: | :---: |
| add | Add a prefix | None | `milk.config prefixes add m!` |
| remove | Remove a prefix | None | `milk.config prefixes remove m!` |
| list | All prefixes set | None | `milk.config prefixes list` |

