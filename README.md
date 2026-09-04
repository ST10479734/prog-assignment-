# prog-assignment-
RaceDay bridges the gap between event organizers and participants across South Africa. It replaces manual paper registrations and spreadsheet tracking with an automated, RESTful platform that handles user authentication, event and route management, registrations, payments, and race results.

The platform is backed by Microsoft SQL Server (RaceDayDB). The schema consists of 7 core entities designed with relational integrity and cascading rules:
USERS: Stores participant and organiser profile data with password security.
EVENTS: Captures race name, organizer mapping, date, and location
ROUTES: Stores start and endpoint data for specific events (1-to-0..1 optional mapping).
CATEGORIES: Holds sub-event options (distance, name, event type).
ENROLMENTS: Maps users to race categories and tracks race numbers and payment status.
