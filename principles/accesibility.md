---
description: Our main goal is to create inclusive experiences across all of our products.
---

# Accesibility

### Color Contrast

![](../.gitbook/assets/contrast.svg)

Some users find it hard to read light gray text on a white background, dark gray text on a black background and white text on a red background.

{% hint style="info" %}
The contrast should be 3.0 or more for 18 px text, or larger.
{% endhint %}

{% hint style="info" %}
The contrast should be 3.0 or more for 14 px bold text, or larger
{% endhint %}

{% hint style="info" %}
The contrast should be 4.5 or more for all other text
{% endhint %}

### Proper tags and elements

As part of our process to achieve a fully accesible product, make sure that implementation is always using standard tags for elements. H1, H2, H3. 

### Provide alternative information

As designers we should be providing aria labels and alt descriptions for new elements that don't have standard attributes.

### Keyboard Navigation

One consideration to make is to always think about how to traverse and interact with your product by using only the keyboard. 

A keyboard user typically uses the Tab key to navigate through interactive elements on a web page—links, buttons, fields for inputting text, etc. When an item has keyboard "focus", it can be activated or manipulated with the keyboard. A sighted keyboard user must be provided with a **visual** indicator of the element that currently has keyboard focus.

| Keyboard Key | Description |
| :--- | :--- |
| `Esc` | Close a modal  \*\* |
| `Alt+/` | Open Hamburger menu |
| `Enter` | Activates primary button |
| `Space` | Actives focused element |
| `Tab` | Traverses through the DOM |

\*\* make sure to brung a confirmation popup before closing.

### Test on a developer instance

See how accessible your application/feature is by trying to complete tasks only using a a keyboard and or screen reader devices

## Accessibility Reference 

{% embed url="https://www.w3.org/TR/WCAG21/" %}




