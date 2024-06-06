# 🛠️ DamlHouseRentalService 🛠️
DamlHouseRentalService is a house rental application built in Daml.

### I. Overview

Guest can create a BookingProposal contract. Host can Reject or Approve the house booking. Upon getting rejected, the guest can exercise Revise to re-book at another date. Upon getting approved, a Booking contract is created.

### II. Workflow
  1. guest creates a BookingProposal contract
  3. host exercises Reject with feedback: "House is unavailable"
  4. guest exercises Revise with an updated date
  5. host exercises Approve where a Booking contract is created

### III. Compiling & Testing
To compile and test, run the pre-written script in the `Test.daml` under /daml OR run:
```
$ daml start
```
