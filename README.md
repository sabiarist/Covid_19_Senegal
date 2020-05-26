#flask-covid website

A web application developed with the [Flask] framework.

- URL creation
- Configuration of the Covid 19 API
- Authentication with sessions
- Model and model inheritance
- Error handling
- Integration with * Bootstrap *
- Interaction with the database (SQLite)
- Call for static resources

For a more basic knowledge of Flask, you can refer to [a PDF Drive book] (1)

## How to execute
- Step 1: make sure that the Python * flask *, * hashlib * and * sqlite3 * packages are installed.
- Step 2: Go to the directory of this application and run `python app.py`

## Details on this App

There are three tabs in this app

- ** Take the Test (ctest) **: this is a page with a form for diagnosing potentials infected with Covid 19. 
It is accessible to everyone, whether the user has logged in or not.

- ** Covid View SN (public) **: it is a page which presents the statistics of the confirmed, cured and deceased cases 
of covid 19 in Senegal and in the world. This page uses covid19api (2) from KYLE REDELINGHUYS (3).

- ** Macky Sall (contact) **: Message to the Nation from President Macky Sall of May 11, 2020.Page accessible to all,
 whether the user has logged in or not.

- ** Private (private) **: A page allowing to record notes and load images. Only the logged in user can access 
this page. Otherwise, the user will get a 401 error page.

- ** Dashboard (admin) **: This part is only open to the user who has logged in as "Admin". In this tab, 
the administrator can manage the accounts (list, delete or add).


Some accounts have been defined for the tests, such as *** admin *** (password: admin),
 *** test *** (password: 123456), etc. You can also delete or add accounts after logging in as * ** administrator ***.


## References
-1 https://buff.ly/2LQuvXu
-2 https://covid19api.com/
-3 https://ksred.me/
- https://github.com/sabiarist