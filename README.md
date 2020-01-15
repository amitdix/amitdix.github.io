Oracle performance tunning blogs 
oracle performance tuning kellyn pot'vin 


ADDM ASH 

Real time ADDM - 

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
