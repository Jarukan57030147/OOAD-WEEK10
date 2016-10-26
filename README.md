# OOAD-WEEK10
Sequence Diagram


README.md 

    *  รูปที่ 1 การซื้อขายเครื่องดนตรี
code


customers -> Owner : Greetings Instruments
customers -> Owner : Payment

customers <- Owner : Receipt

customers <- Owner : Receive product

Owner -> booksales : Death records

Owner -> product : Product Update


[![IMAGE ALT TEXT] (http://www.plantuml.com/plantuml/img/VOr12i9034NtFKKkq0k8k1B4bKNm06FcewNjP4Wo5MzlIukw47VXl_T_k9ZB03MgTtHw92XjwA20j-bcT4pcMWOajuf_gKruplGBRkitF8FHvdzm16MLMDYh9P-choATXHusINi4lvE2HQDzbBKp_r-lIux1yG80)





* รูปที่ 2 การขนส่งสินค้า

code 

salesman -> systemtransport : Order items

salesman <-- systemtransport : Items shipped

salesman -> systemtransport : Check Transport

salesman <-- systemtransport : Report a product review

ShippingStaff <-- systemtransport : Information Delivery

ShippingStaff -> systemtransport : Send shipping



[![IMAGE ALT TEXT] (http://www.plantuml.com/plantuml/img/XOz12i9034NtFKKkq0k8kD6DAy7n0g6JiS5EPaZ6IczlgnH1HjnzFY___nWEP145sXtOP8LYKHJBIGjiuAIU57XshR6LtBPj1Jqk45ZFEPF_mDNOVK_T3Iwhyo_wJ2-1a3NvUrT0QMHwD6ufOxcwWY7ycYKXQSJ2IU100u-aqzTXTQ8ZyUzlPku9)






* รูปที่ 3 การถามยอดเงินตู้ ATM

code


user -> ATMscreens : Enter the password

ATMscreens -> MyAccountInformation : GetBalance

ATMscreens <--  MyAccountInformation : ShowBal




[![IMAGE ALT TEXT](http://www.plantuml.com/plantuml/img/AorEBLBGjLDm3F4jJYvAJSqhLh1ISCqh0OgMPAGg52GM5vVd5wLm8Sa3LVjMEYOdvvVcbNZcfUKNvIQMPERd0VMvfvOu9UOavYMd8gktqTLLmAKZE2E_7AW50000)





* รูปที่ 4 การสั่งซื้อรองเท้าจากเว็บไซต์

code

customer -> SHOESWEB : Login

SHOESWEB -> shopowner : Get orders

customer -> ATM : payment

shopowner --> SHOESWEB : Information Delivery

shopowner --> customer : Delivery



[![IMAGE ALT TEXT](http://www.plantuml.com/plantuml/img/IoujBidFJIrIqBLJ2FRmTmqETtLIi5BmoK_FpEE22m0bYpFo2_BByu0ghHJSKqiKyejIKekAkPAHz3k6-08b2n8hSrFpIhWG6dHHpVRCIyiloaqioSpFKt19pSaiIosgH5CDDzKAhW80)





* รูปที่ 5 การโทรออก

code


caller -> Phone : pick up

caller <-- Phone : Dial tone

caller <-- Phone : Ring notification

Phone -> Recipient : ring

Recipient --> Phone : pick up



[![IMAGE ALT TEXT](http://www.plantuml.com/plantuml/img/IqxCoKajKj2rKmZ8oCzBLR1IACXCpbOeBU1AXiZOwEh2fLmo4tCKIe1iR991cNdf2ddv9PbfcSc99PdvULmG6Q3HGQd9cGMPgNabG6L5G6LS205TB3PpSG40)





