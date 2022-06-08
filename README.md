# Tugas-Akhir-AJT-TKOM-A-Ardi-Rahardian
Ardi Rahardian

195150307111045

Arsitektur Jaringan Terkini - Teknik Komputer A

## Tugas 1 - Membuat Instance dan Instalasi OpenFlow, Mininet dan Ryu
![image](https://user-images.githubusercontent.com/99635519/172621685-8fb1275c-0804-41de-a7fb-050e394b6bec.png)
![image](https://user-images.githubusercontent.com/99635519/172621834-8cd57adb-4491-402d-9a1f-6ae80df17fd7.png)

Membuat instance dengan ketentuan :

Name and tags: Tugas Akhir

OS Images: Ubuntu Server 22.04 LTS 64 bit

Instance type: t2.medium

Key pair: vockey

Edit Network settings: allow SSH, allow HTTP, allow HTTPS, allow TCP port 8080, allow TCP port 8081

Configure storage: 30 GiB, gp3

![image](https://user-images.githubusercontent.com/99635519/172622073-c3465a51-cc66-44a0-bc01-c8b8b5fec57e.png)

Memastikan Mininet, Ryu, Flowmanager dan OpenFlow telah ter-install dan uji koneksi antara host dan switch

![image](https://user-images.githubusercontent.com/99635519/172622138-021549a5-156d-4588-a6e9-22759019f9c7.png)

Menguji perintah sederhana Mininet (help)

![image](https://user-images.githubusercontent.com/99635519/172622529-d54afd74-b71d-44ac-a1e2-638edb19f2fa.png)

## Tugas 2 - Mininet Custom Topology
![image](https://user-images.githubusercontent.com/99635519/172622749-1382c144-c9b5-4d50-9605-a895781319d5.png)

Pada tugas 2 ini, saya ditugaskan untuk membuat sebuah custom topology, lalu dilanjutkan dengan membuat flow antara host 1 dengan host 2 dan diuji koneksinya

## Tugas 3 - Ryu Load Balancer 
![image](https://user-images.githubusercontent.com/99635519/172622827-2ef12734-a40a-4648-b571-3bfb511d476b.png)

![image](https://user-images.githubusercontent.com/99635519/172622885-81e9190a-de96-4cb5-bbf9-0bb0777ca8ed.png)


![image](https://user-images.githubusercontent.com/99635519/172622910-64c48533-beee-43df-a849-9760f02262ec.png)

Pada tugas 3 ini, saya ditugaskan untuk membuat sebuah load balancer, yang merupakan proses pembagian beban traffic pada sebuah aplikasi atau server. Dengan adanya load balancer, beban traffic tidak akan dibebankan ke beberapa jalur koneksi, sehingga keseluruhan pemrosesan menjadi lebih cepat dan efisien serta mencegahnya dari overloading.

## Tugas 4 - Shortest Path Routing
Tampilan Terminal 1 : 

![image](https://user-images.githubusercontent.com/99635519/172623152-6bfb5e29-1c75-4062-a4ca-4b0e2b8ee632.png)

![image](https://user-images.githubusercontent.com/99635519/172623173-8f4d3ccd-8ff7-4737-9e26-3edaa76794a0.png)

![image](https://user-images.githubusercontent.com/99635519/172623196-7eafda5c-f043-4d0e-9fe9-4bfb8336368e.png)

Tampilan Terminal 2 :

![image](https://user-images.githubusercontent.com/99635519/172623503-2a85731d-bce8-4d67-b923-140c0c49c9a3.png)

Pengujian koneksi (h1 ping -c 4 h4)

Tampilan terminal 1 :

![image](https://user-images.githubusercontent.com/99635519/172623580-ae573499-9816-43dd-9cd5-2267a058734a.png)

Tampilan terminal 2 :

![image](https://user-images.githubusercontent.com/99635519/172623645-622f4fae-394a-4471-8fa2-3dc34383a28b.png)

Pengujian koneksi (h5 ping -c 4 h6)

Tampilan terminal 1 :

![image](https://user-images.githubusercontent.com/99635519/172623755-260908ca-fb2a-4cae-b796-a6f2eb71f8ba.png)

Tampilan terminal 2 :

![image](https://user-images.githubusercontent.com/99635519/172623815-9cd0d67e-a71e-4028-92d6-81f10de87297.png)

Pada tugas 4 ini, kita diajarkan tentang cara pengaplikasian SPF Routing, yang merupakan algoritma routing di mana router menghitung jalur terpendek antara setiap pasangan node yang terdapat di dalam jaringan. Protokol Open Shortest Path First (OSPF) dibuat berdasarkan algoritma Shortest Path First (SPF)
