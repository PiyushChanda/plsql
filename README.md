# plsql
Oracle PL/SQL
Oracle 11g Express Edition

SYS and SYSTEM are two users that are created by default

Code reusability/modularity/Network Traffic/System Defined Error Message, OOP

PL/SQL has support for OOP/Security/Packages/Modular Programming/Public/Private access specifier

DECLARE
-- GLOBAL VARIABLE
<VARIABLES, CURSORS, SUBPROGRAMS>
<VAR NAME> <DATATYPE> := <DEFAULT VALUE>
<VAR NAME> <OPT. CONSTANT> <DATATYPE> DEFAULT <DEFAULT VALUE>
BEGIN
<VAR NAME> := <VALUE>
dbms_output.put_line()

declare
begin
end

EXCEPTION

END;

--
/*

*/

if count > 100
then
statement
else
statement
elsif
statement;
end if;

CASE
WHEN <CONDTION>
  THEN
  <STATEMENT>
WHEN <CONDITION>
  THEN
  <STATEMENT>
ELSE
  <STATEMENT>
END CASE

WHILE CNTR<20
LOOP
dbms_output.put_line('VALUE OF CNTR' || CNTR)
CNTR := CNTR + 1
END LOOP;

FOR CNTR IN reverse 1..10 -- Inclusive of 1 and 10
LOOP
dbms_output.put_line('value of CNTR' || CNTR)

DECLARE
a NUMBER;
b VARCHAR2(10);


customer_id <tablename>.<columnname>%type - Application Independence
named code - procedures
  NEVER SPECIFY TH LENGTH OF THE DATATYPE IN THE INPUT PARAMETER
  
  VARCHAR -- CORRECT
  VARCHAR(10) --INCORRECT
  <PARAMETER> => 15,
  RETURNS TO THE ENVIRONMENT IN WHICH IT IS CALLED
  RETURN DATATYPE
  RETURN EXPRESSION
