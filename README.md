# Da Criptografia Clássica ao BB84: Computação Quântica na Segurança da Informação

<img width="860" height="820" alt="image" src="https://github.com/user-attachments/assets/774c683f-569b-45b3-9523-27b8d256d3a5" />


📘 **Projeto Final – Computação Quântica**  
🏫 Faculdade de Ciências e Tecnologia da Universidade de Coimbra  
👨‍🎓 Leonardo Gonçalves (leoleocordeiro@gmail.com)  
👨‍🎓 Gonçalo Bastos (eusoudebastos@gmail.com)  
📅 Ano letivo: 2024/2025

---

## 📌 Descrição

Este repositório documenta a transição da **criptografia clássica** para a **criptografia quântica**, com foco nos protocolos **BB84** e **E91**, e no **algoritmo de Shor**, que ameaça os sistemas clássicos como o RSA.

O trabalho incluiu a **implementação e testes reais** com a plataforma IBM Quantum (Qiskit), explorando os desafios de execução prática, ruído, decoerência e limitações do hardware atual. Discutimos ainda a **criptografia pós-quântica** como abordagem complementar e as perspetivas futuras na construção de redes seguras em ambientes pós-clássicos.

---

## 🧠 Tópicos Abordados

- 📎 Criptografia clássica (RSA, fatorização)
- ⚡ Algoritmo de Shor (implementado em Qiskit)
- 🔐 Protocolo BB84 (QKD com simulações e testes em hardware real)
- 🧬 Protocolo E91 (QKD com entrelaçamento quântico)
- 🧪 Testes com e sem interferência (Eve)
- 🧠 Criptografia Pós-Quântica (lattices, códigos, assinaturas hash)
- 🚀 Perspetivas futuras e Internet Quântica

---

## 💡 Tecnologias Utilizadas

- 🧪 Qiskit (IBM Quantum)
- 🐍 Python 3
- 📈 Matplotlib, NumPy
- 💻 IBM Quantum Experience (backends: `ibm_quito`, `ibm_kyiv`)

---

## 🔭 Resultados

- Algoritmo de Shor implementado com sucesso (N = 15)
- Protocolo BB84 atingiu >96% de eficiência em ambiente ideal
- Testes em hardware real mostraram impacto de ruído e decoerência
- Simulações de ataque (Eve) impactaram a eficácia do BB84 e E91
- Integração dos conceitos com demonstrações práticas em dispositivos reais

---

## 🛡️ Discussão

Este projeto mostra que a segurança da informação está a entrar numa nova era. A criptografia baseada em leis da **mecânica quântica** é mais do que teoria — já é possível testar, validar e refletir sobre o seu potencial e limitações, em cenários reais.

---

## 📘 Licença

Distribuído apenas para fins académicos e educativos. Para uso comercial, contactar os autores.
