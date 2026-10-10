# CircuitBase feedback

Public issue tracker for [CircuitBase](https://circuitbase.tech), a reference of board and connector
pinouts, electronic components and schematics, with a browser-based schematic editor.

The site's source code is not in this repository. This repository is for what readers see on the
site: data errors, community confirmations and ideas.

## What you can do here

| I want to… | Use |
|---|---|
| Report a wrong pin, contact, voltage or orientation on a board, connector or component page | [Data error](../../issues/new?template=data-error.yml) |
| Report a mistake in a schematic (part, value, net, connection) | [Schematic error](../../issues/new?template=schematic-error.yml) |
| Confirm that a pinout matches the board or connector in your hands | [Confirm a pinout](../../issues/new?template=confirm-pinout.yml) |
| Confirm that a schematic works as drawn | [Confirm a schematic](../../issues/new?template=confirm-schematic.yml) |
| Suggest a board, part, schematic or feature | [Idea](../../issues/new?template=idea.yml) |

The easiest way is the **Report a problem** or **Confirm** link on the page itself: it opens the
right form with the page already filled in.

## How confirmations work

A confirmation is a report from someone who checked a page against real hardware. It is an extra
trust signal, shown separately from CircuitBase's own source review; it does not publish or approve
anything on its own.

1. You submit the form. Please say which vendor and revision you checked and how you checked it.
2. The maintainer reviews it. Accepted confirmations get the `status:accepted` label.
3. On the next site build, the page shows the number of accepted confirmations, the board
   revisions they cover and the latest date, with a link back to the issues.

If you found a difference instead, the form turns it into an error report.

## Before you post

- Issues are public. Do not post personal data, private photos or anything you cannot share.
- Link your evidence: a datasheet page, a measurement, a photo of the board markings.
- Be specific: page URL, pin or part, what you expected and what you found.

## Licence

Text, data and images you submit here are published under
[CC BY 4.0](LICENSE), the same licence as CircuitBase catalogue data, so they can be used to
correct and improve the site with attribution.

CircuitBase is a solo project by [Serhii Shvab](https://www.linkedin.com/in/serhii-shvab/).
