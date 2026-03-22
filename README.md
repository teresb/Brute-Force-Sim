# Brute Force Attack Simulation & Detection (Windows)

## Objective
Simulate a brute-force login attack and detect it using Windows Event Viewer.

## Tools Used
- Windows Command Prompt
- Event Viewer

## Methodology
1. Simulated failed login attempts using `runas`
2. Generated multiple authentication failures
3. Analyzed Windows Security logs
4. Filtered logs using Event ID 4625

## Key Findings
- Multiple failed login attempts detected
- Repeated login failures for the same username
- Pattern consistent with brute-force attack behavior

## Skills Demonstrated
- Log analysis
- Threat detection
- Understanding Windows security events
- Basic incident investigation
