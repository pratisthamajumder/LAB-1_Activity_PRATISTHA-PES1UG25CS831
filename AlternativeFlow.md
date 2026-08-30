# Alternative Flow - Activity Diagram

## Requirement Used
FR-003 - Transfer Solar Credits

## Alternative Flow

The alternative flow occurs when the resident tries to transfer more solar credits than the amount available in their account. The system checks the available balance before allowing the transfer.

## Activity Flow

1. The Prosumer Resident logs in to the system.
2. The resident selects the "Transfer Solar Credits" option.
3. The resident selects the receiving resident.
4. The resident enters the number of solar credits to transfer.
5. The system checks the available credit balance.
6. The system checks whether the balance is sufficient.
7. If the balance is sufficient, the system transfers the credits to the receiving resident.
8. The system updates the balances of both residents.
9. The system displays a successful transfer message.
10. If the balance is not sufficient, the system displays an "Insufficient credits" message.
11. The resident enters a different credit amount.
12. The system checks the balance again.

## Diagram

The activity diagram shows the normal transfer flow and the alternative flow when the resident does not have enough solar credits.
