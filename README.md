# otus-lab-datacenter



#### spine: 
labsw01 labsw02  ASN:65001

#### leaf: 
##### labsw03 labsw04   ASN:65003
##### labsw05 labsw06   ASN:65004

### IP адресация
labsw01
|Device|Interface|IP Address|Subnet Mask
|---|---|---|---|
labsw01|mgmt|192.168.1.1|255.255.255.0
labsw01|Loopback0|198.18.10.1|255.255.255.255
labsw01|1/0/3|198.18.113.1|255.255.255.252
labsw01|1/0/4|198.18.114.1|255.255.255.252
labsw01|1/0/5|198.18.115.1|255.255.255.252
labsw01|1/0/6|198.18.116.1|255.255.255.252

labsw02
|Device|Interface|IP Address|Subnet Mask
|---|---|---|---|
labsw02|mgmt|192.168.1.2|255.255.255.0
labsw02|Loopback0|198.18.10.2|255.255.255.255
labsw02|1/0/3|198.18.123.1|255.255.255.252
labsw02|1/0/4|198.18.124.1|255.255.255.252
labsw02|1/0/5|198.18.125.1|255.255.255.252
labsw02|1/0/6|198.18.126.1|255.255.255.252

labsw03
|Device|Interface|IP Address|Subnet Mask
|---|---|---|---|
labsw03|mgmt|192.168.1.3|255.255.255.0
labsw03|Loopback0|198.18.30.1|255.255.255.255
labsw03|Loopback1|198.18.31.1|255.255.255.255
labsw03|vlan4093|198.18.134.1|255.255.255.252
labsw03|1/0/1|198.18.113.2|255.255.255.252
labsw03|1/0/2|198.18.123.2|255.255.255.252

labsw04
|Device|Interface|IP Address|Subnet Mask
|---|---|---|---|
labsw04|mgmt|192.168.1.4|255.255.255.0
labsw04|Loopback0|198.18.30.2|255.255.255.255
labsw04|Loopback1|198.18.31.1|255.255.255.255
labsw04|vlan4093|198.18.134.2|255.255.255.252
labsw04|1/0/1|198.18.114.2|255.255.255.252
labsw04|1/0/2|198.18.124.2|255.255.255.252

labsw05
|Device|Interface|IP Address|Subnet Mask
|---|---|---|---|
labsw05|mgmt|192.168.1.5|255.255.255.0
labsw05|Loopback0|198.18.50.1|255.255.255.255
labsw05|Loopback1|198.18.51.1|255.255.255.255
labsw05|vlan4093|198.18.156.1|255.255.255.252
labsw05|1/0/1|198.18.115.2|255.255.255.252
labsw05|1/0/2|198.18.125.2|255.255.255.252

labsw06
|Device|Interface|IP Address|Subnet Mask
|---|---|---|---|
labsw06|mgmt|192.168.1.6|255.255.255.0
labsw06|Loopback0|198.18.50.1|255.255.255.255
labsw06|Loopback1|198.18.51.2|255.255.255.255
labsw06|vlan4093|198.18.156.2|255.255.255.252
labsw06|1/0/1|198.18.116.2|255.255.255.252
labsw06|1/0/2|198.18.126.2|255.255.255.252




Схема лабораторного стенда:

![image](https://github.com/user-attachments/assets/3f4b4784-ae5f-4b6b-8756-550eecaee59b)

