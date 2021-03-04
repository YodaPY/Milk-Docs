# XP

When it comes to making a levelling system, having a non-customizable XP rate is boring. Does it take years or does it take just a few messages to get to Level 10? Luckily, that's not the case here. But before we get into the commands, let's get an understanding of how the XP system works.

### So, how does it work?

Milk distinguishes between Global XP and Server XP. If you ever ran `milk.rank`, it would ask for a scope, same counts for `milk.levelling leaderboard`. You might ask yourself: Why is that? Why wouldn't it default to server? The answer is: As an user, you wouldn't know if Milk is showcasing the Server or Global XP which can lead to a result you think you want but really isn't what you want.

The default XP rate is a random value between 10 and 30 with a cooldown of 1 minute \(means, when you get your XP, you're not able to receive XP for another minute until the lock is over, to prevent people from spamming\).

### What you have been waiting for

How are we going to change the XP rate now? Surprise, surprise: Another command.

In the following example we are going to use the value 100 as our XP rate. You will notice that levelling up becomes faster than ever.

```text
milk.config levelling xp set 100
```

We did it! We now have our own _custom_ XP rate.

I would strongly recommend taking a look at `milk.config levelling xp info` to see when at which XP the user is going to level up.

## Commands

| Name | Description | Aliases | Example | Permission |
| :---: | :---: | :---: | :---: | :--- |
| add | Add Server XP to a member  | None | `milk.config levelling xp add 500 Yoda#0660` | `MANAGE SERVER` |
| set | Set a custom XP rate | None | `milk.config levelling xp set 100` | `MANAGE SERVER` |
| reset | Reset the XP rate to the default | None | `milk.config levelling xp reset` | `MANAGE SERVER` |
| info | XP needed to level up for 100 levels | information, list | `milk.config levelling xp info` | None |



