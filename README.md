# Gestão de Vulnerabilidades e Melhoria da Postura de Segurança - PoP-DF/RNP

## 📝 Introdução do Projeto
Este projeto detalha a implementação completa de um novo processo de Gestão de Vulnerabilidades realizado durante minha residência na **RNP (Rede Nacional de Ensino e Pesquisa) no PoP-DF**. O objetivo foi estruturar um ciclo contínuo que vai desde a varredura inicial até a remediação e verificação de conformidade, fortalecendo a postura defensiva da organização.

## 🛠️ Modelagem e Ferramentas
Para a construção deste ecossistema de segurança, foram utilizadas as seguintes tecnologias e metodologias:

* **Varredura e Mapeamento**: Utilização de **OpenVAS (Greenbone)**, **Nmap** e **Nessus** para identificação de ativos e superfícies de ataque.
* **Orquestração de Dados**: Implementação do **DefectDojo** para centralizar os achados e gerenciar o ciclo de vida das vulnerabilidades.
* **Priorização Técnica**: Análise baseada em frameworks globais como **CVSS**, **CWE** e **CVE**, garantindo que as falhas de maior impacto fossem corrigidas primeiro.
* **Compliance e Normas**: Alinhamento com os padrões internacionais **ISO 27001/27002** e as diretrizes do **NIST SP 800-115**.
* **Automação**: Desenvolvimento de scripts em **PowerShell** e **Bash** para otimizar a coleta de dados e aumentar a eficiência operacional.

## 🏆 Conclusão e Resultados
A implementação resultou em uma infraestrutura mais robusta e transparente, permitindo uma resposta rápida a ameaças emergentes. 
* **Resultados Chave**: Redução do risco residual através da correção focada em ativos críticos e automação de processos repetitivos de segurança.
* **Próximos Passos**: Como expansão futura, pretendo integrar este processo ao monitoramento em tempo real com **Wazuh (SIEM)** para uma visão ainda mais holística do ambiente.

---
*Projeto desenvolvido como parte da Residência em Cibersegurança no PoP-DF/RNP (2024-2025).*
