<!--
SPDX-FileCopyrightText: 2025 The envu-cli contributors (https://github.com/env-for-you/envu-cli/blob/master/CONTRIBUTORS.md)

SPDX-License-Identifier: MIT
-->

# Contributing

Thank you for your interest in contributing to `envu-cli`! We welcome contributions from the community.

## Commit Guidelines

We use atomic commits and follow the [seven rules for great commit messages](https://chris.beams.io/posts/git-commit/) to maintain a clean and useful git history:

1. **Separate subject from body with a blank line**
   - Use a blank line between the subject and the body to improve readability

2. **Limit the subject line to 50 characters**
   - Keep subjects concise and scannable
   - If you need more space, use the body

3. **Capitalize the subject line**
   - Begin the subject line with a capital letter

4. **Do not end the subject line with a period**
   - Trailing punctuation is unnecessary in subject lines

5. **Use the imperative mood in the subject line**
   - Write as if giving a command: "Fix bug" not "Fixed bug" or "Fixes bug"
   - A good subject line should complete: "If applied, this commit will..."

6. **Wrap the body at 72 characters**
   - Git never wraps text automatically, so wrap it manually for readability

7. **Use the body to explain what and why vs. how**
   - Focus on the reasons for the change and what changed
   - The code shows how; the commit message explains context

For example (taken and slightly altered from the link above):

```
Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequences of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: #123
See also: #456, #789
Signed-off-by: Your Name <your.email@example.com>
```

## License Headers (REUSE)

This project follows the [REUSE Specification](https://reuse.software/) for copyright and licensing information. All files must include REUSE-compliant headers.

Add these lines at the top of new files (using appropriate comment syntax):

```
SPDX-FileCopyrightText: YYYY Your name <your.email@example.org>

SPDX-License-Identifier: MIT
```

For files that don't support comments (images, binaries, etc.), create a corresponding `.license` file with the same content.

You can also use the [REUSE tool](https://codeberg.org/fsfe/reuse-tool) to add headers automatically:

```bash
reuse annotate --copyright="Your name <your.email@example.org>" --license="MIT" <file>
```

## Developer Certificate of Origin (DCO)

By contributing to `envu-cli`, you certify that you have the right to submit your contribution under the project's license. All commits must be signed off to acknowledge the [Developer Certificate of Origin](https://developercertificate.org/):

```
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

### Signing Off Commits

To sign off your commits, use the `-s` flag with `git commit`:

```bash
git commit -s -m "Your commit message"
```

This will add a `Signed-off-by` trailer to your commit message:

```
[Your commit message]

Signed-off-by: Your Name <your.email@example.com>
```

Alternatively, you can manually add the `Signed-off-by` trailer line to your commit message.

**Important**: Commits without a `Signed-off-by` trailer cannot be accepted.

## Adding Yourself to Contributors (Optional)

If you'd like to be recognized for your contributions, you're welcome to add yourself to the [CONTRIBUTORS.md](CONTRIBUTORS.md) file. This is completely optional and not required for your contributions to be accepted.

To add yourself, include an entry in alphabetical order by first name. You can include just your name, or optionally add your email address and/or GitHub username.

## License

This project is licensed under the MIT License. By contributing to this project, you agree that your contributions will be licensed under the same MIT License that covers the project. See the [LICENSE](LICENSE) file for the full license text.
