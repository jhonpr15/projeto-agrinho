# 🌾 Projeto Agrinho - Irrigação Inteligente Automatizada

![Status do Projeto](https://shields.io)
![Ano](https://shields.io)
![Categoria](https://shields.io)

## 📝 Sobre o Projeto
Este repositório armazena todo o código-fonte, esquemáticos de circuitos e documentação do protótipo **Irrigação Inteligente Automatizada**. O projeto foi integralmente desenvolvido para a participação no **Concurso Agrinho 2026**, promovido pelo [Sistema FAEP/SENAR-PR](https://www.sistemafaep.org.br/agrinho/) em parceria com a Secretaria de Estado da Educação ([Seed-PR](https://www.educacao.pr.gov.br/Noticia/Concurso-de-Redacao-Agrinho-2026-mobiliza-alunos-da-rede-estadual-partir-desta-semana)).

Alinhado com o tema oficial deste ano — **"Agro forte, futuro sustentável: equilíbrio entre produção e meio ambiente"** —, o projeto propõe uma solução tecnológica viável para evitar o desperdício de água na agricultura familiar, otimizando o uso de recursos hídricos por meio da automação.

---

## 🎯 Objetivos
*   **Otimizar Recursos:** Monitorar a umidade do solo em tempo real para acionar a irrigação apenas quando necessário.
*   **Sustentabilidade:** Evitar o desperdício de água e energia elétrica nas propriedades rurais.
*   **Aprendizado Prático:** Aplicar conceitos fundamentais de lógica de programação, eletrônica digital e robótica aplicada ao campo.

---

## 🚀 Tecnologias e Ferramentas Utilizadas
O projeto combina componentes físicos (hardware) e instrução lógica (software):
*   **Hardware / Componentes:** 
    *   Placa Microcontroladora (Compatível com Arduino)
    *   Sensor de Umidade do Solo Higrômetro
    *   Módulo Relé 5V
    *   Mini Bomba de Água Submersível
    *   Display LCD 16x2 e LEDs indicadores (Verde/Vermelho)
*   **Linguagens e Softwares:**
    *   Linguagem C++ (IDE do Arduino)
    *   Tinkercad (Para simulação inicial do circuito eletrônico)

---

## 🛠️ Como Funciona?
O sistema opera em um ciclo contínuo de leitura e tomada de decisão automática:
1.  **Leitura do Solo:** O sensor higrômetro mede o nível de umidade da terra constantemente.
2.  **Análise de Dados:** O microcontrolador processa o valor recebido pelo sensor.
3.  **Ação Automatizada:** 
    *   Se o solo estiver **seco**, o módulo relé é ativado, ligando a bomba de água automaticamente e acendendo o **LED Vermelho** (Alerta de Irrigação).
    *   Assim que o solo atinge o nível de umidade **ideal**, a bomba é desligada imediatamente e o **LED Verde** se acende, economizando água.
4.  **Interface Visual:** O Display LCD exibe a porcentagem exata de umidade atual para controle do produtor rural.

---

## 📂 Estrutura do Repositório
*   `/src`: Contém o código-fonte `.ino` principal utilizado na placa.
*   `/hardware`: Esquemáticos do circuito, diagramas de blocos e lista de componentes.
*   `/docs`: Relatórios pedagógicos e arquivos complementares exigidos pelo concurso.

---

## 📸 Demonstração
> 💡 *Dica: Substitua os links falsos abaixo pelas imagens reais do seu protótipo em funcionamento ou simulação.*


| Protótipo Físico | Circuito Simulado |
| :-: | :-: |
| ![Foto do Projeto Físico](https://placeholder.com) | ![Esquema do Circuito](https://placeholder.com) |

---

## 👥 Integrantes e Autores
O projeto foi desenvolvido com dedicação e trabalho em equipe:
*   **Nome do Aluno 1** - Desenvolvedor de Software - [GitHub](https://github.com/)
*   **Nome do Aluno 2** - Montagem e Hardware
*   **Nome do Professor(a)** - Orientador(a) do Projeto
*   **Escola:** Nome da Instituição de Ensino
*   **Cidade:** Município - PR

---

## 📄 Licença
Este projeto é aberto e está sob a licença MIT. Consulte o arquivo `LICENSE` no repositório para obter mais detalhes.
