# Opis projektu
Plik Docker Compose generujący usługę LEMP wraz phpMyAdmin. Usługa składa się z 4 kontererów: Nginx, PHP-FPM, MySQL i phpMyAdmin.
# Treść plików
index.php, wyświetlający informacje o instalacji PHP </br>
<img src="screen1.png" alt="screen index.php" title="screen index.php">
</br> </br> 
default.conf, konfiguracja nginx </br> 
<img src="screen2.png" alt="screen default.conf" title="screen default.conf"> </br>  </br> 
docker-compose.yml </br>
<img src="screen3.png" alt="screen docker-compose.yml" title="screen docker-compose.yml"> </br>
<img src="screen4.png" alt="screen docker-compose.yml" title="screen docker-compose.yml"> </br></br> 

# Reprezentacja graficzna projektu </br>
<img src="docker-compose.png" alt="Reprezentacja graficzna projektu" title="Reprezentacja graficzna projektu"> </br>  </br> 

# Polecenie uruchamiające cały stack wraz z phpMyAdmin, utworzenie testowej bazy
sudo docker compose up -d </br>
baza zostaje stworzona dzięki konfiguracji "MYSQL_DATABASE: 'testdb'" w docker-compose.yml
