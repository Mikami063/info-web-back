# info-web-back

how to start develop and debug on this project:

all the command below is for terminal on mac or linux, i'm not sure about windows, maybe install a bash.

make sure you have python3 installed and properly linked to terminal

cd into the outer AUI folder:
```
pipenv install
```
(install dependent packages for this specific project, seperate from the global packages, to avoid mess if working on multiple project)
```
pipenv shell
```
(to active seperate environment to store dependencies)

```
python3 manage.py runserver
```
(start running server on localhost, instruction will be shown on the terminal)

i do strongly encourage people to watch tutorial below to get idea on basis of working on a django project

https://www.youtube.com/watch?v=rHux0gMZ3Eg
