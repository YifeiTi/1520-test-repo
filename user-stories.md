# E1: Reporting an issue

Tenants can file a maintenance problem for their unit and add detail later.

## US1: Log in to my unit

As a tenant, I want to log in with an account linked to my unit so that I only see reports for the place I live.
FR: FR8
Priority: Must
MVP: yes

- [ ] A tenant cannot view or submit reports until they log in.
- [ ] After login, the tenant's account is tied to one unit, and they only see that unit's reports.
- [ ] A landlord logs in with an account linked to their property and only sees reports for that property.

## US2: Submit a maintenance issue

As a tenant, I want to submit a maintenance issue in under five steps so that I can report it before I get pulled back into what I was doing.
FR: FR3
Priority: Must
MVP: yes

- [ ] A logged-in tenant can submit a report by entering a short description and confirming, in four steps or fewer from the home screen.
- [ ] The saved report is added to that unit's active report list.
- [ ] A submission with an empty description is rejected, and the tenant is told the description is required.

## US3: Date the report on submission

As a tenant, I want the report to be dated when I submit it so that we can tell how long the problem has been open.
FR: FR2
Priority: Could
MVP: yes

- [ ] The system stores the date and time when the report is submitted.
- [ ] The tenant does not enter the date.
- [ ] The submission date is visible to every end user who can open the report.

## US4: Attach a photo

As a tenant, I want to attach a photo to a report so that the landlord can see the problem without coming over first.
FR: FR7
Priority: Should
MVP: no

- [ ] A tenant can attach one photo while submitting a report, or while viewing an existing report for their unit.
- [ ] The system accepts .png, .jpeg, and .jpg, and rejects any other file type with a message that names the allowed types.
- [ ] End users who can open the report can view the attached photo.

## US5: Comment on a report

As a tenant, I want to comment on an existing report so that I can add what I noticed without filing a second one.
FR: FR11
Priority: Could
MVP: no

- [ ] Any end user linked to the unit can add a text comment to a report for that unit.
- [ ] The comment shows who wrote it and when it was added.
- [ ] An empty comment is not saved.

# E2: Tracking a report

People linked to the unit can see what is open, and the landlord can move a report forward.

## US6: See active reports for my unit

As a tenant, I want to see every active report for my unit so that I know what my roommates already sent in.
FR: FR4
Priority: Must
MVP: yes

- [ ] After login, a tenant sees all active reports for their unit, including reports filed by roommates.
- [ ] A report marked Resolved no longer appears on the active list.
- [ ] A tenant cannot see reports for a unit their account is not linked to.

## US7: Show the report's stage

As a tenant, I want every report to show which stage it is in so that I can tell a new problem from one that is already being fixed.
FR: FR1
Priority: Must
MVP: yes

- [ ] Every report has exactly one status: Submitted, In progress, or Resolved.
- [ ] A report is Submitted as soon as it is saved.
- [ ] The status is shown on the active report list and on the report itself.

## US8: Update a report

As a landlord, I want to update a report's status and planned fix so that tenants know what I am doing about it.
FR: FR10
Priority: Must
MVP: yes

- [ ] A landlord can open a report for their property and change its status to In progress or Resolved.
- [ ] A landlord can add a short note describing the planned fix, including who is coming and when.
- [ ] A tenant cannot change the status or the planned-fix note.

## US9: View status and planned fixes

As a tenant, I want to open a report and read its status and any planned-fix notes so that I do not have to text the landlord for an update.
FR: FR6
Priority: Must
MVP: yes

- [ ] A tenant can open any report for their unit and see its current status.
- [ ] If the landlord has written a planned-fix note, that note is on the same screen.
- [ ] The screen also shows the date the report was submitted.

## US10: Hear when the landlord acknowledges a report

As a tenant, I want a notification when the landlord acknowledges my report so that I know it was not missed.
FR: FR5
Priority: Should
MVP: no

- [ ] When the landlord marks a report as acknowledged, every end user linked to that unit receives a notification.
- [ ] The notification names the report it refers to.
- [ ] No acknowledgement notification is sent unless the landlord has acknowledged the report.

## US11: Flag a similar open report

As a tenant, I want the system to tell me if a similar report is already open so that I can add to that one instead of creating a duplicate.
FR: FR9
Priority: Should
MVP: no

- [ ] Before a new report is saved, the system compares its description with open reports for the same unit.
- [ ] If a similar open report exists, the system shows that report and lets the tenant cancel the new submission.
- [ ] The tenant can still submit the new report after seeing the match.

## US12: Filter the report list

As a landlord, I want to filter reports by status and date so that I can find the ones I still need to handle.
FR: FR12
Priority: Could
MVP: no

- [ ] A landlord can filter the report list by status: Submitted, In progress, or Resolved.
- [ ] A landlord can filter the report list by submission date.
- [ ] Clearing the filters shows the full list again.
