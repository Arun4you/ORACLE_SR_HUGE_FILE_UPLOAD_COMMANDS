# ORACLE_SR_HUGE_FILE_UPLOAD_COMMANDS
Uploading Hude files such as Heap dumps, Thread dumps in Oracle SR


COMMAND:
[grd@Myhost bin]$curl -T heap.tar.gz -o output_sr.txt -u [Oracle Registered Mail ID] https://transport.oracle.com/upload/issue/{SR number}

OUTPUT:
Enter host password for user '[Oracle Registered Mail ID]':
% Total % Received % Xferd Average Speed Time Time Time Current
Dload Upload Total Spent Left Speed
100 106M 0 12 100 106M 0 1651k 0:01:06 0:01:06 --:--:-- 1659k
