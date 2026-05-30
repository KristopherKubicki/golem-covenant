# Security policy

The Golem Covenant is a draft standard and set of public templates. It does not
run production infrastructure for users, but security review is still welcome.

## What to report

Please report:

- Unsafe default guidance in the spec, schema, or templates.
- Missing revocation, logging, audit, or return-to-dust controls.
- Guidance that could encourage credential exposure, unsafe automation, or
  unbounded agent authority.
- Bugs in the public site or repository configuration that could mislead
  implementers.

## Where to report

For public design or implementation concerns, open an issue:

https://github.com/KristopherKubicki/golem-covenant/issues/new/choose

For broad security or runtime-enforcement discussion, use Discussions:

https://github.com/KristopherKubicki/golem-covenant/discussions

If a report includes a sensitive exploit path, credential, or private system
detail, do not post it publicly. Use GitHub's private vulnerability reporting
for the repository if available, or contact the repository owner directly.

## What to include

- Affected file or URL.
- The unsafe behavior or ambiguous guidance.
- A minimal scenario showing how an agent could misuse it.
- Suggested safer wording, schema constraint, template control, or runtime test.

## Status

This project is v0.1 and seeking security and runtime-enforcement review.
