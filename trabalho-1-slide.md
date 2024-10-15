---
marp: true
theme: default
paginate: true
footer: 'Análise de Robôs Aspiradores de Pó com Sistemas Operacionais em Tempo Real'
---

# Análise de Robôs Aspiradores de Pó com Sistemas Operacionais em Tempo Real

## Juan Fricke, Gabriel Buron
### Unijuí, Curso de Ciência da Computação

---

# Abstract

Este artigo analisa a utilização de sistemas operacionais em tempo real (RTOS) em robôs aspiradores de pó, focando nas características técnicas desses dispositivos, nas vantagens proporcionadas pelo RTOS e nas implicações para a segurança e confiabilidade da operação.

---

# Introdução

Os robôs aspiradores de pó são sistemas embarcados que exigem precisão e eficiência no processamento de dados sensoriais para navegar em ambientes complexos e otimizar o processo de limpeza.

---

# Características Técnicas

- Sensores: infravermelhos, giroscópios
- Atuação: mobilidade, escovas, sistema de sucção
- Navegação:
  - Caminhada aleatória
  - SLAM visual
  - Scanners de laser

---

# Sistemas Operacionais em Tempo Real (RTOS)

- **RTOS** garantem a execução de tarefas críticas com prazos específicos
- Exemplo: **Nano-RK**
- Multitarefa preemptiva baseada em prioridades

---

# Hard e Soft Real-Time

- **Soft real-time**: variações temporais são toleráveis
- **Hard real-time**: falhas temporais resultam em danos críticos

---

# Sensores e Atuadores

- **Sensores**: obstáculos, quedas, sujeira
- **Atuadores**: rodas, escovas, sucção
- RTOS coordena sensores e atuadores em tempo real

---

# Segurança e Confiabilidade

- **RTOS**: garante execução de tarefas críticas
- Reduz falhas temporais
- RTOS como Nano-RK oferece reserva de CPU e energia

---

# Comparação: RTOS vs GPOS

- **RTOS**: alta previsibilidade e resposta rápida
- **GPOS**: eficiência geral, sem garantias de tempo real
- Exemplo: **Nano-RK** vs **Linux tradicional**

---

# Eficiência Energética

- **RTOS**: melhor gestão de energia
- Permite operação prolongada de dispositivos embarcados
- Exemplo: Nano-RK garante eficiência energética

---

# Conclusão

O uso de RTOS em robôs aspiradores de pó oferece:
- Segurança
- Eficiência
- Melhor gestão de recursos

Os RTOS, como o Nano-RK, são superiores a GPOS para aplicações críticas.

---
