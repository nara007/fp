**class User(db.Model):**  
&nbsp;&nbsp;&nbsp;&nbsp;\_\_tablename\_\_ = 'UserData'  
&nbsp;&nbsp;&nbsp;&nbsp;\_\_table_args\_\_ = {'mysql_charset': 'utf8',
                      'mysql_engine': 'InnoDB', 'mysql_collate': 'utf8_unicode_ci'}  
&nbsp;&nbsp;&nbsp;&nbsp;UserID = db.Column(db.String(64), primary_key=True)  
&nbsp;&nbsp;&nbsp;&nbsp;Username = db.Column(db.String(64), nullable=False)  
&nbsp;&nbsp;&nbsp;&nbsp;Password = db.Column(db.String(64))
&nbsp;&nbsp;&nbsp;&nbsp;PublicKey = db.Column(db.Text)
&nbsp;&nbsp;&nbsp;&nbsp;RegistrationDate = db.Column(db.DateTime, nullable=False)

**Relation UserData**  
**Columns:**  
&nbsp; **UserID**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; varchar(64)  
&nbsp; Username &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;varchar(64)  
&nbsp; Password &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;varchar(64)  
&nbsp; PublicKey &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;varchar(64)  
&nbsp; RegistrationDate &nbsp;&nbsp;varchar(64)  

             


