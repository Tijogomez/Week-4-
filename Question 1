import sqlite3
con = sqlite3.connect('car.db')
cur = con.cursor()
cur.execute("DROP TABLE IF EXISTS CAR_DETAILS")
query = """CREATE TABLE CAR_DETAILS(
         OWNERNAME CHAR(20) , 
         CARNAME CHAR(20) )"""
cur.execute(query)
con.execute("INSERT INTO CAR_DETAILS (OWNERNAME,CARNAME) "
                 "VALUES ('Tijo', 'Freestyle')")
con.execute("INSERT INTO CAR_DETAILS (OWNERNAME,CARNAME) "
                 "VALUES ('Benny', 'Fortuner')")
con.execute("INSERT INTO CAR_DETAILS (OWNERNAME,CARNAME) "
                 "VALUES ('Tina', 'Polo')")
con.execute("INSERT INTO CAR_DETAILS (OWNERNAME,CARNAME) "
                 "VALUES ('Dom', 'GT')")
con.execute("INSERT INTO CAR_DETAILS (OWNERNAME,CARNAME) "
                 "VALUES ('Emy', 'XUV')")
con.execute("INSERT INTO CAR_DETAILS (OWNERNAME,CARNAME) "
                 "VALUES ('Nita', 'Sclass')")
con.execute("INSERT INTO CAR_DETAILS (OWNERNAME,CARNAME) "
                 "VALUES ('Bevin', 'Tiago')")
con.execute("INSERT INTO CAR_DETAILS (OWNERNAME,CARNAME) "
                 "VALUES ('Awsathy', 'Pajero')")
con.execute("INSERT INTO CAR_DETAILS (OWNERNAME,CARNAME) "
                 "VALUES ('Sosi', 'Q40')")
con.execute("INSERT INTO CAR_DETAILS (OWNERNAME,CARNAME) "
                 "VALUES ('Cerin', 'City')")
con.commit()
cur = con.execute("SELECT * from CAR_DETAILS")
print(cur.fetchall())
con.close()
