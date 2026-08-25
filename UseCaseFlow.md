# Use-Case Flow Specification

## Use Case: Transfer Solar Credits

### Primary Actor
Prosumer Resident

### Preconditions
- The resident should have a valid account in the system.
- The resident should have enough solar credits available.
- The receiving resident should be registered in the same community.

### Postconditions
- The solar credits are deducted from the sender's account.
- The transferred credits are added to the receiving resident's account.
- The credit balances of both residents are updated.

### Main Success Scenario
1. The Prosumer Resident logs into the system.
2. The resident selects the option to transfer solar credits.
3. The resident selects the receiving resident.
4. The resident enters the number of solar credits to transfer.
5. The system checks the available credit balance.
6. The system confirms that the resident has enough credits.
7. The system transfers the credits to the receiving resident.
8. The system updates the credit balances of both residents.
9. The system displays a successful transfer message.

### Alternate Flow - Insufficient Credit Balance
1. The resident enters the number of credits to transfer.
2. The system checks the resident's available credit balance.
3. The system finds that the resident does not have enough credits.
4. The system rejects the transfer.
5. The system displays a message saying that there are insufficient credits available.
