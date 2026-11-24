# Projetos de Rede

## Repetidor com redes separadas
- Objetivo: Separar rede da diretoria e visitantes
- Equipamento: [Huawei/LinkSys]
- Configuração:
  - Rede 1 (Diretoria): SSID "Home Sweet Home", faixa 192.168.1.0/24, DHCP automático
  - Rede 2 (Visitantes): SSID "Visitas", faixa 192.168.2.0/24, DHCP automático
- Resultado: Tráfego isolado entre as duas redes

## Criação de subredes
- Objetivo: separar VoIP de dados
- Subredes: 192.168.10.0/24, 192.168.20.0/24
- Máscara: 255.255.255.0  
