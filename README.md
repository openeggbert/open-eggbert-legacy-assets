# Open Eggbert Data

select count(*),lower(name), HASH_SUM_VALUE from file  group by HASH_SUM_VALUE, lower(name)

