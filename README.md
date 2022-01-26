# Alpha Vet International Junior Front End Developer Test

Welcome to the Alpha Vet International junior front end developer test.

This test is designed to be as simple to get up and running. You do not need any server software. You simply drag the html file into a browser and it should open.

It's a single index.html file, with all tools being imported via CDN to avoid any headaches with Node or any other build tools. This should let you focus on the test, rather than setting it up!

## Task

This task is designed to replicate a ticket you may receive in a normal day working at Alpha Vet International.

This test uses a stripped down version of one of our internal tools, which allows veterinary practice owners and managers to observe how many hours of learning a member of their team has done.

You have been asked to build out the user section in the middle of Figma design file (https://www.figma.com/file/bBMZl16EO2lFpaTpK8v0Cy/Paige?node-id=0%3A1).

You do not need to build the header, or footer. These have already been built in a previous project. The scope is just the three users.

You only need to worry about the code inside the comments, and adding any components, methods and such within the Vue app. You shouldn't need to change any data that already exists.

### Design File
You will need to create a Figma account to be able to see the correct sizes, styles (colors, fonts etc), and spacing. Please let me know if you've never used Figma before and I'll jump on a call to quickly demo how to get the information you'll need out of it.

## Tools

### Tailwind CSS

You must use Tailwind CSS for this task. The version of Tailwind CSS used on this project is version 3.

It called in via the CDN, and any sizes and fonts not included by default are already included.

I strongly advise watching this video from the makers of Tailwind. It will give you a crash course into how to use Tailwind. https://www.youtube.com/watch?v=elgqxmdVms8

You can also check out then documentation here: https://tailwindcss.com/

Also, don't forget – there's already examples of Tailwind in the code. This should help you see how it works.

### Vue 3

We've called in Vue 3 in via CDN. This is already configured, and has some examples already in there. Feel free to add new methods, and components as you need them.

Things you'll need are:

* [Methods](https://v3.vuejs.org/guide/data-methods.html#methods)
* [Conditional Rendering](https://v3.vuejs.org/guide/conditional.html)
* [List Rendering](https://v3.vuejs.org/guide/list.html)
* [Components](https://v3.vuejs.org/guide/component-registration.html#component-names)

### SweetAlert2

SweetAlert2 is a JS library for creating modals. We've included it via CDN already. You just need to add it via Vue in a way that you can trigger it when a user clicks the Remove button.

You do not need to make the element you click be removed from the DOM.

https://sweetalert2.github.io/#usage

Use the one with the heading: "A confirm dialog, with a function attached to the "Confirm"-button". You do not need to amend anything in the code example.

You do not need to design anything with it either. Once it fires when a user clicks the button, it should already be styled.

**Note:** I'm aware that when the SweetAlert2 modal opens, it causes the footer to lift off the bottom of the site. This isn't something to worry about in this test. Don't spend any time fixing it.

## Version Control

Please use version control (Git) as you normally would. GitHub, BitBucket, and GitLab are all fine to use. When you create a repo, please invite me via benf@thewebinarvet.com.

Create a branch from the main/master branch, and make changes inside it. When you are ready for it to be reviews, set the pull request to me as the reviewer.

## Don't forget!

The test isn't the output; it's seeing how you approach problems, like how you achieve a design, how you think about reducing the amount of code you write, and how to you get to grips with tools you've never used before.

You'll be asked about these things in your code review interview.

**Please remember.** If you get stuck with anything, please contact me and I'll jump on a call with you. We're testing how we'd work together, so jumping on a call is perfectly fine and actually encouraged if you get stuck!