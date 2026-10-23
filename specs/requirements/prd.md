# Meeting room booking

## Problem Statement

Teams in a shared office compete for the same handful of meeting rooms. Without one place to see what is free and to claim it, people double-book, turn up to an occupied room, or book a room too small for the group they invited. The wall calendar, chat messages and spreadsheets used today cannot refuse a clash, so it is discovered in the corridor.

## Solution

One place where employees see which meeting rooms are free, claim one for a time slot, and are stopped from booking a room that is already taken or too small for their group.

## Actors

- Employee: signs in, searches for free rooms, books, changes and cancels their own bookings, and sees the room schedule.
- Office admin: keeps the room directory (rooms, capacity, equipment) up to date.

## Features

- F1 [Room directory](features/F1-room-directory.md)
- F2 [Find a free room](features/F2-find-a-free-room.md)
- F3 [Book a room](features/F3-book-a-room.md)
- F4 [Room schedule](features/F4-room-schedule.md)
- F5 [Reminders and notifications](features/F5-reminders-and-notifications.md)

## Product-wide

See [Product-wide](product-wide.md).

## Out of Scope

- Integration with an external calendar or booking system; the product is standalone.

