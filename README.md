# Odoo Live Price Formatter
![Odoo](https://img.shields.io/badge/Odoo-18.0-714B67)
![Tested](https://img.shields.io/badge/Tested%20On-Odoo%2018-success)
![Type](https://img.shields.io/badge/Type-Odoo%20Addon-blue)
![Feature](https://img.shields.io/badge/Feature-Real--Time%20Price%20Formatting-brightgreen)
![Feature](https://img.shields.io/badge/Feature-Thousands%20Separator-green)
![Frontend](https://img.shields.io/badge/Frontend-JavaScript-yellow)
![License](https://img.shields.io/badge/License-LGPL--3-green)
![Status](https://img.shields.io/badge/Status-Active-success)

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
