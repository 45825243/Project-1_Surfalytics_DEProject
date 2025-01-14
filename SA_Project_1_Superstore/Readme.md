# Project № 1

## Week 1

### Tasks
1. Create a GitHub repo
2. Add Readme.md file with info about the project using VSCode (create branch before PR)

### Solution
###### Task 1 
- Repo "Project-1_Surfalytics_DEProject" was created without Readme.md file
###### Task 2
- create a folder and a file "Readme.md"
- `git init` to start a process
- `git remote add origin https://github.com/45825243/Project-1_Surfalytics_DEProject.git` to connect our VSCode to our repo on GitHub
- `git checkout -b vlad/project1SA` create a new branch to work with
- Fill in our readme file with the info
- `git add .` add all files to commit
- `git commit -m "what was done"` write and commit what we have done in this commotment
- `git push origin vlad/project1SA` all files are in our github repo now
- `git status` and `git branch` we're using to track our progress and make sure we work in a right branch
---
## Week 2

### Tasks
1. Add a dataset into Git, create `folder` data and inside put a file or files
2. Ingest data into Azure Postgres (our Data Warehouse). Connect to PostgreSQL using DBeaver.

### Solution
###### Task 1
- `git clone <link>` we got Superstore dataset we'll work with
- In VSCode create a folder "data" and put our dataset there
- We have 3 .csv files. Rename them to Orders, People, Returns
###### Task 2
- Install DBeaver with default setting
  - In connestion settings click on PostgreSQL, next we need to set up our connection details. This information was given by my supervisor
  - Test connection shows details (successful/fail)
- Create a new database (screenshot #1)
- In this database create a new schema `STG`

![Creating a new database in DBeaver](images/DBeaver_new_database.jpg)








## Cheatsheet .md
```sh
# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня
#### Заголовок четвертого уровня
##### Заголовок пятого уровня
###### Заголовок шестого уровня
**полужирный**
*курсив*
***жирный и курсив***
1. Первый пункт
2. Второй пункт
3. Третий пункт
- Пункт 1
- Пункт 2
  - Подпункт 2.1
  - Подпункт 2.2
Link - [текст ссылки](URL)
Picture - ![альтернативный текст](URL_изображения)
Quote - > Это цитата.
Code `код`
Code many lines ```sh ``` 
Table 
| Заголовок 1 | Заголовок 2 |
|-------------|-------------|
| Строка 1, Ячейка 1 | Строка 1, Ячейка 2 |
| Строка 2, Ячейка 1 | Строка 2, Ячейка 2 |
Line ---

```









