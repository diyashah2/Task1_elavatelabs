# Data Cleaning
Changes:
    Converted Dates:
        ScheduledDay and AppointmentDay columns were changed to proper date format.
    Standardized Gender:
        Gender was converted to lowercase and mapped to 0 (Male) and 1 (Female).
    Day of the Week:
        A new column for the day of the week was created based on ScheduledDay.
    Removed Columns:
        Dropped AppointmentID and PatientId columns as they weren't needed.
    Saved Cleaned Data:
        The cleaned data was saved to a new CSV file.
