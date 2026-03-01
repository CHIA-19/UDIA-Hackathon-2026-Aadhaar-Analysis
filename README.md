** UDIA Hackathon 2026 **
## Aadhaar Analysis: A Multi-DimensionalAnalysis of Enrollment Maturity and Maintenance Demand
## Our Solution: The Operational Stress Mapping Framework
Our project introduces a new way to manage Aadhaar operations. Instead of just counting
heads, we identify Systemic Stress.
1. Creativity & Originality
We developed the "Update-to-Enrollment Ratio." This metric allows us to distinguish between
districts that are still "growing" and those that have ”matured” and now require a
different set of resources.
2. The "Maintenance Forecast"
By analyzing the Biometric Compliance Funnel, we can predict exactly when a wave of
teenagers will need biometric refreshes in a specific district. This allows the UIDAI to move
from Reactive Fixing to Proactive Resource Deployment.

** Goal **
To ensure that no citizen is denied a service simply because the system was too stressed to
process their update.

## Dataset Overview
To map the operational stress of the Aadhaar system, this analysis utilizes three interconnected
datasets provided for the year 2026. Together, they represent the complete ”Identity
Lifecycle”—from the birth of a new digital ID to its lifelong maintenance.
2.1 Enrolment Dataset (The Growth Track)
This dataset records the creation of new Aadhaar identities. It is the primary indicator of
system expansion and market saturation.
• Granularity: Data is captured at the State and District levels.
• Key Variables: Tracks new registrations across three critical life stages: age 0 5
(Newborns), age 5 17 (Youth), and age 18 greater (Adults).
• Operational Role: Used to identify ”Saturation Deserts” where new enrollment is
still high, indicating areas that are not yet fully onboarded into the digital ecosystem.
2.2 Demographic Update Dataset (The Maintenance Track)
This dataset captures changes to personal details such as names, addresses, and mobile
numbers. It is the most sensitive indicator of population movement and administrative
changes.
• Granularity: Captured at the PIN Code level, allowing for hyper-local ”Stress
Mapping.”
• Key Variables: Segregated by age groups (demo age 5 17 and demo age 17 ) to
track who is updating their records.
• Operational Role: High volumes in this dataset signify ”Migration Hubs” or districts
undergoing administrative reorganization (like new district formation), requiring a
temporary surge in service capacity.
2.3 Biometric Update Dataset (The Compliance Track)
This dataset monitors the refreshes of fingerprints, iris scans, and facial photographs. Biometric
accuracy is the ”heartbeat” of Aadhaar authentication.
• Granularity: Aggregated by State and District.
• Key Variables: Tracks mandatory refreshes for the bio age 5 17 and bio age 17
buckets.
• Operational Role: Used to calculate the Biometric Compliance Funnel, identifying
where youth are failing to perform mandatory updates at ages 5 and 15, which
is essential for preventing future service denials.
2.4 Unified Data Architecture
The strength of our analysis lies in the triangulation of these sources. By merging these
datasets on date, state, and district, we created a master operational file (df final)
that allows us to compare:
• The Maintenance-to-Growth Ratio: Comparing updates to enrollments.
• Temporal Synchronicity: Checking if peaks in demographic updates are followed
by biometric updates.
4
• Geographic Stress: Identifying PIN codes that appear as statistical outliers in update
volume compared to their historical enrollment baseline.
