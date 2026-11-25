# Watchdog de Certificados TLS/SSL

[![Escopo de Verificação Perimetral](https://img.shields.io/badge/TAVARDT-Diagn%C3%B3stico%20T%C3%A9cnico-5b3cf5.svg)](https://tools.tavardt.com/br/analise-cabecalhos-seguranca/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Monitoramento automatizado de expiração de certificados SSL/TLS, integridade de cadeia criptográfica e conformidade perimetral no Brasil.

***

## 1. Escopo de Verificação Perimetral

Este utilitário de terminal inspeciona em tempo real a validade, cifras e autoridades certificadoras de conexões seguras:

* **Alerta Preventivo de Expiração:** Calcula os dias restantes para o vencimento do certificado com alertas configuráveis.
* **Auditoria de Cifras e Protocolos:** Identifica o suporte a TLS 1.3 e assegura a desativação de protocolos obsoletos.
* **Validação de Autoridade Emissora (CA):** Inspeciona a entidade emissora da cadeia de confiança e integridade dos SANs.
* **Zero Dependências Externas:** Construído exclusivamente com os módulos nativos ssl e socket do Python.

***

## 2. Guia de Execução Rápida

Execute a ferramenta diretamente via Python sem necessidade de instalar dependências externas:

```bash
python watchdog.py exemplo.com.br
```

***

## 3. Ferramentas Técnicas Online (Brasil)

Audite a infraestrutura pública das suas aplicações utilizando a suíte de diagnósticos da TAVARDT:

* [Validador de Consent Mode v2 e LGPD](https://tools.tavardt.com/br/validador-consent-mode-v2-lgpd/)
* [Verificador DMARC e Segurança de E-mail](https://tools.tavardt.com/br/verificador-dmarc-email/)
* [Deteção de Arquivos Expostos](https://tools.tavardt.com/br/verificador-arquivos-expostos/)
* [Portal de Diagnóstico Técnico Brasil](https://tools.tavardt.com/br/)

***

## 4. Consultoria e Remediação Técnica

Para hardening criptográfico de servidores, automação de renovação e proteção corporativa no Brasil, contate a **TAVARDT**.

***

## Links Úteis

* **Portal Corporativo:** https://ag.tavardt.com/br/
* **Suíte de Diagnósticos:** https://tools.tavardt.com/br/
* **Contato Técnico:** https://ag.tavardt.com/br/contato/

***

### Licença
Distribuído sob a Licença MIT.

***

© 2026 TAVARDT. Todos os direitos reservados.
