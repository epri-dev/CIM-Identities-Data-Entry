### CreateTable

This should be the first program run after installing PostgreSQL.  However, before running it, you will need to run the
driver file located at dist/lib/postgresql-9.2-1002.jdbc4.jar

After successfully running the driver file, run the CreateTable jar file located at CreateTable/dist/CreateTable.jar
This will prompt you for the password you set up for PostgreSql and upon successful password entry will create a
database with the following 5 tables:
 *  IdentifiedObject
 *  Identity
 *  Name
 *  NameType
 *  NameTypeAuthority

### DataEntryForm

Do not run this before running CreateTable.jar.  Navigate to the jar file located at DataEntryForm/dist/DataEntryForm.jar
When launched, it will prompt you for your password for PostgreSQL.  See "CIM Identities Data Entry Example Cases.pdf"
for examples of how to use the software to populate your database.