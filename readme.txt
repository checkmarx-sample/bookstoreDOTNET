1.	Extract zip into <BS-FOLDER>
2.	DB Configuration (SQL Server / SQL Express)
	a.	Create new DB and call it 'bs'
	b.	Select this db in SQL management studio and click on 'New Query'
	c.	Open file <BS-FOLDER>\SQL\BookStore_MSSQL.sql and copy all its contents into SQL management studio
	d.	Run the script
	e.	Update the attributes of the connection string in <BS-FOLDER>\Web.config (Source, User, Password, ...)
3.	IIS configuration
	a.	Open IIS management studio, click on Default Web Site and 'Add application'
	b.	Call it bookstore and map to <BS-FOLDER>
	c.	Select bookstore, click on contents view tab and browse default.aspx
