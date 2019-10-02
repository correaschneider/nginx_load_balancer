Inicia a bagaça com uma instancia do PHP
docker-compose up --build -d

Aumenta as instancias de PHP
docker-compose up --scale meu_querido_servico_php=2 -d

Registrar as novas instancias no server.conf

Restart serviço do Load Balancer
docker-compose restar meu_querido_load_balancer