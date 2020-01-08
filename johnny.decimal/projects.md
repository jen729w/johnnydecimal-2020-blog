# Multiple projects, or multiple clients

{% hint style="info" %}
This page will definitely become a formal part of the JD system when I've thought about it some more. This is probably the thing I get asked about the most.
{% endhint %}

When I [started this system](the-history-of-j-d.md) I was running a specific project, and I didn't really consider the need for multiple projects _on the same computer_.

If two projects never meet, there's no issue. I have a project at work with one set of numbers and my system at home with another, totally unrelated, set of numbers. No problem at all – it's like I'm two people leading separate lives.

Fast-forward a decade and I find myself needing more. I still have my personal system, but I work as a contractor and the projects I run for other people must exist alongside my personal stuff, and each other.

{% hint style="info" %}
If you haven't already, familiarise yourself with the [AC.ID notation](acid-notation.md).
{% endhint %}

---

# Projects vs. Clients

There are two distinct kinds of system that seem to be required.

1. You manage multiple totally separate projects. This is what I do (I'm an IT project manager/architect by day). Many of these projects are for the same client but they're quite distinct, different things. I'm going to call **type 1 contractor** (or **employee**).
2. You have one main business, and in that business you manage multiple clients, and they may have multiple jobs each. **Type 2** is your typical **freelancer**, graphic designer, writer, photographer.

I'm still trying to fix this problem. I fall in to category 1. above, and my partner is 2. I just drew this on [my desk](../random/my-desk.md).

![](../.gitbook/assets/butchers-sketch-project-types.jpg)

On the left we have type 1, **contractor**. The stick-figures are clients, and the lines out are projects. That's how I tend to work. The top figure is me, personally. Actually I only have one line out and it's my `101 Personal` project. The bottom figure is the company I'm working for, and the lines are the many projects.

On the right we have type 2, **freelancer**. There are many clients, and each of them only has a job or two.

The system I describe below works really well for a **type 1 contractor**. It needs some tweaking for a **type 2 freelancer**, which I'll write up over the next few days.

# Adding projects to the system

I've thought about this for a few years, and have been using the system I'll describe here since 2018. So far it's working well for me.

## Goals

The extended system must retain the advantages of the original Johnny.Decimal system.

1. Each item must have a unique identifier.
2. You must be able to search \(your notes, your file system\) for this identifier.
3. The identifier should be short and preferably memorable.

## Letters: no good

I tried systems using letters rather than numbers and they didn't work. My initial attempt looked something like this:

- `HME.AC.ID` = home system
- `DVO.AC.ID` = the DevOps project at work
- `ETC.AC.ID` = etc. for more projects

Now you just have to remember what those letters mean, and they don't add any semantic value to your system.

## The answer: more numbers

Here were my goals and constraints when introducing new numbers:

1. It must not confuse the system.
2. It must allow for a sufficient number of additional projects.
3. It must allow the user to organise those projects in some way \(i.e. like you organise categories in to areas\).
4. It must be optional and easy to add/remove/change.

The solution is to **add a three-number project code to the start of your numbers**, e.g. `000.AC.ID`. In the abstract I'll refer to this as `PRO.AC.ID`. 😃

### 1. It must not confuse the system

Three numbers is not two numbers. I think if I'd gone with `PR.AC.ID`, e.g. `10.12.53`, that would have been a bit much on the brain. The only thing in the JD system with three numbers is a project code.

### 2. It must allow for a sufficient number of additional projects

One thousand projects should be enough for anyone. I'd love to know what you're doing if you need more than a thousand projects.

### 3. It must allow the user to organise those projects in some way

Here's what my current system looks like.

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

You have flexibility here to group by tens, or by hundreds. Up to you.

### 4. It must be optional and easy to add/remove/change

TBC, need to go to bed. 💤
