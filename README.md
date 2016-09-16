MTN.*NIX.11 Automated Environment Configuration Management
---

***Student***: [Uladzislau Charches](https://upsa.epam.com/workload/employeeView.do?employeeId=4060741400038705754#emplTab=general)

# Chef Task9

**1. I edited Vagrantfiles of 2 Vm. Run it with edited files "hosts". You can check its below**
**2. Created 3 recipes: web, web_nginx, web_apache **

**Knife bootstrap commands:**

- knife bootstrap 192.168.56.110 -N chefX -x root -P vagrant -r 'role[apache_web_server]' -E web_server_type |tee apache_bootstrap.log  
- knife bootstrap 192.168.56.115 -N chefX -x root -P vagrant -r 'role[nginx_web_server]' -E web_server_type |tee nginx_bootstrap.log 


Screenshots:

**Apache**

![1](https://github.com/VladCharches/Chef-courses/blob/Task9/screens/1.png)

**NginX**

![2](https://github.com/VladCharches/Chef-courses/blob/Task9/screens/2.png)
