# Odoo Live Price Formatter

## Overview

This module automatically formats numeric price inputs while the user is typing. As soon as a value is entered, thousands separators (`,`) are added in real time, improving readability and reducing input errors.

### Example

Input:

```
1000000
```

Displayed instantly as:

```
1,000,000
```

## Features

* Real-time formatting while typing
* Automatic thousands separator insertion
* Better user experience for price and amount fields
* No need to leave the field or save the record
* Lightweight and easy to integrate with existing Odoo forms

## Supported Examples

| User Input | Displayed Value |
| ---------- | --------------- |
| 1000       | 1,000           |
| 25000      | 25,000          |
| 1234567    | 1,234,567       |
| 999999999  | 999,999,999     |
