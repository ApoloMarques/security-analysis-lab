# Relatório de Análise de Vulnerabilidades e Hardening – Ambiente Windows e Rede Local

## 📌 Descrição

Projeto técnico de análise de vulnerabilidades e hardening realizado em ambiente Windows e rede local (LAN), com foco na identificação de portas expostas, serviços inseguros e configurações inadequadas de segurança.

O projeto foi desenvolvido com base nas boas práticas dos CIS Critical Security Controls (CIS Controls), visando demonstrar processos de identificação, mitigação e validação de vulnerabilidades em infraestrutura local.

---

## 🎯 Objetivos

- Identificar vulnerabilidades em ambiente Windows e rede local
- Realizar análise de portas e serviços expostos
- Avaliar configurações inseguras no roteador
- Aplicar medidas de hardening
- Validar as correções implementadas

---

## 🛠 Ferramentas Utilizadas

- Nmap
- OpenVAS
- Windows
- Roteador Wi-Fi / Rede LAN

---

## 🔎 Vulnerabilidades Identificadas

Durante a análise, foram identificadas portas e serviços expostos:

- 135/tcp – MSRPC
- 139/tcp – NetBIOS
- 445/tcp – SMB
- 2179/tcp – RDP Hyper-V
- 16992/tcp – Intel AMT

Também foram identificadas configurações inseguras na rede local e no roteador.

---

## 🔐 Medidas de Hardening Aplicadas

- Fechamento das portas identificadas
- Desativação do WPS
- Desativação de gerenciamento remoto
- Ativação de firewall
- Ativação de isolamento AP
- Configuração de criptografia Wi-Fi
- Alteração da senha do roteador
- Aplicação de controles de segurança na rede

---

## 📚 CIS Controls Relacionados

- CIS Control 4 – Secure Configuration
- CIS Control 5 – Account Management
- CIS Control 6 – Access Control Management
- CIS Control 7 – Continuous Vulnerability Management
- CIS Control 8 – Audit Log Management
- CIS Control 12 – Network Infrastructure Management

---

## 📄 Estrutura do Projeto

- Relatório Executivo
- Relatório Técnico
- Estatísticas de Criticidade
- Evidências Técnicas
- Hardening e Mitigação
- Conclusão Final

---

## ⚠️ Aviso

Este projeto possui finalidade exclusivamente educacional e demonstrativa, voltado para estudos e práticas de segurança da informação em ambiente controlado.

---
