# Directory-Tree-Generator

**Install the requirements:**

    pip install walkdir
    
    python tree_gen.py.py -h
    usage: tree_gen.py.py [-h] [-d MAXDEPTH] [-H] [-S] path

    positional arguments:
      path                  Root directory of the tree

    optional arguments:
      -h, --help            show this help message and exit
      -d MAXDEPTH, --maxDepth MAXDEPTH
                            Max depth for the tree expansion
      -H, --includeHidden   Include hidden files
      -S, --includeSystem   Include system files
      
      
Output:
.1 {/home/user/djangoproject/djangoall-20210113T091003Z-001/djangoall/gs34} .
  .2 {db.sqlite3} .
  .2 {manage.py} .
  .2 {enroll} .
   .3 {\_\_init\_\_.py} .
   .3 {admin.py} .
   .3 {apps.py} .
   .3 {forms.py} .
   .3 {models.py} .
   .3 {tests.py} .
   .3 {views.py} .
   .3 {\_\_pycache\_\_} .
    .4 {\_\_init\_\_.cpython-36.pyc} .
    .4 {admin.cpython-36.pyc} .
    .4 {forms.cpython-36.pyc} .
    .4 {models.cpython-36.pyc} .
    .4 {views.cpython-36.pyc} .
   .3 {migrations} .
    .4 {\_\_init\_\_.py} .
   .3 {templates} .
  .2 {gs34} .
   .3 {\_\_init\_\_.py} .
   .3 {asgi.py} .
   .3 {settings.py} .
   .3 {urls.py} .
   .3 {wsgi.py} .
   .3 {\_\_pycache\_\_} .
    .4 {\_\_init\_\_.cpython-36.pyc} .
    .4 {settings.cpython-36.pyc} .
    .4 {urls.cpython-36.pyc} .
    .4 {wsgi.cpython-36.pyc} .

      

  
