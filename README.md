# Kit Tracking

**This repo is still WIP**

This document outlines a proposal for tracking kit logistics for SR2022 and going forward in an open manner.

It will allow us to have a view of what kits are currently in the field, and whether they need returning.

The proposed ticketing-style system would be implemented using [GitHub Issue Templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms) and would replace the current system of spreadsheets.

## Kit Lifecycle Issue (KLI)

When a kit is not with SR, a *Kit Lifecycle* issue is created.

The KLI is a GitHub issue that tracks the status of kit with a given team during a competition year.

The KLI should not contain any information to link it to the team other than the TLA, to minimise data protection risk.

The KLI can be referenced to by other issue types, to link relevant information together.

### Opening a KLI

A KLI should be opened when a kit is issued to a team.

This may occur during kit shipping, or be created by a volunteer at a physical kickstart.

When the KLI is opened, the kit box should be moved to `teams/SR20XX/TLA` in the inventory.

### Closing a KLI

A KLI should be closed when a kit is returned to SR from the team.

This may occur as part of a Kit Return Request, or when handed to a volunteer at the end of the competition.

When the KLI is closed, the kit box should be moved in the inventory to the actual location of the box.

## Other Issue Types

### Kit Shipping Request

This issue is used to track the shipment of a complete kit to a team at the start of a competition.

This issue should be opened when we have received the details required to send a kit to the team.

It should only be closed when the kit has arrived with the team.

### Kit Return Request

This issue is used to track the return of a kit to SR via post.

This issue should be opened when we have agreed with a team to return their kit.

The issue should be closed when the kit has arrived with a volunteer, or in UK-PostBox.

### Replacement Parts Request

This issue is used to track sending a replacement part to a team.

It should be opened when a team needs a replacement part, even if in-person.
This is so that we can track how many spare parts are being issued and where they are being issued.

The issue should be closed when the team has received the replacement part.
