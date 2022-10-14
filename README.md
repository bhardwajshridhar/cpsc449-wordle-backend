# CPSC 449 Group 22 Project 1
<p><b>Group Member:</b> Vu Diep, Jiu Lin, Shridhar Bhardwaj, Heet Savla<p/>

## Installations
<p>1. Install libraries needed</p>

```sh
python3 -m pip install databases[aiosqlite]
python3 -m pip install quart-schema
sudo apt install --yes python3-pip ruby-foreman sqlite3
python3 -m pip install --upgrade quart[dotenv] click markupsafe Jinja2
```
<p>2. Clone the repository</p>

```sh
git clone https://github.com/vudiep411/cpsc449-wordle-backend.git
```
<p>3. Setting up the database</p>

```sh
cd cpsc449-wordle-backend/
sqlite3 ./var/wordle.db < ./share/wordle.sql
```
<p>4. Start the server with foreman</p>

```sh
foreman start
```
> ⚠ The development server will be started at http://127.0.0.1:5000/

## Team member instructions
<p><b>Database people:</b> Create your schema in ./share/worldle.sql file</p>
<img src="https://firebasestorage.googleapis.com/v0/b/chatapp-be9bd.appspot.com/o/databasepeople.png?alt=media&token=efed70eb-5555-438c-97df-7afa0b3ec917" alt="database"/>

<p><b>Python people:</b> Write your api in wordle.py file</p>
<img alt="python" src="https://firebasestorage.googleapis.com/v0/b/chatapp-be9bd.appspot.com/o/pythonpeople.png?alt=media&token=e27a58cb-ecd2-45a5-8384-e58e654cd6cd"/>