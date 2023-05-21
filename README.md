## Portainer and Traefik Setup

Этот репозиторий содержит инструкции по развертыванию Portainer и Traefik с помощью Docker.

### Репозиторий

GitHub: https://github.com/Romaxa55/portainer.git

### Файлы

1. `.gitignore` - Игнорируемые файлы Git.
2. `docker-compose.yml` - Файл конфигурации Docker Compose.
3. `start.sh` - Скрипт для запуска развертывания Docker.
4. `.idea` - Файлы конфигурации IDE (если вы используете JetBrains IDE).
5. `.git` - Папка Git для контроля версий.

### Использование

1. Клонируйте репозиторий на свой компьютер.

```bash
git clone https://github.com/Romaxa55/portainer.git
```

2. Перейдите в директорию проекта.

```bash
cd portainer
```

3. Запустите скрипт start.sh.

```bash
bash start.sh
```

*Примечание*: Вам может потребоваться предоставить скрипту `start.sh` права на выполнение. Вы можете сделать это с помощью команды `chmod +x start.sh`.

### Настройка
- Для настройки приложения измените переменные в docker-compose.yml.
- Токен API Cloudflare (CF_DNS_API_TOKEN) должен быть установлен через переменную среды CF_API_KEY.

### Обслуживание
- Для проверки состояния своих сервисов используйте команды Docker и Docker Compose.
- Посмотреть логи можно с помощью команды docker logs.

### Безопасность
Помните, что важно хранить свои секретные ключи в безопасном месте и не коммитить их в репозиторий. Если вы случайно это сделали, измените их как можно скорее.

### Поддержка
Если у вас возникли вопросы или проблемы, создайте вопрос в этом репозитории.

Спасибо за использование Portainer и Traefik!