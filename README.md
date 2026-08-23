# Day Weave

**Prioritize What Matters**

Day Weave is a private Apple-platform productivity app designed to help individuals and households decide what actually deserves attention today.

Instead of turning every open task into another source of pressure, Day Weave focuses on three questions:

1. What matters most today?
2. Who should handle it?
3. What can safely wait?

## Core Experience

### My Day

A personalized view of the tasks that deserve your attention now.

Day Weave considers structured context such as:

- Due dates
- Scheduled dates
- Responsibility
- Estimated effort
- Personal priorities
- Household assignments
- Dependencies
- Deferral history

### Not Today

Not every task needs to become urgent.

Not Today identifies lower-priority work that can safely wait, helping reduce noise without losing track of unfinished responsibilities.

### Why This Matters

Priority recommendations should be understandable.

Day Weave exposes the structured reasons behind a recommendation so users can see why one task outranks another.

### Our Day

Households can coordinate shared responsibilities without forcing every member to prioritize things the same way.

A task may be Priority 1 to one member, Priority 3 to another, and resolve to a different household priority based on context.

The household priority engine considers more than simple arithmetic averaging.

## Delegation

Day Weave Unlimited supports structured household delegation.

Shared tasks may be:

- Assigned
- Accepted
- Declined
- Reassigned
- Completed

Assignment is not the same as acceptance.

## Personal and Household Privacy

Day Weave separates personal data from shared household data.

Joining a household does not automatically expose:

- Personal tasks
- Private notes
- Personal priority history
- Private recommendation feedback

Only information intentionally placed into the household collaboration layer is shared with other household members.

## Built-In Task Calendar

Day Weave includes a lightweight task calendar with day, week, and month views.

It is intended to organize task due dates and scheduled work without trying to replace Apple Calendar.

Where appropriate, users may choose **Add to Apple Calendar** for individual tasks.

## Apple Intelligence

On supported devices, Day Weave may use Apple's Foundation Models framework to enhance natural-language task interpretation, context extraction, recommendation explanations, and priority-conflict summaries.

The core priority system remains deterministic.

Day Weave does not require a third-party AI API or paid AI credits for its core functionality.

If Apple Intelligence is unavailable, the priority engine continues to function.

## iCloud and CloudKit

Day Weave uses SwiftData for local persistence and Apple's CloudKit for supported synchronization and household sharing.

The architecture is local-first:

- Immediate app behavior uses local persistence.
- Cloud synchronization occurs separately.
- Personal and shared household records remain distinct.

## Business Model

### Free

The free tier is a complete personal prioritization experience.

It includes:

- Unlimited personal tasks
- Unlimited shared household tasks
- Personal priority engine
- My Day
- Not Today
- Why This Matters
- Built-in task calendar
- Household creation and joining
- Shared task creation, viewing, and completion
- Optional Apple Calendar export

### Day Weave Unlimited

Day Weave Unlimited is planned as a one-time non-consumable purchase.

It unlocks:

- Independent household priority perspectives
- Household priority resolution
- Priority mismatch detection
- Delegation
- Assignment acceptance and decline
- Reassignment
- Personalized household task ranking
- Our Day collaborative prioritization

No subscription is required.

Where supported by Apple, the Unlimited purchase may support Family Sharing.

> **Personal productivity is free. Household alignment is premium.**

## Privacy

See [Privacy](https://beardednerd3d.github.io/Day-Weave/PRIVACY).

## Support

See [Support](https://beardednerd3d.github.io/Day-Weave/SUPPORT).

## Notices

See [Notice](https://beardednerd3d.github.io/Day-Weave/NOTICE).

## Platform

Day Weave is being designed for:

- iPhone
- iPad

The project uses Apple-native technologies including:

- Swift
- SwiftUI
- SwiftData
- CloudKit
- StoreKit
- EventKit / EventKitUI
- Foundation Models

## Project Status

Day Weave is currently in development.

Features described in this repository may change before public release if required for reliability, privacy, App Store compliance, or platform compatibility.
