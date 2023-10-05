to run the site make sure that you have already installed sqlite database in your system if not installed than install it and add path in environment 

step 1:
download this zip file.

step 2:
extract this file.

step 3:
open extracted folder in any IDE such that app.py file path can be directly accecable in terminal of IDE.

step 4:
run following command in terminal.
pip install -r requirements.txt 

step 5:
if you want to have empty database perform following codes in terminal after deleting todo.db file.
from app import db
db.create_all() 
run belown code in terminal 

step 6:
else you can directly run python app.py in terminal.

