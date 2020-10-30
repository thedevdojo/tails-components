# Contributing 🙌

Howdy 👋, fellow developer. In this document you'll learn how to contribute to this project 🤓. There are 3 ways you can learn how to contribute to this repo. You can **watch** a quick video or **read** the steps.

# Watch 🍿

Want to watch a video instead? Click the link below to watch a quick **5 min.** video on how to contribute.

[![Submit PR Video](https://cdn.devdojo.com/episode/images/September2020/hacktoberfest-2020.jpg)](https://devdojo.com/episode/hacktoberfest-2020)


# Read 📖

**Create a Component** 🛠️- Visit the [Playground](https://devdojo.com/tailwindcss/playground) to create your TailwindCSS component.

![Create Component GIF](https://cdn.devdojo.com/tails/images/1-create-component-min.gif)

**Fork This Repo** 🍴

![Fork Repo GIF](https://cdn.devdojo.com/tails/images/2-fork-repo-min.gif)

**Download your Forked Repo** 🔻

![Clone Repo GIF](https://cdn.devdojo.com/tails/images/3-clone-min.gif)

**Add your Component** ➕

![New Component GIF](https://cdn.devdojo.com/tails/images/4-new-component-min.gif)

**Push your Changes** 👊

![Push GIF](https://cdn.devdojo.com/tails/images/5-push.gif)

**Create your Pull Request**  🤏

![Create PR GIF](https://cdn.devdojo.com/tails/images/6-open-pr-min.gif)

and then,

![Push GIF](https://cdn.devdojo.com/tails/images/boom.gif)

Congratulations,🎉 you just submitted your PR 🤙


# More Details 📖

## Pull Requests 🤏

### Creating a Pull Request 👨‍💻

If you would like to contribute to this project you can visit the [Playground](https://devdojo.com/tailwindcss/playground) and create your TailwindCSS component. After creating your component in the playground you'll want to clone the repo on your machine, add that component to a new `.html` file, and submit a Pull Request. (this process will be refined in a couple days).

To request us to review code that you create, you will need to create a pull request as described in
 [this tutorial](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github).

### File Location/Types 📁

### [`components`](./components)

All the TailwindCSS Components for the project are stored in `.html` files located within the [`components`](./components) directory.

### [`templates`](./templates)

All the TaildwindCSS Templates for the project are stored in `.html` files located within the [`templates`](./templates) directory.

## Issue Creation 🤨

In the event that you have a issue using the tool or have a suggest for a change but don't want to contribute code,
 we are more than happy to help.
Make sure that when you create your issue, it follows the format for the type of issue you select
 (it has individual templates for each issue type).

Issue template types include the following:
 - Bug Reporting
 - Feature Requests
 - Help Requests

## Style Guide 🎨

### Components 🔧

For components you don't need to add `<html>`, `<head>` or `<body>` elements. We provide that on the back-end.

### Templates

For templates we do not provide any wrapping code like we do for components. As our components though, we do expect them to contain TailwindCSS like our components. Here's a little snippet taken from our current templates.

#### TailwindCSS Link Snippet

```html
<!--
    For more customization options, we would advise
    you to build your TailwindCSS from the source.
    https://tailwindcss.com/docs/installation
-->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/1.9.2/tailwind.min.css">
```

### TailwindCSS

All our components and templates rely on TailwindCSS. Components work of our provided TailwindCSS version. Templates have a hard-coded version included in each template, as shown in [the above snippet](#tailwindcss-link-snippet).

### Editorconfig

Tails has an [`.editorconfig`](./.editorconfig) to ease the building of both components and templates.

For indenting we prefer `space` over `tab`,  4 spaces for `.html` and 2 for other files.

## Naming Conventions 📋

### Components 🔧

When naming your component file, it's best to stick with a descriptive name. Such as for a component with featured content containing a large image, we named the file `feature-content-image.html`.

### Templates

TBD.
