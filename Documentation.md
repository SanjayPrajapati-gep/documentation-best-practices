# Documentation

## Good Practices

This article ["What nobody tells you about documentation"](https://www.divio.com/blog/documentation/) is a must-read! It separates the documentation into four quadrants, each of which takes a different responsibility:

> - Tutorials
>   - is **learning-oriented**
>   - allows the newcomer to get started
>   - is a lesson
> - How-to guides
>   - is **goal-oriented**
>   - shows how to solve a specific problem
>   - is a series of steps
> - Explanation
>   - is **understanding-oriented**
>   - explains
>   - provides background and context
> - Reference
>   - is **information-oriented**
>   - describes the machinery
>   - is accurate and complete

The great thanks go to [Daniele Procida](https://twitter.com/evildmp) who makes it so clear and concise!

## Current Issues

With the above-mentioned four documentation quadrants, I find many documentations are poor because of the lack in "Explanation": they provide a lot of tutorials and how-to guides but fail to give a conceptual explanation of the product components and how and **especially why** they are put that way.

I **strongly believe** understanding `why`s is crucial to using the product correctly, because those `why`s reflect the problems the product is solving. Not understanding the `why`s may result in using the product in the wrong context to solve the wrong problem.

## Doc Smells

### Reference without Definition

See the section ["Control Machine Requirements"](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#control-machine-requirements) of Ansible's documentation. This section is the first time the term "control machine" is used, but there is no definition or explanation of what a "control machine" is. The reader needs to infer it from the context.

This looks quite like in a program you start to use a variable without defining it. "Hey," you may argue, "the compiler should be smart enough to figure out what that variable means from its context. Any compiler that's unable to do so is dumb."

## Useful Links

- [14 Examples of Documentation Mistakes You Are Making](http://blog.screensteps.com/14-examples-of-bad-documentation)
- [Poor Documentation: Why It Happens and How to Fix It](http://www.fortherecordmag.com/archives/0516p12.shtml)
- [Documentation Bad Habits: Shortcuts in Electronic Records Pose Risk](http://library.ahima.org/doc?oid=81008#.W1uFmnXwbdE)
