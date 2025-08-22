# Changelog

## v1.1.15

- fix(ui): wording for student title of invoice creation
- fix(infra): http server config enhanced

## v1.1.14

- fix(ui): add tag filtering for invoice list
- fix(infra): request timeout for exporting large billing periods
- fix(frontend): typos
- fix(export): remove signing section for person export details

## v1.1.13

- fix: moved calculation for activation change permission to the API

## v1.1.12§

- fix: person settlement balance calculation unified
- fix: topbar title for settlement student list added
- fix: minor typing issues

## v1.1.11

- fix: managers and supervisors can now see all attachments
- fix: removed possible login deadlock
- fix: hide invoices with not outbalancing from account balance invoice list view

## v1.1.10

- fix(settlements): display correct number of active settlement participants
- fix(account balance): account balance amount on dedicated page should now be calculated correctly
- fix(ux): navigate back from invoice detail and not fix to invoice list
- fix(ui): date picker display ignores the timezone now

## v1.1.9

- fix: inactive people are now not selected when clicking the 'select all' icon in the invoice builder
- fix: date picker timezone handling
- fix: the log order in the person detail view for admins is now descending
- fix: date formatting ignores timezones now
- fix: settlements can now be deleted only by the owner or by an admin.

## v1.1.8

- feat: the datepicker popup accepts now disabled date limits like disabledBefore and disabledAfter.
- feat: add sorting support for settlement list
- fix: refined fetching permissions for invoice edit
- fix: calculation of compensation amount for invoice detail view works now
- feat: added sort oder for invoice connection list in invoice detail view
- feat: the save button in settlement settings saves now all changes at once

## v1.1.7

- feat: cashiers can now only delete settlement connections if they are allowed to
- fix: settlement connections are now only deletable is no booking exists
- fix: settlement owners are now set to inactive then the person is manager or supervisor

## v1.1.6

- fix: settlement connection permissions for supervisor and manager

## v1.1.5

- feat: settlement connect people: converted filter to backend search
- feat: added person delete feature for API and UI
- feat: added reference display for logs and automatic linking to the admin UI for logs regarding people
- fix: settlement edit permissions refined
- fix: metadata application command refined
- fix: refined storage cleanup command and added error handling

## v1.1.4

- fix: students can now be deleted when editing an invoice
- fix: add active and inactive filter for settlement students page
- feat: add inactive settlement connections with non zero saldo to settlement status calculation
- fix: supervisors can now change the password for other supervisors

## v1.1.3

- fix: changelog typos and formatting
- fix: outsourced changelog to asset repository

## v1.1.2

- fix: remove plausible
- fix: account balance calculation and display
- fix: reload settlement setting when user is deleted
- infra: upgraded dependencies
- ux: set invoice default type to invoice instead of credit
- ux: changed checkbox for invoice builder to tabs
- fix: refined rounding behaviour for account balance
- fix: renamed trilliuner to 'Kontoausgleich' / account balance

## v1.1.1

- fix: added conflict detection when adding new people to a settlement
- fix: added error handling for expired JWT
- fix: finished export refactoring
- fix: finished media refactoring

## v1.1

- fix: added title to log page, added log type mappings
- fix: removed logging
- fix: enhanced dateFns composable, integrated said composable into SettlementPreview
- fix: trilliuner amount doesnt get rounded to .05 amounts anymore
- dx: removed unnecessary logging
- fix: added rounding property to SaldoDisplay (default to false)
- fix: replaced multiple cookie initializations with one composable.
- fix: added sorting to people queries
- fix: added page meta to settlement detail index page. redirecting to overview works now
- fix: added selection count for students
- fix: added trilliuner amount in saldo display
- fix: added back button for invoice list if there are no invoices
- fix: transfer date is now shown on invoice detail
- fix: added error displaying to export section
- fix: created useVersion composable, integrated it into sidebar.
- fix: added defensive checks in proxyRequest to the backend
- fix: changed PersonNameLabel name order default to lastnamefirst, integrated PersonNameLabel to SettlementPreview
- fix: topbar title in settlement invoice section is now set on reload aswell and more fitting
- fix: added sidebar to connect page

## v1.0.9

