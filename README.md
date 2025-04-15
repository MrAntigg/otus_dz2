В результате выполнения задания:
- через docker была развернута Victoria Metrics
- в prometheus настроен remote-write в Victoria Metrics с указание label site=prod
- в docker-compose.yml для контейнера Victoria Metrics заданые параметры запуска, отвечающие за место и период хранения 