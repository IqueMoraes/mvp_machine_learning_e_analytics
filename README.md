### README.md

# Projeto de Avaliação - Pós-Graduação em Data Science e Analytics (PUC-Rio)
### por Ique Moraes


Este projeto faz parte da avaliação da disciplina de **Machine Learning e Analytics** no curso de pós-graduação em Data Science e Analytics da **PUC-Rio**. O trabalho tem como objetivo principal aplicar técnicas de aprendizado de máquina para classificar alunos no meio de um curso, proporcionando insights para ações de reaproximação e engajamento.

---

## **Descrição do Projeto**

- **Foco do Trabalho:**  
  A classificação dos alunos no meio do curso visa identificar aqueles que apresentam menor interesse e engajamento, permitindo ações direcionadas de reaproximação e suporte por parte da instituição de ensino.

- **Dados:**  
  Os datasets utilizados no projeto são baseados em dados reais fornecidos por uma empresa de ensino para fins de estudo. Para garantir a segurança e privacidade dos dados de terceiros:
  - Todos os **e-mails**, **nomes de cursos** e **nomes de professores** foram mascarados.
  - O dataset disponível no diretório já foi alterado e mascarado, de modo a preservar a confidencialidade das informações.

- **Arquivos Principais:**
  1. **Classificação de Texto:**  
     Contém o modelo básico de processamento de linguagem natural (PLN) treinado, que foi utilizado como suporte para o projeto principal. Este arquivo não explora ações detalhadas, focando apenas na classificação de texto.
  2. **Compilando e Mascarando Dados:**  
     Scripts responsáveis por:
     - Processar os datasets iniciais.
     - Mascarar os dados reais.
     - Unir as informações em uma única planilha para análise.
  3. **Valores_Mapping.json:**  
     Um dicionário que contém as regras de troca e mapeamento de valores categóricos conforme definido nas regras de negócio. Isso facilita o processamento e análise dos dados.
  4. **Requisitos:**  
     As bibliotecas necessárias para executar o projeto estão listadas no arquivo **requirements.txt**.

---

## **Observações Importantes**

- **Privacidade:**  
  Os datasets apresentados foram modificados para preservar a segurança dos dados reais. Qualquer tentativa de reproduzir os resultados utilizando outros dados deve seguir os mesmos cuidados éticos.

- **Objetivo Final:**  
  Auxiliar a instituição de ensino na tomada de decisões para melhorar o engajamento dos alunos e aumentar as taxas de retenção nos cursos.

---

## **Estrutura do Projeto**

- **Notebooks:**  
  - Contêm as análises exploratórias, treinamento dos modelos e avaliação de resultados.
- **Datasets Mascarados:**  
  - Versões seguras dos dados reais, utilizadas exclusivamente neste projeto.
- **Arquivos de Apoio:**  
  - Scripts de pré-processamento e mapeamento de valores.

---

## **Configuração do Ambiente**

1. Clone o repositório.
2. Instale as dependências executando:
   ```bash
   pip install -r requirements.txt
   ```
3. Certifique-se de que todos os arquivos do diretório estão organizados conforme descrito.

---

## **Créditos**

Projeto desenvolvido como parte da avaliação da pós-graduação em **Data Science e Analytics** - **PUC-Rio**.  
Os dados foram fornecidos por uma empresa de ensino exclusivamente para fins educacionais.