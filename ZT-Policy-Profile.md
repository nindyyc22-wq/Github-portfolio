# ZTA Component Definitions
Policy Engine (PE) - The brain of the Zero Trust Architecture. It works hand in hand with the Policy Administrator, to make decision on whether access is allowed or denied. It does this by using an algorithm, based on policy, to determine whether or not resources are granted. It also, logs this process and the results. 

Policy Administrator (PA) - The rule setter of the Zero Trust Architecture. The PA is the component that executes the decision made by the PE. The PA works with the Policy Enforcement Point to allow or deny the session. It manages the connection between the user and requested resource. With the use of authentication or session token, it's able to verify whether or not to establish or restrict the connection.

Policy Enforcement Point (PEP) - The gatekeeper of the Zero Trust Architecture. Based on the communications between the PA and PEP, it determines when to terminate the connection between the user and resource. It enables the connection, then monitors it.

# Core Principle Application
A ZT core principle is Least Privileged.

The Policy Engine grants access based on whether or not it's absolutely needed to perform their specific work duties. 

# Simplified Policy Table
| Resource | Signal (Inputs) | Condition | Enforcement |
| --- | --- | --- | :---: |
| HR Employee <br> PII Database| User Identity + <br> Device Posture + <br>Network Context | Is an HR employee at Golden State Water Treatment Facility <br> AND uncompromised device <br> AND using a trusted network | Allow Acess |


# Submission Details
 Git Repository Metadata

Project: Lab 2 - Zero Trust Policy

Filename: ZT-Policy-Profile.md

Commit Message: Add ZTA Component Definitions, Core Principle Application, and Policy Table

Due Date: February 27, 2026
