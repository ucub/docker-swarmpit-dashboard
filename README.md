Source : https://github.com/swarmpit/swarmpit


1. Clone pada folder anda
```
git clone http://git.dinustek.com/yusufsanjaya/docker-swarmpit.git
```

2. Kemudian jalankan pada swarm manager leader dengan perintah
```
docker stack deploy -c swarmpit.yml swarmpit
```
3. Untuk custom port,bisa diedit pada bagian port apps ```ports: - port:port```
4. Kemudian buka pada dashboard pada masing-masing manager dengan akses ```http://{ip_address}:5001```
5. Buat User pada kedua dashboard.