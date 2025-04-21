# Data Cleaning
Changes:
    1. Converted Dates:
        ScheduledDay and AppointmentDay columns were changed to proper date format.
    2. Standardized Gender:
        Gender was converted to lowercase and mapped to 0 (Male) and 1 (Female).
    3. Day of the Week:
        A new column for the day of the week was created based on ScheduledDay.
    4. Removed Columns:
        Dropped AppointmentID and PatientId columns as they weren't needed.
    5. Saved Cleaned Data:
        The cleaned data was saved to a new CSV file.
