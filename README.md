# Домашнее задание к занятию 10.1 «Keepalived/vrrp» - `Мальцев Виктор`

---

Задание 1

Разверните топологию из лекции и выполните установку и настройку сервиса Keepalived.

vrrp_instance test {

state "name_mode"

interface "name_interface"

virtual_router_id "number id"

priority "number priority"

advert_int "number advert"

authentication {

auth_type "auth type"

auth_pass "password"

}

unicast_peer {

"ip address host"

}

virtual_ipaddress {

"ip address host" dev "interface" label "interface":vip

}

}



1) ![alt text](https://github.com/vmmaltsev/screnshot/blob/main/Screenshot_21.png)
2) ![alt text](https://github.com/vmmaltsev/screnshot/blob/main/Screenshot_22.png)
3) ![alt text](https://github.com/vmmaltsev/screnshot/blob/main/Screenshot_23.png)
4) ![alt text](https://github.com/vmmaltsev/screnshot/blob/main/Screenshot_24.png)
5) ![alt text](https://github.com/vmmaltsev/screnshot/blob/main/Screenshot_25.png)
6) ![alt text](https://github.com/vmmaltsev/screnshot/blob/main/Screenshot_26.png)

---

