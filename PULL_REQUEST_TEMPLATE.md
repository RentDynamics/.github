## PR Checklist
 * Which ticket is this associated with?
    * Closes #ISSUE_NUMBER
 * Where can we test this?
    * http://SUBDOMAIN.dev.rentdynamics.com
 * Additional Notes
    * NOTES


## Dev Checklist (Code Reviewer is responsible for filling this out or providing a brief explanation why it isn't necessary)
- [ ] Verify that code is tested appropriately 
- [ ] Evaluate all calls to the DB are efficient
- [ ] Ensure any values returned for the DB are cached and reused
- [ ] Evaluate any code that is run by a Pusher event is very clean and very necessary
- [ ] Verify that all critical algorithms work as intended


## Q/A Checklist (
- [ ] Review that solution matches mockup
- [ ] Review that solution matches JTBD
- [ ] Update test plan with test cases created
- [ ] Verify solution doesn't allow rage clicking of buttons
