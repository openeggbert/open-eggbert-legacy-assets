# Open Eggbert Data

select count(*),lower(name), HASH_SUM_VALUE from file  group by HASH_SUM_VALUE, lower(name)

## How to convert BMP to PNG on Linux

for file in *.bmp; do convert "$file" "${file%.bmp}".png; done

