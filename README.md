# shporgalka demo2024
Чтобы выполнить задание, нужно назначить и подсчитать IP-адреса для различных устройств в сети. В задаче сказано:

1. Для сети офисов BRANCH нужно не более 16 адресов.
2. Для сети офисов HQ нужно не более 64 адресов.

### Назначение IP-адресов (IPv4)

Предположим, что сеть у нас с IP-адресом 192.168.1.0/24:

- Сеть офиса HQ: 192.168.1.0/26 (64 адреса)
  - 192.168.1.1 - 192.168.1.62
- Сеть офиса BRANCH: 192.168.1.64/28 (16 адресов)
  - 192.168.1.65-192.168.1.78

Теперь заполним таблицу:

### Таблица №1:

| Имя устройств | IPv4             | 
| --------------|:-----------------|
| CLI           | 192.168.1.65     | 
| ISP           | 192.168.1.66     | 
| HQ-R          | 192.168.1.1      | 
| HQ-SRV        | 192.168.1.2      | 
| BR-R          | 192.168.1.67     | 
| BR-SRV        | 192.168.1.68     | 
| HQ-CLI        | 192.168.1.3      | 
| HQ-AD         | 192.168.1.4      | 
