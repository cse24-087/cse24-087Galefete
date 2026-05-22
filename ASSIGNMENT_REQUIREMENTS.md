# MAD Assignment Requirements Map

Project folder: `C:\Users\galef\Documents\Student Accomodation`

## App Chosen

Student Accommodation Finder for Gaborone students.

## Functional Requirements Started

- User management: `LoginActivity`, `RegisterActivity`, seeded 50 student records.
- Listings: Room `listings` table seeded with 50 accommodation records including title, BWP price, Gaborone location, type, amenities, availability date, deposit amount, image filename, campus distance, and status.
- Smart filtering and alerts: `FilterActivity` filters by availability date and max price, then sends a local notification with match count.
- Deposit and reservation: `ReservationActivity` simulates deposit payment, generates a receipt/reference number, changes listing status to `Reserved`, and blocks duplicate reservations.
- Mandatory extension chosen: Chat between student and landlord.
- Minimum screens: Login, Register, Listings, Listing Details, Smart Filter, Chat, Reservation, Receipt, My Reservations.
- Listing images: six real photo-based room/house PNG images are stored in `app/src/main/res/drawable` and reused across the 50 records.

## Technical Choices

- Language: Kotlin.
- IDE target: Android Studio.
- Database: Room.
- UI approach: Native Android views in Kotlin to keep the starter project lightweight.

## Demo Video Talking Points

- Problem: Students need quick, verified accommodation options around Gaborone.
- Users: Students looking for rooms and landlords/providers listing spaces.
- Database schema: Students, listings, reservations.
- Main workflows: Register/login, browse listings, filter by date/price, reserve, view receipt.
- Testing: invalid login, required field validation, filter matches, successful reservation, duplicate reservation prevention.

## Remaining Work

- Polish UI styling further after testing on an emulator/device.
- Build APK after Android SDK/Gradle sync is available.
- Create the 3-6 page report or PowerPoint with screenshots.
