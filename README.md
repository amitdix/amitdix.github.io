Oracle performance tunning blogs 
oracle performance tuning kellyn pot'vin 


ADDM ASH 

Real time ADDM - 

```
GRANT ALL ON t to user;
SET ECHO ON
SET SERVEROUTPUT ON
BEGIN 
  FOR i in 1..5234568 LOOP
  INSERT INTO t values (s.NEXTVAL, 'first');
  COMMIT;
  END LOOP;
END;
/
```
Cloud watch and SNS (Simple notification service)

VPC - Virtual private cloud - layer of security - To cut off any other connection - Resources have private IP address to communicate with each other

Subnet is inside VPC

AWS cloud formation - template to create resources

jps - process id of java apps

jmap -histo <pid> |less - object memory
