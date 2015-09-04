# Best Practices for Getting a Proposal Through WICG

While these are ordered roughly in descending order from easiest to hardest, you're free to do these in any order (though doing some of the later ones without doing the earlier ones is liable to result in harder, unnecessary work):

## Join the Web Platform Incubator Community Group on W3.org

Going to https://www.w3.org/community/wicg/ and joining the group states that you agree to abide by the [W3C Code of Ethics and Professional Conduct](http://www.w3.org/Consortium/cepc/), and that you release your contributions under the terms of the [W3C’s Community Contributor License Agreement](https://www.w3.org/community/about/agreements/cla/) (the CLA) - without this, key members won’t be able to review or discuss your proposal, since they can't be legally certain that you won't do something like suing the W3C for using your specification without permission.

If you want to see your spec become part of the web, you'll need to sign this stuff first, and joining the WICG group is the simplest way to do that.

## Start a thread on Discourse

This is a great starting point for you to point out any issues you've had and propose something you're thinking of that could solve it. Others will weigh in with their own experiences around this problem, and how it may be solved more easily.

## Create a public GitHub repository (repo)

See [the GitHub documentation on creating a repo](https://help.github.com/articles/create-a-repo/).

The README.md in your repository should tell a visitor to your repo where the different parts of your proposal are located in the repository; specifics about how you're using the various features of GitHub (such as Issues and Pull Requests) should be described in a file called CONTRIBUTING.md.

(You don't necessarily have to use [Markdown](https://help.github.com/articles/github-flavored-markdown/) to format the documents in your repo, but it's generally the [lingua franca](https://en.wikipedia.org/wiki/Lingua_franca) of rich-plaintext on the web nowadays, and using it will generally make it easier for others to contribute to your docs.)

## Write a draft specification

Do your best to explain how it'd work as a determinative series of rules, after it's been workshopped a bit in Discourse the group'll dive in and help you bring it up to snuff for the W3C & co in terms of details and terminology.

## Write an explainer document

It should just explain the technology to other developers in simple terms. I.e., explain why you might want to use this, and how you achieve something. Interested people should "get it" from reading the explainer.

See [the explainer document for the ServiceWorker proposal](https://github.com/slightlyoff/ServiceWorker/blob/master/explainer.md) as an example.

## Write a polyfill and/or patches

If you can write *code* that will show how what you're proposing should work, that is a *significant* help in conveying what you're talking about, and will make it much easier both to write the specification, and to convince browser vendors that it can be done.
