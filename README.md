BreathScope – User Manual

Version: Inspiration / Research Prototype
Author & IP: Moustafa Ali
Contact: dptmostafa@gmail.com | Agentic@virtualcaresolution.de

⸻

1. Purpose of BreathScope

BreathScope is a microphone-based respiratory screening and trend-monitoring tool designed as an inspirational and exploratory prototype.

It demonstrates how commodity smartphone sensors (microphones) can be used to:
	•	Capture breathing sound signals
	•	Derive airflow-related proxies
	•	Estimate respiratory parameters for personal trend observation

⚠️ BreathScope is NOT a medical device.

⸻

2. Intended Use

BreathScope is intended for:
	•	Educational purposes
	•	Research inspiration
	•	Digital health demonstrations
	•	Personal, non-clinical breathing trend observation
	•	Concept validation for remote monitoring ideas

It is not intended for:
	•	Medical diagnosis
	•	Clinical decision-making
	•	Therapy guidance
	•	Emergency use

⸻

3. System Requirements
	•	Smartphone, tablet, or laptop with:
	•	Built-in microphone
	•	Modern browser (Chrome, Safari, Edge)
	•	Internet access only for initial loading (runs fully client-side)
	•	No account, no backend, no data upload

⸻

4. Language Selection

At the top of the application, select your preferred language:
	•	English
	•	Deutsch (German)

The interface, labels, and disclaimer update automatically.

⸻

5. User Inputs

5.1 Age
	•	Enter your age in years
	•	Used only for normalization heuristics

5.2 Height
	•	Enter your height in centimeters (cm)
	•	Used to scale estimated lung capacity

If no values are entered, default reference values are applied.

⸻

6. Performing a Breathing Test

Step-by-step instructions:
	1.	Hold the phone 20–30 cm from your mouth
	2.	Sit upright or stand
	3.	Take a deep breath in
	4.	Press “Start Breathing Test”
	5.	Blow out as hard and as steadily as possible for 5 seconds
	6.	Wait for results to appear

💡 Tips for consistency:
	•	Use the same phone each time
	•	Keep distance and posture consistent
	•	Avoid background noise

⸻

7. Displayed Results

After each test, BreathScope displays:

7.1 Estimated Peak Expiratory Flow (PEF – relative)
	•	Derived from sound energy peaks
	•	Expressed as a relative, non-calibrated value
	•	Useful only for within-user comparisons

7.2 Estimated FEV₁
	•	Heuristic estimation based on:
	•	Sound peak
	•	Age
	•	Height
	•	Displayed in liters (L)

⚠️ These values are approximations, not measurements.

⸻

8. Trend Charts
	•	Each test is stored locally using browser localStorage
	•	No data leaves your device
	•	A line chart visualizes estimated FEV₁ over time

Interpretation:
	•	Look for personal trends, not absolute values
	•	Sudden drops may indicate changes worth discussing with a clinician

⸻

9. Clinical Validation Mode

Purpose

Clinical Validation Mode supports research comparison, not diagnosis.

How to use:
	1.	Enable “Clinical validation mode”
	2.	Enter a reference FEV₁ value from a certified spirometer
	3.	Perform a BreathScope test
	4.	The system displays the difference (ΔFEV₁)

This mode is intended for:
	•	Pilot studies
	•	Algorithm exploration
	•	Method comparison

⸻

10. Data Privacy & Security
	•	All processing happens locally in the browser
	•	No servers, cookies, analytics, or tracking
	•	Data persists only in your browser storage
	•	Clearing browser data deletes all trends

⸻

11. Disclaimer (Legal & Medical)

BreathScope is NOT a medical device under MDR, FDA, or any regulatory framework.

It:
	•	Does NOT comply with ATS/ERS spirometry standards
	•	Does NOT replace professional lung function testing
	•	Must NOT be used for diagnosis or treatment decisions

Always consult a qualified healthcare professional for medical concerns.

⸻

12. Known Limitations
	•	Microphone variability between devices
	•	Environmental noise sensitivity
	•	No airflow calibration
	•	Heuristic-based estimation
	•	User technique affects results

These limitations are explicit and intentional for an inspiration prototype.

⸻

13. Intellectual Property & Attribution

© Concept, design, and implementation:

Moustafa Ali
Agentic@virtualcaresolution.de
dptmostafa@gmail.com

All rights reserved.

⸻

14. Versioning Note

This tool is provided “as-is” for inspiration and exploration.
Future versions may change functionality, models, or structure without notice.

⸻

End of User Manual
