##Run python script

Every python script has a .py extention.
Let's create our first "Hello world" programm.


    echo 'print "Hello World" ' > hello.py

To run it we need to execute 'python' command and put a script name as a first parameter.

    python hello.py

But there is another and more convenient way how to execute python script without mentioning 'python' in command line. 
Add this line at the begining of out script.

    #!/usr/bin/env python

Than mark the file as executable.

    chmod +x hello.py

Now we can run it just like that

    ./hello.py

###Execute string as python code.

    python -c "print 'Hello World!'"
    python -c "import sys; print sys.path"
    




