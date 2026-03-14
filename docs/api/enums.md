# Enums

Enums used by the billing API.

---

## BillingResponseCode

Response codes returned by billing operations.

```
OK = 0
USER_CANCELED = 1
SERVICE_UNAVAILABLE = 2
BILLING_UNAVAILABLE = 3
ITEM_UNAVAILABLE = 4
DEVELOPER_ERROR = 5
ERROR = 6
ITEM_ALREADY_OWNED = 7
ITEM_NOT_OWNED = 8
NETWORK_ERROR = 12
SERVICE_DISCONNECTED = -1
FEATURE_NOT_SUPPORTED = -2
SERVICE_TIMEOUT = -3
```

---

## ConnectionState

Represents the billing connection state.

```
DISCONNECTED
CONNECTING
CONNECTED
CLOSED
```

---

## ProductType

Defines the type of product.

```
INAPP
SUBS
```

---

## PurchaseState

Represents the state of a purchase.

```
UNSPECIFIED_STATE
PURCHASED
PENDING
```

---

## ReplacementMode

Defines how subscription replacements behave.

```
UNKNOWN_REPLACEMENT_MODE = 0
WITH_TIME_PRORATION = 1
CHARGE_PRORATED_PRICE = 2
WITHOUT_PRORATION = 3
CHARGE_FULL_PRICE = 5
DEFERRED = 6
```
