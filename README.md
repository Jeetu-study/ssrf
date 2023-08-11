# 1 Basic SSRF against the local server

***Stock feature has ssrf vulnerbulity when i putted http://localhost/admin/delete?username=carlos on stockApi= perameters i got successfully ssrf vulnerbulity***

![image](https://github.com/Jeetu-study/ssrf/assets/132050251/fc65d923-cacd-40d5-852a-b0215ec8c747)


# 2 Basic SSRF against another back-end system

***In this lab stock feature per stockApi=http://192.168.0.1:8080/product/stock/check?productId=1&storeId=1 internal ip address show hora tha jiske upper stock feature ki details show hori thi.. to socho agar hum last byte ko brute force kre to possible hai ki hum ek valid output ko paa sake the i did used intuder tab for brute force attack.***

![image](https://github.com/Jeetu-study/ssrf/assets/132050251/eb95314f-a92a-413e-827f-0dc6dd912060)

***and 225 per mujhe ek valid output laga then i try 192.168.0.225:8080  and i got admin panel then i deleted carlos user***

![image](https://github.com/Jeetu-study/ssrf/assets/132050251/a97e5d52-6784-485b-a6c5-8fe0a7922aff)


# 3 Blind SSRF with out-of-band detection

***In this lab Referer header ke upper burp collabrater ka payload dala and ping back hua DNS OR HTTPS and lab solved***

![image](https://github.com/Jeetu-study/ssrf/assets/132050251/0d0da51f-e504-411e-b8ed-b494a5e82990)

![image](https://github.com/Jeetu-study/ssrf/assets/132050251/d3e01972-8f03-4fbb-b4f1-81107d29d1a8)



