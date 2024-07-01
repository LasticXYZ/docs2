---
description: Let's have a look into how it is possible to modify the core.
---

# 🪓 Modifying the Core

{% hint style="info" %}
Any modifications that you will do to a Core will prevent you to renew this Core in the future!
{% endhint %}

### Splitting a Core

As we before mentioned before when you buy the core it will last you for a whole month. But what if you need it only for a week? And the rest you want to offer on the market. You can do that with by splitting the core:

<figure><img src="../.gitbook/assets/Screenshot 2024-07-01 at 18.39.31.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2024-07-01 at 18.38.19.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
In Polkadot terminology you will hear this term as partitioning
{% endhint %}

### Changing the Core's Frequency

Did you know you can tweak your core's frequency with a technique called Interlacing?&#x20;

Here's a simple breakdown: Think of the blockchain as a giant computer. Buying a core is like getting a processor in this vast network. What's a processor's superpower? Parallel computing! How does a processor handle tasks like moving the mouse and opening a new tab simultaneously? It runs both tasks so fast on the same processor that you don't even notice. Applying the same concept, how can we manage multiple parachains on the same core? Polkadot introduces Interlacing, a feature that adjusts your core's frequency within 80 blocks (one timeslice). The core division is tracked using a variable called Mask, an 80-bit bitmap. Ever wondered what a Mask of 0xffffffffffffffffffff indicates? It means your core hasn't been interlaced yet And guess what? We can even shape our core interlacing like a heart!&#x20;



<figure><img src="../.gitbook/assets/Screenshot 2024-07-01 at 18.34.45.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2024-07-01 at 18.35.04.png" alt=""><figcaption></figcaption></figure>
