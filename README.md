# kubernetes
## Задание 2.2
## «Хранение в K8s. Часть 2»
1.
Данная часть выполнялась из kubernetes/deployment.yaml, kubernetes/pv.yaml, kubernetes/pvc.yaml
\
1.3
![Alt text](<Pasted Graphic 35.png>)
\
1.4 pv перешел в статус Released из-за того, что persistentVolumeReclaimPolicy со значением Retain
\
1.5 файл остался на ноде, за что также, как и в предыдущем пункте отвечает параметр Retain (после удаления PV ресурсы из внешних провайдеров не удаляются)
![Alt text](<Pasted Graphic 36.png>)
![Alt text](<Pasted Graphic 37.png>)
\
2. Данная часть выполнялась из kubernetes/deployment_sc.yaml kubernetes/pvc_sc.yaml
![Alt text](<Pasted Graphic 38.png>)