# Testing

This project was tested locally in n8n.

## Functional Tests

| Test Case | Expected Result | Status |
|---|---|---|
| Price inquiry | Classified as `price` | Passed |
| Technical inquiry | Classified as `technical` | Passed |
| Refund inquiry | Classified as `refund` | Passed |
| Unclassified inquiry | Classified as `other` | Passed |
| Missing required field | Routed to required field error path | Passed |
| Invalid email format | Routed to invalid email path | Passed |
| AI draft generation | Draft response generated | Passed |
| Approval = approved | `workflow_status = ready_to_send` | Passed |
| Approval = rejected | `workflow_status = needs_revision` | Passed |
| Inquiry result logging | Result saved to Data Table | Passed |

## Error Handling

Error handling workflow has been implemented.

End-to-end automatic error-handler execution has not yet been fully validated.

## Notes

Tests were performed using sample data in a local n8n environment.
No real customer data was used.