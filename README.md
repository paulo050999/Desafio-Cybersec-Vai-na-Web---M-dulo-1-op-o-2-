# Desafio Cybersec Vai na Web Módulo-1 (opção 2)

# Projeto de Rede Corporativa – Cliente Fictício S/A

Este repositório apresenta o projeto teórico de arquitetura de rede corporativa desenvolvido como parte de um curso de Cibersegurança. O cenário é baseado em uma empresa fictícia do setor financeiro com três localidades (Matriz em SP, filiais no RJ e MG), visando segurança, segmentação e controle de acesso.

## 🌐 Estrutura Geral

- **Matriz São Paulo**:
  - 80 colaboradores
  - 6 VLANs (departamentais + visitantes + servidores)
  - Conectividade com internet e integração com sistemas em nuvem
  - VPN com as filiais

- **Filial Rio de Janeiro**:
  - 30 colaboradores
  - 6 VLANs (mesmas da matriz, adaptadas)
  - VPN site-to-site com a matriz

- **Filial Minas Gerais**:
  - 10 colaboradores
  - 3 VLANs (interna, infraestrutura e visitantes)
  - VPN com a matriz

## 🔐 Tecnologias e Conceitos Aplicados

- VLANs por departamento
- Isolamento de visitantes (Wi-Fi separado)
- Servidores locais em SP e RJ
- Firewalls entre roteador e LAN
- VPNs site-to-site para comunicação segura
- Segmentação da rede para limitar propagação de ameaças

## 📁 Estrutura do Repositório

├── diagramas/
│ ├── diagrama-rede-matriz-sp e filial rj.png
│ ├── diagrama-rede-filial-mg.png
│ └── diagrama-imgem-completa.png
│ └── diagrama.pdf
├── documentos/
│ ├── VAI NA WEB - CYBERSEC.pdf
├── README.md

## 🧠 Autor

Este projeto foi desenvolvido por Paulo Douglas Wanderley Bezerra como conclusão do 1° Módulo do curso do primeiro módulo do curso de Cibersegurança. 
