# 🤖 Placa Base Arduino Nano para Iniciantes em Robótica

Este projeto documenta uma **placa personalizada baseada no Arduino Nano**, desenvolvida especialmente para **iniciantes em robótica**. Ela foi criada como parte de uma iniciativa educacional para introdução à robótica em escolas, permitindo que alunos e entusiastas aprendam os fundamentos de forma prática, segura e acessível.

---

## 🧩 Características da Placa

- ✅ Compatível com **Arduino Nano** (header padrão)
- 🔋 Alimentação via bateria com regulação para **5V** utilizando **L7805CD2T-TR**
- 📶 Suporte para módulo **Bluetooth HC-06**
- 📡 Conectores para **3 sensores ultrassônicos** (HC-SR04 ou similares)
- 🎯 Headers para conexão de **4 sensores adicionais**
- 💡 **5 LEDs** embarcados para indicação ou debug
- 🔋 Circuito para **medição da tensão da bateria**
- 🔁 **2 drivers DRV8871DDA** integrados para controle de motores DC

---

## 📚 Pensado para a Educação

Este projeto foi desenvolvido como parte de um **programa de ensino de robótica em escolas**, com foco em:

- Simplicidade de uso para alunos do ensino fundamental e médio
- Facilidade de montagem e programação usando a IDE do Arduino
- Compatibilidade com sensores e atuadores amplamente disponíveis no mercado
- Introdução a conceitos como automação, lógica de controle e comunicação sem fio

---

## 📷 Esquemático e Layout

> (Adicione imagens nesta pasta: `docs/images` e substitua os nomes abaixo)

<p align="center">
  <img src="docs/images/esquematico.png" alt="Esquemático da placa" width="600"/>
</p>

<p align="center">
  <img src="docs/images/layout.png" alt="Layout da PCB" width="600"/>
</p>

---

## ⚙️ Aplicações Sugeridas

- Robôs autônomos simples
- Plataformas móveis controladas via Bluetooth
- Testes de sensores em sala de aula
- Introdução à eletrônica e programação embarcada

---

## 📥 Instalação e Uso

1. Grave seu código normalmente via **IDE do Arduino**.
2. Alimente a placa com tensão adequada (ex: 7V–12V na entrada do regulador).
3. Conecte seus sensores e motores nos headers correspondentes.
4. Utilize o módulo Bluetooth para enviar comandos remotamente (ex: via app de celular).

---

## 📐 Especificações Técnicas

| Item                       | Especificação                                  |
|---------------------------|-------------------------------------------------|
| MCU                       | Arduino Nano (ATmega328P)                       |
| Regulador de tensão       | L7805CD2T-TR                                    |
| Comunicação sem fio       | HC-06 (Bluetooth Serial)                        |
| Drivers de motor          | 2x DRV8871DDA (PWM e controle de sentido)       |
| Sensores suportados       | 3x Ultrassônico + 4x via headers                |
| LEDs                      | 5x LEDs embarcados                              |
| Monitoramento da bateria  | Divisor resistivo conectado ao ADC do Nano      |

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 🤝 Contribuições

Sinta-se livre para abrir issues ou enviar pull requests com melhorias, correções ou sugestões!

---

## 🙌 Agradecimentos

Este projeto foi desenvolvido por Eric Makiya Lazana com apoio da Fundação Asimo como **iniciativa educacional para introdução à robótica em escolas públicas**.

