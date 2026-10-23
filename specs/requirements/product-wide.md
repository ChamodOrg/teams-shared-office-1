# Product-wide

Rules that apply to more than one feature.

## Requirements

- P1 Every user signs in through company SSO; bookings are attributed to the signed-in employee. \[org default\] Applies to: all.
- P2 A room is never booked for two overlapping time slots; a clashing booking is refused. Applies to: F3.
- P3 A booking's attendee count may not exceed the room's capacity. Applies to: F2, F3.

## Decisions

- The product is standalone: no integration with an external calendar or booking system.
- Capacity is enforced against the number of invitees, not merely shown.