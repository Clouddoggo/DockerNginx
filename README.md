# Instructions to run

## Run using source code

1. Clone this repository

 `git clone https://github.com/Clouddoggo/OTOT-Task-A.git`
2. Build the image and tag it with any tag you want. In this example, the tag 3219-Task-A is used.

 `docker build -t 3219-Task-A`
3. Run the image with a name, and expose port number 80. In this example, the name 3219-Task-A is used.

 `docker run --name 3219-Task-A -p 80:80 --rm 3219-task-a`
4. Go to http://localhost or http://localhost:80. The contents of the file `index.html` should be rendered
