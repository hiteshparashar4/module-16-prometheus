# module-16-prometheus

## Note: To save cloud cost, I am creating it on an Ubuntu VM

## Create namespace first, then create the online shop microservices resources.
- <img width="1499" height="757" alt="p1" src="https://github.com/user-attachments/assets/e1e911ff-29d5-4140-a447-09c91b9fc878" />
- Verify if all the pods are online
- <img width="800" height="334" alt="p2" src="https://github.com/user-attachments/assets/99b946fc-613b-4e16-8f04-c43311622e8e" />
- Download and install helm
- <img width="1317" height="189" alt="p3 1" src="https://github.com/user-attachments/assets/618f66f9-8bb8-4073-bf49-5b18e95097fb" />
- Add Promethus repo and update repo
- <img width="1211" height="182" alt="p3" src="https://github.com/user-attachments/assets/492d1885-c7a3-4dad-baa7-02051abd4287" />

## Create namespace monitoring
- <img width="1451" height="730" alt="p4" src="https://github.com/user-attachments/assets/24a9e147-3822-42f5-beee-c8ac412721b0" />
- Check running pods
- <img width="1151" height="129" alt="p6" src="https://github.com/user-attachments/assets/461e5f95-1e63-4223-bbae-c6cd024b741c" />
- <img width="966" height="156" alt="p7" src="https://github.com/user-attachments/assets/3012a815-3e9e-4714-a89c-4544ec4266a4" />

## Forward port
- <img width="1530" height="251" alt="p8" src="https://github.com/user-attachments/assets/d67af325-ce4a-4084-afc3-a44a668ce46d" />

## Open Prometheus dashboard
- <img width="1916" height="511" alt="p9" src="https://github.com/user-attachments/assets/12c0eddb-8fd2-41eb-9bdc-d8c2532d4eed" />
- <img width="1909" height="891" alt="p10" src="https://github.com/user-attachments/assets/90694f29-4a54-4d13-a9fe-4e50aefd78b3" />

## Forward port
- <img width="1167" height="291" alt="p11" src="https://github.com/user-attachments/assets/a69b6ef3-4bfa-409e-8522-fc5b445e161f" />

## Open Grafana dashboard - invalid password
- <img width="993" height="778" alt="p12" src="https://github.com/user-attachments/assets/e221288a-7e03-4666-9bcd-68fc88fb4ae1" />
- As per the video the password is `prom-operator` but that password kept giving me error. So I had to look for the actual password myeslf.

## Find correct password
- <img width="1726" height="110" alt="p13" src="https://github.com/user-attachments/assets/cb513d2c-aaa5-4919-91fa-005cbb1de920" />
- Use that password
- <img width="968" height="713" alt="p14" src="https://github.com/user-attachments/assets/0cc1793e-f503-468d-8f10-8433ba293bdb" />

## Open Grafana  dahboard - valid password
- <img width="1911" height="818" alt="p15" src="https://github.com/user-attachments/assets/efa4b52d-54fe-405c-b2b9-cade5e193b5d" />
- <img width="1883" height="661" alt="p16" src="https://github.com/user-attachments/assets/dd71064b-08c3-419b-b7e8-45875e2654cb" />

