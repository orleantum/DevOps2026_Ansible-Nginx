### Проброс портов:

<img width="720" height="344" alt="image" src="https://github.com/user-attachments/assets/6a895485-1230-4d48-83f9-816108ace7c3" />




### Коммент строки вызова скрипта погоды на обеих ВМ:

```Bash
crontab -e
```


### Генерация ssh-ключа на 1-ой ВМ:

<img width="965" height="402" alt="image" src="https://github.com/user-attachments/assets/4664cd57-a96c-4c69-a4e3-738c64fb6462" />



### Проверка подключения с 1-ой ВМ на 2-ую.

<img width="810" height="520" alt="image" src="https://github.com/user-attachments/assets/eb43f834-fb23-470d-b2ba-9415ccdb3e32" />



### Смена названий ВМ чтобы не путаться:

```Bash
sudo hostnamectl set-hostname Ubuntu1
sudo hostnamectl set-hostname Ubuntu2
sudo nano /etc/hosts
sudo reboot
```


### На Ubuntu1

```Bash
sudo apt install Ansible
```

<img width="1056" height="269" alt="image" src="https://github.com/user-attachments/assets/4c33bfb7-1fbb-47ef-94e7-faee659e2609" />


`inventory.yml`:
<img width="649" height="124" alt="image" src="https://github.com/user-attachments/assets/2676555c-bd37-4fe3-b4e6-c3980bc77d6c" />


`playbook.yml`:
<img width="359" height="280" alt="image" src="https://github.com/user-attachments/assets/5eed3e01-df82-4cd6-8d86-b1bbb2e5b2f9" />



### Первый запуск с `--check`:

<img width="1117" height="286" alt="image" src="https://github.com/user-attachments/assets/830df7a2-2573-4292-9b1a-ef51e7655ab5" />



### Реальный запуск:

<img width="1118" height="294" alt="image" src="https://github.com/user-attachments/assets/8f3c1731-e4d3-486a-98c1-c988d32031f6" />



### Копирование `index.html`:

<img width="1125" height="349" alt="image" src="https://github.com/user-attachments/assets/c06f6871-83ed-4db4-bed9-a17bbf188ae7" />


### Проверка:
<img width="490" height="119" alt="image" src="https://github.com/user-attachments/assets/2a278153-63ba-43da-8b9a-0445d459cdfd" />


<img width="446" height="115" alt="image" src="https://github.com/user-attachments/assets/f38154ec-b249-4b11-a438-71d777fa9712" />
