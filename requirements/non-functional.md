# Non-functional Requirements

## Security
1. A billing staff should be only able to generate invoices. It should not be possible for the billing staff to directly alter the stock or promotional offers.
1. A manager should see only daily/monthly statistics. He should not be able to view quarterly statistics or GST details, nor should he be able to generate invoices.
1. An accountant should see only quarterly statistics.
1. No actions should be allowed without a valid user in the system.

## Performance
1. All requests should take less than 2 seconds to return a response.
1. The software should be light enough to work from a thin client.

## Scalability
1. The software should be able to handle ~2000 requests per minute.
1. The software should be able to handle addition of billing counters without change in code.

## Resilience and Fault Tolerance
1. An error in one counter should not affect working of other counters.
1. The software should be able to handle network outages.
