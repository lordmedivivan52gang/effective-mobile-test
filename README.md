# Тестовое задание: Nginx + Backend

## Как запустить проект

1. Убедитесь, что установлены Docker и Docker Compose:
   ```bash
   docker --version
   docker-compose --version

2. Клонируйте репозиторий 
    git clone https://github.com/lordmedivivan52gang/effective-mobile-test.git
    cd ~/project

3. Запустите проект
    docker-compose up -d

4. Проверьте что контейнеры запустились
    docker-compose ps

5. Как проверить результат
    curl http://localhost
    Ожидаемый ответ : Hello from Effective Mobile!
