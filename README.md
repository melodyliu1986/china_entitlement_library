# china_entitlement_library

# Description

A Flask Web application used for on-line library.  

# Function Introduction

Search books     --  Search by book name.  
Advanced Search  --  Support search by book name, book category, owner and bought time.  
All Books        --  List all the books in library DB.  
Books Categories --  List books in library DB by categories.   
Book Wish List   --  List books that you want to buy.   
Best Sellers     --  If you don't know which books you want to buy, then you can refer to Best Seller List in Amazon or JD.

# Dependencies

pip install flask  
pip install wtforms   
pip install flask-wtf   
pip install flask-bootstrap

# Modules

library.py - Contains the app views.   
forms.py - Contains WTForms Form objects for use in views and templates.  
database/ - Library database writen by sqlite3.   
templates/ - Contains jinja2 templates.   
static/ - Contains imgs and .css files used in app.

# Running

python library.py
