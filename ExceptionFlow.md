# Exception Flow Document

## Requirement
FR-003 - Transfer Solar Credits

## Exception Flow

The exception flow explains what happens when the solar credit transfer cannot be completed normally.

### Exception 1 - Insufficient Solar Credits

If the resident tries to transfer more credits than the available balance:

1. The resident enters the amount of credits to transfer.
2. The system checks the available credit balance.
3. The system finds that the balance is not enough.
4. The transfer is cancelled.
5. The system displays an "Insufficient credits" message.
6. The resident can enter a smaller amount and try again.

### Exception 2 - Receiving Resident Not Found

If the receiving resident is not registered in the system:

1. The resident selects the receiving account.
2. The system checks the account details.
3. The receiving resident is not found.
4. The transfer is stopped.
5. The system displays a message that the receiving resident is not available.
6. The resident can select another registered resident.

### Exception 3 - Transfer Failure

If a problem occurs while processing the transfer:

1. The resident confirms the transfer.
2. The system tries to process the transaction.
3. The transfer cannot be completed.
4. The system does not change either resident's credit balance.
5. The system displays a transfer failure message.
6. The resident can try the transfer again later.

## Result

The exception flow makes sure that invalid or failed credit transfers do not incorrectly change the solar credit balance of the residents.
