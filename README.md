# Healthcare Appointment Dashboard — Data Analysis Summary
## Project Overview 

This project analyzes healthcare appointment scheduling data to evaluate access-to-care efficiency by measuring the time difference between when an appointment was requested and when it actually occurred. The analysis focuses on identifying delays across provider roles, time periods, and individual clinicians to uncover operational bottlenecks and opportunities to improve patient access.

The dashboard visualizes trends in average wait time (in days), compares performance by provider type (MD, Nurse, Psychologist), and highlights individuals and months associated with longer scheduling delays. The goal is to support healthcare administrators in optimizing scheduling workflows and improving timely care delivery

<img width="1244" height="685" alt="Screenshot 2026-02-16 232353" src="https://github.com/user-attachments/assets/e591c212-a83b-456c-aa9e-17ef8cf890bf" />

## Key Analytical Questions

- How long do patients wait between requesting and receiving an appointment?
- Does wait time differ by provider role (MD, Nurse, Psychologist)?
- Are there specific months where access delays increase?
- Which providers experience the longest scheduling gaps?
- Is there a trend indicating worsening or improving access over time?
- Where should operational changes be prioritized to reduce patient wait times?

# Key Findings / Results
## 1. Wait Time Varies Significantly by Provider Role
- Nurses showed the longest average wait time ( 10 days).
- MDs followed closely (9–10 days).
- Psychologists had shorter wait times ( 6–7 days).

## 2. Access Delays Increased Over Time (September → November)
- September had relatively low delays.
- October showed moderate increases.
- November experienced the highest wait times (peaking ~35 days combined across roles).

## 3. Specific Providers Experience Disproportionate Scheduling Delays
Top providers by average delay:
- Richie Hickman (40+ days)
- Sameer Howard (25 days)
- Romeo Russo (24 days)

## 4. Daily Trend Analysis Shows Irregular Scheduling Patterns
- The time-series visualization revealed:
- Fluctuating delays rather than stable scheduling.
- Several sharp spikes (>25 days), indicating episodic backlog.
