Project: Smart Operation Lab
Title: 001 - Authentication and authorization

## Anonymous User
Only the login page is accessible by anoanymous user


## Application user
The first page shown are the login page
On the page a user have the ability to use the local authentication provider or use Microsft Entra ID a
Someone can access the application as a AppUser (application interna) o trmite Microsft Entra ID

## Login page wireframe
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

If login is success go tu the return url in the parameter is present in the query url or to the honepage if is not present


Notes:
- Responsive required: NO you can optimize for a desktop monitor of display resolution wide 1360
- Dark mode: YES / NO
- Multi-company switch: At the login page

---


