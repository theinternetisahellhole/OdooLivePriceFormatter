# Odoo Live Price Formatter
```md
![Odoo](https://img.shields.io/badge/Odoo-18.0-714B67?logo=odoo&logoColor=white)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Tested](https://img.shields.io/badge/tested%20on-Odoo%2018-success)
![License](https://img.shields.io/badge/license-LGPL--3-green)
![Status](https://img.shields.io/badge/status-production-success)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)
```


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
