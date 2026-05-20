## Project: Smart Operation Lab 

# Title: 500 - UI Wireframe

## Global application layout
```text
+-------------------------------------------------------------+
| Header                                                      |
| Logo | Company | Fiscal Year | User | Notifications         |
+-------------------------------------------------------------+
|  [Top menu]                                                 |
+-------------------------------------------------------------+
|  [Main area]                                                |
|                                                             |
|                                                             |
|                                                             |
|                                                             |
|                                                             |
|                                                             |
|                                                             |
+-------------------------------------------------------------+
```

Notes:
- Responsive required: NO you can optimize the css html for a desktop monitor of display resolution wide 1360;
- All other page, except the login page, are visualized on the [Main Area]

## Login page 
```text
+---------------------------------------------------+
|                                                   |
|                   [Company Logo]                  |
+---------------------------------------------------+
|                                                   |
|  Email:      [____________]                       |
|  Password:   [____________]                       |
|                      [ Login ]                    |
|                                                   |
|                        - OR -                     |
|                                                   |
|            [Log in with Microsft Entra ID]        |
|                                                   |
+---------------------------------------------------+
```
Notes:
- This is the only page avaible for anonymous user
- This page have one optional parameter in the url who is the ReturnUrl. If the login procedure have a success result the user is redirected on the url in the ReturnUrl paramenter if is present else redirect to the home page

## Home page
```text
+---------------------------------------------------+
| Fiscal year: [___________] Work date: [________]  |
+---------------------------------------------------+
|                                                   |
|                                                   |
|                                                   |
|                                                   |
|                                                   |
|                                                   |
|                                                   |
|                                                   |
|                                                   |
|                                                   |
|                                                   |
+---------------------------------------------------+
```

Notes
- Is a blank page except of the first area on the top

## General ledger account List
```text
+--------------------------------------------------------------------+
| Search: [____________]  [] Filter 	-- []Add 										             |
+-------+------------------+------+-----------+----------+-----------+
| Code 	| Name             | Type | MainGroup |    Debit |    Credit |
+-------+------------------+------+-----------+----------+-----------+
```
Debit or Credit is the amount of  the transaction of any account during the fiscal year. If the sum is negative is Debit else is Credit
