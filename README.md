# Extension-Attributes
Jamf Extension Attribute for Battery Health Condition

This extension attribute file will return a string indicating the status of the listed device's battery condition. This is normally "OK" or "Service" to
indicate the battery's current condition and whether replacement is warranted. 

Jamf's Battery Health Status extension attribute that's built in will only return "OK" as the status even if Service is the condition, and remaining capacity is
a fraction of the original.
