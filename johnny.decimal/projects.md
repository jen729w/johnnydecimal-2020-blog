# Multiple projects

{% hint style="info" %}
This page will definitely become a formal part of the JD system when I've thought about it some more. This is probably the thing I get asked about the most.
{% endhint %}

When I [started this system](the-history-of-j-d.md) I was running a specific project, and I didn't really consider the need for multiple projects _on the same computer_.

If two projects never meet, there's no issue. I have a project at work with one set of numbers and my system at home with another, totally unrelated, set of numbers. No problem at all – it's like I'm two people leading separate lives.

Fast-forward a decade and I find myself needing more. I still have my personal system, but I work freelance and the projects I run for other people must exist alongside my personal stuff, and each other.

{% hint style="info" %}
If you haven't already, familiarise yourself with the [AC.ID notation](acid-notation.md).
{% endhint %}

## Adding projects to the system

I've thought about this for a few years, and have been using the system I'll describe here since 2018. So far it's working well for me.

### Goals

The extended system must retain the advantages of the original Johnny.Decimal system.

1. Each item must have a unique identifier.
2. You must be able to search \(your notes, your file system\) for this identifier.
3. The identifier should be short and preferably memorable.

### Letters: no good

I tried systems using letters rather than numbers and they didn't work. My initial attempt looked something like this:

* `HME.AC.ID` = home system
* `DVO.AC.ID` = the DevOps project at work
* `ETC.AC.ID` = etc. for more projects

### The answer: more numbers

Here were my goals and constraints when introducing new numbers:

1. It must not confuse the system.
2. It must allow for a sufficient number of additional projects.
3. It must allow the user to organise those projects in some way \(i.e. like you organise categories in to areas\).
4. It must be optional and easy to add/remove/change.

The solution is to **add a three-number project code to the start of your numbers**, e.g. `000.AC.ID`. In the abstract I'll refer to this as `PRJ.AC.ID`.

### 1. It must not confuse the system

Three numbers is not two numbers. I think if I'd gone with `PR.AC.ID`, e.g. `10.12.53`, that would have been a bit much on the brain. The only thing in the JD system with three numbers is a project code.

### 2. It must allow for a sufficient number of additional projects

One thousand projects should be enough for anyone. I'd love to know what you're doing if you need more than a thousand projects.

### 3. It must allow the user to organise those projects in some way

Here's what I do at home.

```text
100-199 Personal
  101 Personal system

200-299 ACME Corp   // The name of the company I'm contracting to
  200 ACME, general & templates
  201 Project 1
  202 Project 2
  ...
  211 Project 11    // Yeah, I'm really up to 11
```

### 4. It must be optional and easy to add/remove/change

I'll discuss this in more detail later.

