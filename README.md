# -first-job
Это моя первая работа в репозитории. Прошу сильно не ругаться.
В ansible-playbook описано создание мониторинга на основе Prometeus и Grafana. С дополнительной установкой node_exporter.
В файле "node_exporter.service.j2" описаны настройки unit systemd node_exporter. 
В файле описана "zadacha.yaml" установка всех компонетнов.
Примечание:  В "zadacha.yaml", на tasks:"Create systemd service file" измените путь копирования (откуда будет все копироваться):
src: "/home/danil/node_exporter.service.j2"

