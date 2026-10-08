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

## Files Touched

### 1. `FlagController.java`

Passed the optional description from the request to the service.

### 2. `CreateFlagRequest.java`

Added the optional `description` field to the request.

### 3. `Flag.java`

Added the `description` field, constructor parameter, and getter.

### 4. `FlagService.java`

Updated the `create()` method to accept and store the optional description.
