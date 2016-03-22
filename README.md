#Reference

#When faced with postgres issues

pg_ctl restart

mkdir ~/.postgres

initdb ~/.postgres

pg_ctl -D ~/.postgres start
