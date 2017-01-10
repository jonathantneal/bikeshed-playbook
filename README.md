# Bikeshed Playbook

> A new user’s guide to writing bikeshed specifications

Would you like to see a new feature added to CSS? Can you imagine what it does and how it works in your head? This guide is intended to help you capture that idea into a [bikeshed] specification; the best way to communicate a feature to the CSSWG.

### Steps

1. Setup a [bikeshed] project.
    - [Create a new repository](https://github.com/new) for your specification.
    - Create a new local directory for your specification.
        ```sh
        # create the directory
        mkdir my-feature-spec

        # goto the directory
        cd my-feature-spec

        # connect the directory to your specification repository
        git init
        git remote add origin git@github.com:YOUR-GITHUB/FEATURE-REPO.git

        # create the bikeshed and readme files
        touch package.json index.bs README.md
        ```
    - Copy the contents of [package.json](example-spec/package.json), [index.bs](example-spec/index.bs), and [README.md](example-spec/README.md) into your respective files. Update the files to reflect the description of your feature.
- In as few words as possible, describe what your feature does.
    - Write a brief description or advertisement of your feature for social media (roughly 140 characters or less).
    - Write a brief description or advertisement of your feature for posts (70 characters or less)
    - *example*
- In as few words as possible, describe why this feature exists.
    - Outline the problem this feature solves and, if possible, the next best solution without it. This can also be a place to communicate the motivation behind creating the feature.
    - *example*
- As clearly and completely as possible, describe how the feature and all of its parts operate.
    - *describe bikeshed feature markup*
    - *example*
- Share your idea with the world.
    - *create github page*
    - Use your brief descriptions for social media and in blog posts
        + list popular social networks to share ideas
        + list popular developer networks to share ideas
            * https://discourse.wicg.io/
            * http://codepen.io/write/
- Create living demonstations
    + *create postcss plugin*
        * document anything you learn about your feature during this process
    + *create browserified postcss example*
    + *create codepen template using browserified postcss*

[Bikeshed Playbook]: https://github.com/jonathantneal/bikeshed-playbook
[bikeshed]: https://tabatkins.github.io/bikeshed/
