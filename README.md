# Glarm

Geofence based alarm

Has different 'go off' style than normal alarm, combines time-range and location. System activates itself when entered begin of the time-range, keeps awake till end then terminates. When it's awake, looks up for geolocation transitions based on your choice. For real world scenario, i have to be left from home before 07:30 AM on weekday mornings. So i chosen **07:00 AM - 07:30 AM** for time-range, **home place** for location. The rest is so simple, whenever i dwell in home place between **07:00 AM - 07:30 AM**, app will notify me. But will not after 07:30 AM
