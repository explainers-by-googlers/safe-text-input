# Two policy-controlled features for safe user input

This proposal is an early design sketch by the Chrome Autofill team to describe the problem below and solicit
feedback on the proposed solution. It has not been approved to ship in Chrome.

## Overview

We introduce two policy-controlled features for controlling an embedded document's ability to receive text input:

* [`manual-text`](manual-text.md) addresses keyboard input and similar ways of entering text.
* [`autofill`](autofill.md) addresses user agent features that fill one or multiple form control elements on behalf of the user.
