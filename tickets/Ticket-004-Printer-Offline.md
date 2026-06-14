# Ticket #004 - Office Printer Offline and Unable to Print Documents

## Scenario
User reported that the office printer appeared offline and was unable to print documents. Print jobs were stuck in the queue and not being processed.

## Investigation
- Verified printer power status and confirmed the device was turned on
- Checked print queue and confirmed jobs were pending
- Reviewed printer network connectivity
- Identified that the printer had lost connection to the network
- No hardware faults were detected

## Root Cause
Printer lost network connectivity, causing print jobs to fail and remain in the queue.

## Resolution
- Reconnected printer to the network
- Restarted print spooler service
- Performed test print successfully

## Outcome
User confirmed that printing functionality was restored and documents printed normally.
