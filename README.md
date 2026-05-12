
# Okta-IAM-Labs
Documenting my entire Okta Workforce Identity journey completed through Okta's What's Next Learning Grant (April 2026).

All modules completed via Okta's official learning platform as part of my 90-day sprint toward the Okta Certified Professional and Okta Certified Administrator certifications.

---

## Module 1: Customize Your Okta Org
**What I learned:** Applied customization to control how Okta communicates with end users. This includes branding, email templates, and user facing settings.  
**Why it matters:** Enterprise orgs require consistent branding and communication standards across identity workflows.

---

## Module 2: Define Your Users in Okta
**What I learned:** Managed user accounts in Universal Directory, configured user profiles, and handled data accuracy during provisioning as part of lifecycle management.  
**Why it matters:** Clean, accurate user data is the foundation of any IAM program.

---

## Module 3: Organize Users with Groups
**What I learned:** Configured group membership to control application access, administrative privileges, and policy assignments.  
**Why it matters:** Group based access is how least privilege is enforced at scale in real enterprise environments.

---

## Module 4: Define Okta Administrators
**What I learned:** Configured standard and custom administrator roles to enforce least privilege across the Okta admin console itself.  
**Why it matters:** Over privileged admins are a major attack surface. scoping admin roles is a core Zero Trust principle.

---

## Module 5: Define a Secure Policy Structure
**What I learned:** Built a secure policy framework using assurance technology and Okta's comprehensive security policies, balancing security with user experience.  
**Why it matters:** Policy structure determines how authentication and authorization decisions are made inside an organization.

---

## Module 6: Implement Security Policies
**What I learned:** Strengthened security posture by configuring and leveraging Okta's full security policy framework.  
**Why it matters:** Knowing how to implement not just understand security policies is what separates practitioners.

---

## Module 7: Implement Passwordless Authentication
**What I learned:** Configured phishing resistant MFA including Okta FastPass for passwordless authentication flows.  
**Why it matters:** Passwordless is the direction enterprise auth is heading towards. this reduces credential based attacks while improving UX.

---

## Module 8: Create App Integrations
**What I learned:** Integrated applications with Okta to provide SSO access. covering SAML, OIDC, and the Okta Integration Network.  
**Why it matters:** App integration is one of the most hands on in demand IAM skills. Every enterprise has dozens of apps to federate.





## Troubleshooting Log

### Issue: Could not complete provisioning for Salesforce
**What I thought:** Provisioning was part of the SSO configuration process
**What was actually happening:** SSO and Provisioning are separate functions. 
I had successfully completed SSO but was stuck on provisioning because I 
didn't have a Salesforce developer account for Okta to connect to.
**What I learned:** SSO controls authentication. Provisioning controls 
lifecycle management. You can complete one without the other. Full lifecycle 
management requires both  and requires valid API credentials on the 
application side.
**Fix:** Sign up for a Salesforce Developer account (free) to complete 
the provisioning integration end to end.


---

## Module 9: Automate User Provisioning
**What I learned:** Configured automated user provisioning and deprovisioning for full lifecycle management between Okta and connected applications.  
**Why it matters:** Manual provisioning doesn't scale and creates orphaned accounts. Automation is how IAM teams enforce joiner/mover/leaver policies.



---

## Module 10: Monitor Your Okta Org
**What I learned:** Used Okta's monitoring tools to identify tasks, errors, and informational issues requiring attention in the org.  
**Why it matters:** IAM isn't just configuration but ongoing monitoring is how you catch misconfigurations, suspicious activity, and policy drift.

---

## Certifications Targeted
- Okta Certified Professional

