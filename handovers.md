# End-of-shift handovers · Cloudora

## Shift 1 · 2026-09-07

Closed: CLD-0201, CLD-0202, CLD-0204
Open: CLD-0203. Insufficient data to confirm login was legitimate. Contact Eleanor Walsh to check whether login on Sunday was from her. Review guest account MFA policy as soon as possible.

## Shift 2 · 2026-09-08

Closed: CLD-0205, CLD-0206, CLD-0207, CLD-0208
What needs to be watched: Malicious phishing email attempts pretending to be DocuSign to harvest user account credentials.

## Shift 3 · 2026-09-09

Closed: CLD-0210, CLD-0211, CLD-0212
Opened: CLD-0209. Account ewalsh.ext@cloudora.io is highly probable to be compromised. Requires session revoke and password reset. Block mallicious IP. Review guest MFA policy immediately. Continue to monitor the malicious actor's activity.

## Shift 4 · 2026-09-10

Closed: CLD-0214 and CLD-0215
Opened: CLD-0213 and CLD-0216. CLD-0213: Attacker can still access account consent to extensive application permission. Change token expiration and regeneration policy. CLD-0216: Attacker could not log into account but has access to account credentials. Investigate how credentials got leaked.

## Shift 5 · 2026-09-11

CLosed: CLD-0218, CLD0219
Opened: CLD-0217, CLD-0220. CLD-0217: Issue escalated. Contact cyber forensic team to investigate the data sent to bexley-sync.example. CLS-0220: Check through domain finance@cloudora.io to see whether there are important financial messages received during the subscription bombing period. Continue to monitor email activity.

## Shift 6 · 2026-09-12

Closed: CLD-0224
Opened: CLD-0221, CLD-0222, CLD-0223. Executive account daniel.reeve and guest account Eleanor Walsh are compromised. Revoke sessions, invalidate tokens, and reset passwords. Change email inbox rule of account daniel.reev@cloudora.io. Review token expiration and regeneration policy. Increase phishing email awareness.

## Shift 7 · 2026-09-14

Closed: CLD-0227, CLD-0228
Open: CLD-0225, CLD-0226. Unexpected schedule tasks created by malicious actor. Proof that blocked IP are still attempting to perform malicious actions to our system. Revoke service account session and invalidate token. Continue to monitor known malicious actors behaviour. Investigate threat actor's persistent in the company's system. Investigate email baseline variance.

## Shift 8 · 2026-09-15

Closed: CLD-0230, CLD-0231
Opened: CLD-0229, CLD-0232. Send IoC sweep to Bexley Payroll Integration for their investigation; review unwatched IoCs and put them in watchlist. Confirmed compromise of marcus.oje@cloudora.io. Revoke session and invalidate token. Continue to monitor unexpected / suspicious activities.

## Shift 9 · 2026-09-16

Closed: CLD-0234 (duplicated)
Opened: CLD-0233, CLD-0235, CLD-0236. CLD-0233: Remove tenant-wide admin consent for the integration application to original Read.All.File for payroll-live site only. CLD-0235: Revoke session, invalidate token and reset password for account finance-admin@cloudora.io. Investigate how the credential get leaked. CLD-0236: Immediately audit ryan.beck's machine and see any LSASS file/drive dump in his system. If so, destroy it immediately. Check whether user has sent file to external entity. If so, reset all user password. Contact ryan.beck to investigate his intent of this activity.

## Shift 10 · 2026-09-17

Closed: CLD-0238
Opened: CLD-0237, CLD-0239, CLD-0240. Phishing email from 198.18.60.2, a confirmed malicious IP, continue to monitor activity originates from that IP and domain. Lack of DMARC for emails from Cloudora. Suggest to add SPF record and implement DKIM. A few malicious IPs sent spoofed email, pretending to be our domain. Continue to monitor activities from our email domain name.

## Shift 11 · 2026-09-18

