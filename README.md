###### Make new branch
git branch develop

###### Switch to new branch
git checkout -b develop

###### Current branch
git branch

###### All list branchs
git branch -a

###### Add remote git
git remote add origin https://github.com/huutrinh68/eshop.git

###### Install library:
pip install django-compressor
pip install django-paypal
pip install django-oscar-paypal
###### Reference URL
http://akiyoko.hatenablog.jp/entry/2016/05/31/014711
https://qiita.com/ytyng/items/a4ae77df8bc4c5506d19

###### Add shipping country
pip install pycountry
./manage.py oscar_populate_countries

###### Run command:
./manage.py makemigrations
./manage.py migrate
./manage.py runserver

###### Test visa
http://www.getcreditcardnumbers.com

###### Show all tables in database
qlite3 db.sqlite3
.tables

###### Fake address
https://www.fakeaddressgenerator.com/World/us_address_generator

###### TODO
* add tax rate
* stripe
user: trinhsp89@gmail.com
pass: Nhatban2009
* show name country shipping

###### Install stripe
pip install stripe
