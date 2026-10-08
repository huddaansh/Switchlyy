# Switchlyy

## ASSIGNMENT FOR SESSION 2

## 1. Add a Description Field to Flag

The `Flag` model was updated to include an optional `description` field.

The description can be provided when creating a flag, but it is not required.

### Example

With description:

```json
{
  "key": "new-checkout",
  "name": "New Checkout",
  "description": "New checkout experience"
}