- fix: connect people with settlement and changing their connection type works now
- fix: limit invoice comment to 5000 characters
- fix: added validation to transferDate of invoice (must be in between settlement range)
- fix: changelog works again
- fix: export saldos are calculated correctly again
- fix: logged in person interaction has now normal cursor instead of pointer cursor
- fix: invoice amount only accepts positive

## v1.0.8

- fix/infra: reduced docker image size by a factor of 14

## v1.0.7

- fix: settlement connection saving works now
- fix: export should now ignore deleted invoices
- fix: settlement filter enter press works now
- fix: added message to gotenberg health state
- feat: admins can now reset 2fa for cashiers
- fix: admins can now delete people in the admin dashboard
- fix: loading state on settlement connecting page is now aborted if an error occurs
- fix: loading state on settlement creation is now aborted if an error occurs
- fix: changelog works again in prod

## v1.0.6

- fix: added validation for start and end date in settlement settings
- fix: add label to start and end date in settlement settings
- fix: set request timeout in pdf export to 2 minutes and reset loading state on error
- fix: sort logs by createdAt
- fix: added back and dashboard button to error page
- fix: admin people detail deleted style adjustments
- fix: admin people filter adjusted
- fix: person can now not edit himself anymore
- fix: added sidebar to media libary
- fix: changed back button in invoice detail to always route to invoice list
- fix: changed password constraints
- fix: added back button to admin people
- fix: prohibit edit of deleted people
- fix: added sorting for settlement connections in settings
- fix: settlement connection preview amount is now cast as int but now as number
- fix: changed thumbnail url to proxy request
- fix: adjusted tag preview style

## v1.0.4

- fix: invoice connection amount is now registered correctly
- fix: added filter options to export and statistics list
- fix: active and iactive settlement calculations fixed in export and statistics list
- fix: invoice: fetch only invoice connections with associated person
- fix: changed logout url to absolute instead of relative
- fix: changelog is now readable in production as well
- fix: cards in settlement overview stretch now vertically
- fix: moved generam sidebar bottom menu to logged in person avatar in the topbar
- chore: upgraded dependencies
- fix: add name and role to topbar
- fix: magnifying glass gets now converted to close button in styled input if not declared otherwise
- fix: added image to error page and restyled it
- fix: copy text in admin ids fixed, added more ux to copy component
- feat: expanded credits
- fix: added back option to media library of settlement and statistics page of settlement
- fix: refined back bottom bar for custom back locations
- fix: added file validation and correct error handling in frontend
- fix: added quota and extension validation and error handling for thumbnailing in backend
- fix: added file size quota and rudimentary mime type checking in frontend
- fix: added sidebar to invoice list
- fix: added details to invoice beneficiary status
- fix: removed highlight option from tiptap editor
- fix: settlement amount on status detail gets now rounded
- fix: added password visibility toggle to login form
- fix: changed logo to blue version
- fix: added loading indicator when a media is being uploaded
- fix: removed not allowed cursor for inactive settlements
- fix: settlement name is now required in the UI
- fix: added placeholder to settlement settings input if no name or class is given
- feat: created tips and tricks page
- fix: removed bottom bar for settlement list views
- fix: adjusted title for list page of settlement export and settlement statistics
- fix: corrected changelog markdown error
- fix: config loading is now more reliable

## v1.0.3

- fix: added settlement relation to periods
- fix: unauthenticated people can load parts of the config now as well

## v1.0.2

- fix: added sidebar to settlement status page and settlement trilliuner page
- feat: added more REST interfaces for external APIs
- fix: log diffs support booleans now
- fix: added topbar title to settlement status page and settlement trilliuner page
- fix: invoice connections in invoice detail view are now filtered if person id is null
- fix: 2FA system works again

## v1.0.1

- managers and supervisors can now change the auth level of a user in the admin section

## v1.0.0

- Initial release

## v0.11

- fix: created proxy request for Adonis to attach Authorization headers

## v0.8.28

- fix: refined cookie handling from backend

## v0.8.25

- fix: added error handling for settlement status and trilliuner amount requests
- fix: removed about page
- fix: added MinIO health check

## v0.8.24

- fix: removed GraphQL fragment usage
- fix: color mode setting is now device persistent
- fix: trilliuner amount of 0 is now displayed correctly
- feat: integrated periods into settlement creation
