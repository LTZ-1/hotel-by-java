Main Responsibilities

User Interface & Layout Initialization: Sets up Swing UI components (JFrame, JPanels, JComboBoxes, JTextFields, JButtons, and custom layouts) to present room booking options and capture user inputs.

Room Selection & Pricing Calculation: Handles item selection across various room categories (Standard, Luxury, Family, Accessible, Villas, Specialty) and dynamically sets the selected room name and corresponding nightly room rate.

Input Validation: Ensures valid entry for fields such as number of nights, adult/child counts, vehicle count, and validates that check-in/check-out dates strictly follow the yyyy-MM-dd format and do not occur in the past.

Booking & Session Persistence: Saves booking details (room info, dates, guest counts, parking preferences, and user session email) into a local info.txt file and updates active room availability upon confirmation.

Booking Cancellation & Navigation: Provides event handlers to cancel existing bookings, restore room counts, clear session data, and seamlessly navigate to other application screens like Home or Order forms.
