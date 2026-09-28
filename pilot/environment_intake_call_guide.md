# Environment Intake Call Guide

One page to have open during the week 1 intake call. It follows the same order as the
Environment Intake workbook. Bring the workbook to record answers; use this page to keep
the conversation moving.

## Before the call

Confirm who is joining. The right person is whoever actually runs the systems, not only a
manager. If both are available, that is better still. Tell them in advance that some answers
may be "we are not sure," and that this is a normal and useful answer.

## Opening line

"I want to understand what you actually have today, not what the ideal setup looks like.
If something is undocumented, informal, or you are not certain, say so. That tells me as
much as a clean answer does."

## Questions, in order

**Organization.** How many people, how many sites, who runs IT day to day, and are there
any specific regulatory or contractual obligations you have to meet.

**Hosting.** What runs on physical servers you own, what runs in a colo, and what already
runs in the cloud. Ask directly: is anything running on an operating system that is no
longer supported by its vendor.

**Identity.** What directory service is in use. Which applications are behind single
sign-on. Where MFA is enforced and where it is not. Ask specifically about shared logins
and whether any system still accepts an older authentication method.

**Network.** How sites connect to each other. What firewall is in place. Whether there is
any segmentation today, or whether the network is flat. How the cloud environment connects
back to anything on-premises.

**Endpoints.** Roughly how many devices are managed versus not. Whether personal devices
are used for work. What endpoint protection is actually installed, not what is licensed.

**Security tooling.** Is there a central place logs go. Who actually looks at it. Is there
any vulnerability scanning, and how often.

**Data.** What kinds of sensitive data the organization holds, where it physically lives,
and whether any classification scheme is already in use, even an informal one.

**Backup and disaster recovery.** What gets backed up, where, and critically, when a
restore was last tested. A backup that has never been restored is not a verified backup.

**Migration status.** What has already moved, what is planned, and in their own words,
what they are worried will break. This last question often surfaces the most useful
information in the whole call.

## Close the call by asking

"Is there anything running today that only works because of a workaround, an exception, or
something that was supposed to be temporary?" Write every answer down exactly as given, even
if it sounds minor. These become the first entries in the Temporary Conditions sheet, and
from there, the risk register.

## After the call

Complete the Applicability Map before scoring anything. Not every scorecard domain will fit
every organization, and the intake answers are what tell you which ones do.
