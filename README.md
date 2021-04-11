# quiz

Storing some of my Go exploration work from the Learn Go by Examples course.

# Flow of work...

To create a ``go.mod`` file, create a repo in github and clone it locally, then type:

``
go mod init github.com/dmottice20/name-of-project
``

# To run...

``
go build . && ./quiz -limit=time-limit
``

If you have a new .csv file you want to use, run...

``
go build. && -csv=file-name -limit=time-limit
``