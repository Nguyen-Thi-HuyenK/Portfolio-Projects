# Portfolio-Projects

Hello there :wave:, thank you for stopping by! I am Huyen, and in this repository, I have documented a collection of small projects that I completed during my studies at OAMK so far.

| Projects | Language   |
| -----| ---------- |
|   Todo list  | TypeScript |
|   2  | Java       |
|   3  | Python     |

## I. Todo list

This is a very simple application written by Typescript, HTML, CSS (with form control and list group class from Bootstrap), and Mysql as a database. This is my first individual task in my first year at OAMK. The application allows users to add To-do tasks to the list. After entering the task, it will be saved to the database. Users can delete the tasks by clicking on the trash bin icon, and the task will then be removed from the UI as well as from the database.

### Run the application

This application includes 2 separate repositories for frontend and backend code. First of all, you should clone both repositories to your local machine, then install all needed dependencies by running the below command in the command line:
```bash
npm install
```
Link: [Backend repository](https://github.com/Nguyen-Thi-HuyenK/Todos-server), and start the server by running the below command in the command line:
```bash
npm run devStart
```
Link: [Frontend repository](https://github.com/Nguyen-Thi-HuyenK/Todos), and start the application by running the below command in the command line:
```bash
tsc -p tsconfig.json --watch
```
Then go to the browser to use the application via the address: http://localhost:5500/Todos/index.html   

