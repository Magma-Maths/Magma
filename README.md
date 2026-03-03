# Magma Issue Tracker

The official issue tracker for the [Magma Computational Algebra System](https://magma.maths.usyd.edu.au/).

**Note: This repository is primarily for issue tracking and feature requests.**

## Reporting Issues

We really appreciate bug reports and feature requests. Bugs exist because we don't know they're there, and we depend on reports from the Magma community to find and fix them. We promise that any problems you submit will not be ignored.

If you prefer not to use GitHub, or have privacy concerns about sharing code publicly, you can report bugs by email at [magma-bugs@maths.usyd.edu.au](mailto:magma-bugs@maths.usyd.edu.au).

### Before You File an Issue

1. **[Search existing issues](https://github.com/Magma-Maths/Magma/issues?q=is%3Aissue)** to check if your problem has already been reported.
2. **Verify on the latest version**: confirm the issue still occurs on the most recent [patch release](https://magma.maths.usyd.edu.au/magma/download/). You can use the [online calculator](https://magma.maths.usyd.edu.au/calc/) to quickly check.
3. **Check the [Magma Handbook](https://magma.maths.usyd.edu.au/magma/handbook/)** to make sure the behaviour isn't documented or expected.

### Providing a Good Bug Report

When reporting a bug, please provide a **minimal reproducible example**: the shortest possible Magma code that triggers the issue.
- **Tip:** You can recover your full session by typing `%P` on the Magma command line.

## Feature Requests

We welcome suggestions for new functionality or improvements to existing algorithms. When requesting a feature, please provide a clear description and, if possible, a motivating use case or references to relevant mathematical literature.

## Installation and Licensing

For **installation, registration, or licensing** issues, please email the Magma Group directly at [magma@maths.usyd.edu.au](mailto:magma@maths.usyd.edu.au) instead of opening an issue here.

## Internal Errors

An internal error produces output like:

```text
Internal Error
Machine type: intel64-osx
Initial seed: 1431482434
Time to this point: 1.36
Memory usage: 23.07MB
A brief description of the error
```

This is a defensive check: Magma regularly asserts that its internal state is consistent, and raises an internal error when something is unexpected. These are often caused by an incorrect assumption or oversight on our part and, once reported, can usually be fixed in time for the next patch release. **Please report all internal errors.**

## Useful Links

- [Magma Home Page](https://magma.maths.usyd.edu.au/)
- [Magma Handbook](https://magma.maths.usyd.edu.au/magma/handbook/)
- [Magma Calculator (Online)](https://magma.maths.usyd.edu.au/calc/)
- [Downloads & Patch Releases](https://magma.maths.usyd.edu.au/magma/download/)
- [Release Notes](https://magma.maths.usyd.edu.au/magma/releasenotes/)
- Email: [magma-bugs@maths.usyd.edu.au](mailto:magma-bugs@maths.usyd.edu.au)
