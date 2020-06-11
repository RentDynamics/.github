## PR Checklist
 * Which ticket is this associated with?
    * Closes #ISSUE_NUMBER
 * Where can we test this?
    * http://SUBDOMAIN.dev.rentdynamics.com
 * Additional Notes
    * NOTES


## Dev Checklist (Code Reviewer is responsible for filling this out or providing a brief explanation why it isn't necessary)

- [ ] Verify that code is tested appropriately 
- [ ] Verify that all critical algorithms work as intended

Frontend Concerns
- [ ] Evaluate all calls to the DB are efficient
- [ ] Ensure nullable values are treated as such and handled appropriately
- [ ] Ensure any values returned for the DB are cached and reused
- [ ] Evaluate any code that is run by a Pusher event is very clean and very necessary



## Q/A Checklist (QA is responsible for filling this out or providing a brief explanation why it isn't necessary)
- [ ] Appropriate test plan has been updated with all testing performed
- [ ] Review that solution matches JTBD

Frontend Concerns
- [ ] Review that solution matches mockup
- [ ] Verify solution doesn't allow rage clicking of buttons