Opened: CLD-0241, CLD-0242, CLD-0243, CLD-0244
CLD-0241: Confirmed reconnaissance activities from adversary before incident window. Limited log retention period means that we cannot see activity before 19th Sepetember. Suggest to extend log retention. 
CLD-0242: Sharing link with extensive scope created; contact IT admin and revoke permission
CLD-0243: Potential data exfiltration and to unmanaged device and external parties. Contact sam.okoro and remove files synced to his personal device.
CLD-0244: Risks for both approving and denying reenabling guest ewalsh.ext@cloudora.io. Decision hands to executive. Contact Bexley Payroll Integration for more information regarding their investigation.

## Shift 12 · 2026-09-20

Closed: CLD-0246
Opened: CLD-0245, CLD-0247, CLD-0248. Contact HR and legal team regarding the incidents of user sam.okoro. Block suspicious IP from subnet 198.18.92.0/24 and continue to monitor any password spraying attack. Contact Bexley Payroll Integration to investigate whether there are account list information leak from their company.

## Shift 13 · 2026-09-21

Opened: CLD-0249, CLD-0250, CLD-0251, CLD-0252
Immediate revoke link and conditional access policy that enable insecure authentication methods (CLD-0249: sharing link, CLD-0251: MFA exclusion). Further investigation of cutover activities are required and the benefit and risks of the configurations are written down. Revoke legacy service session and change password immediately.

## Shift 14 · 2026-09-22

Closed: CLD-0254
Opened: CLD-0253, CLD-0255, CLD-0256. Malicious macro sent across 9 finance recipients and 2 opened the attachment. Macro fetches unknown file from the internet and tamper with computer protection. Isolate the two affected computers from the network, watch the activities from the IP 198.18.44.20, quarantine the process and perform further investigation.

## Shift 15 · 2026-09-23

Opened: CLD-0257, CLD-0257, CLD-0259, CLD-0260
Review detection gap proposal and rule modifications suggestions. Revoke external recipient permission to read the folder and contact sam.okoro for the past 4 data collection incidents to understand his motive.

## Shift 16 · 2026-09-24

Closed: CLD-0262, CLD-0263
Opened: CLD-0261, CLD-0264. Revoke user session, invalidate tokens and reset password. Continue to monitor suspicious behaviour from the new domain. Potential credential leak of the CEO's account, investigate. Review guest MFA policy as new guest account are exposed to the same risk as previous incidents.

## Shift 17 · 2026-09-25

Closed: CLD-0266
Opened: CLd-0265, CLD-0267, CLD-0268. Update system when new procurement information (device compliance, phone number and manager confirmation) is received on nadia.rahman. Contact tara.kemp to investigate file upload behaviour. Contact all staff regarding the ExpenseFlow credential breach incident, closely monitor any abnormal sign-in activity. Contact ExpressFlow for more attacker information.

## Shift 18 · 2026-09-27

Opened: CLD-0269, CLD-0270, CLD-0271, CLD-0272. Account priya.nair@cloudora confirmed credential, certificate and session compromised. Revoke session, invalidate token and certificate, and reset password. Escalate to incident response team for incident response. Investigate suspicious behaviour from the account from 5am till now.

## Shift 19 · 2026-09-30

Closed: CLD-0273, CLD-0274. Report review to A. Bello. 
Opened: CLD-0275, CLD-0276. Known credential leak from service account svc-deploy. Revoke session, invalidate tokens and reset passwords. Continue monitoring. Correct the misconfiguration of the scheduled task created on LDN-SRV-CI1 and contact build-team@cloudora.io.

## Shift 20 · 2026-10-01

Closed: CLD-0277. Review report.
Opened: CLD-0278, CLD-0279, CLD-0280. 3 open threads the requires monitoring and policy reviews. Continue to monitor any password spraying attempt from threat actors. Revoke sharing links, tokens and memberships of sam.okoro and add these steps to offboarding procedure. Contact kmarsh to confirm his login attempt. if it is not him, revoke session, invalidate token and reset password.
