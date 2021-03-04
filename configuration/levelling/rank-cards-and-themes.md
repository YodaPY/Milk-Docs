# Rank Cards & Themes

## Rank Cards

Milk has some really cool looking rank cards to show off your XP to your friends or opponents and they are very customizable as well!

![](../../.gitbook/assets/rank-card.png)

Don't like the colors? Gotchu.

## Themes

Themes are very useful if you don't want to use the default colors and need something more clean or _crazy_ . First of all let's download the example file for making themes:

{% file src="../../.gitbook/assets/example.json" caption="JSON color map" %}

Now open the file with the text editor of your choice and you should see this:

```javascript
{
    "name": "default",
    "bg": "#262729",
    "pieslice_bg": "#3B3C3E",
    "pieslice": "#D3D3D4",
    "username": "#D3D3D4",
    "discriminator": "#3B3C3E",
    "level_text": "#D3D3D4",
    "level": "#7289DA",
    "xp_text": "#D3D3D4",
    "xp": "#D3D3D4"
}
```

So let's explain what all these keys and values mean based on the rank card above.

First of all, what you see on the left side is called a _key_, what you see on the right side is the key's _value._ We start off by setting the theme's name to `default`. Make sure you put the value of all keys inside two quotation marks also known as a string \(a sequence of characters\).

{% tabs %}
{% tab title="bg" %}
`bg` is short for background and decides about the background color of our rank card.

![](../../.gitbook/assets/theme-background.png)
{% endtab %}

{% tab title="pieslice\_bg" %}
`pieslice_bg` is short for pieslice background and decides about the background color of the pieslice.

![](../../.gitbook/assets/theme-pieslice-background.png)
{% endtab %}

{% tab title="pieslice" %}
The `pieslice` key decides about the color of our pieslice.

![](../../.gitbook/assets/theme-pieslice.png)
{% endtab %}

{% tab title="username" %}
The `username` key decides about the color of the displayed username.

![](../../.gitbook/assets/theme-username.png)
{% endtab %}

{% tab title="discriminator" %}
The `discriminator` key decides about the color of the displayed discriminator.

![](../../.gitbook/assets/theme-discriminator.png)
{% endtab %}

{% tab title="level\_text" %}
The `level_text` key decides about the color of the "Level" text in the rank card.

![](../../.gitbook/assets/theme-level-text.png)
{% endtab %}

{% tab title="level" %}
The `level` key decides about the color of your level in the rank card

![](../../.gitbook/assets/theme-level.png)
{% endtab %}

{% tab title="xp\_text" %}
The `xp_text` key decides about the color of the "XP" text in the rank card.

![](../../.gitbook/assets/theme-xp-text.png)
{% endtab %}

{% tab title="xp" %}
The `xp` key decides about the color of your XP in the rank card.

![](../../.gitbook/assets/theme-xp.png)
{% endtab %}
{% endtabs %}

