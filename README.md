# meta-classificador
# Meta-Classificador de Tecidos para HoloLens 2

![Demonstração da UI](https://imgur.com/mfDkU0N) Um aplicativo de Realidade Mista desenvolvido em Unity para a classificação de tonalidades de tecidos em tempo real, utilizando a plataforma HoloLens 2.

## 📝 Visão Geral do Projeto

Este projeto é uma iniciativa de Pesquisa e Desenvolvimento (P&D) focada em modernizar o processo de controle de qualidade na indústria têxtil. Através do uso da Realidade Mista com o HoloLens 2, o aplicativo permite que um operador analise e classifique a tonalidade de tecidos de forma rápida, precisa e objetiva, diretamente na linha de produção.

O projeto é fruto de uma parceria de inovação entre a universidade **UNESC** e a empresa **ADITT**, e foi desenvolvido pelos estagiários de TI Danieli Zeferino Mota e Lucca Dalla Lana, conforme as metas estabelecidas pelo Ministério da Ciência, Tecnologia e Inovação.

## ✨ Funcionalidades Principais

* **Classificação em Tempo Real:** Fornece um feedback instantâneo de "Aprovado" / "Reprovado".
* **Ciência da Cor Avançada:** Utiliza o espaço de cor **CIELAB** e a fórmula **CIEDE2000** para uma análise de diferença de cor alinhada à percepção humana, garantindo alta precisão.
* **Calibração de Iluminação Ambiente:** O usuário pode calibrar o sistema em tempo real usando uma referência neutra (como um cartão cinza 18%), anulando os efeitos da iluminação variável do ambiente.
* **Análise de Área (Multi-ponto):** A cor não é lida de um único pixel, mas sim de uma média de múltiplos pontos em uma área configurável, aumentando a robustez e a confiabilidade da leitura.
* **Painel de Configurações Avançadas:** Uma interface completa dentro do aplicativo permite ao usuário ajustar todos os parâmetros de análise em tempo real:
    * Tamanho da área de amostra (largura e altura).
    * Densidade da amostragem (número de pontos).
    * Limiar de tolerância (valor Delta E para aprovação).
* **Banco de Dados de Presets de Cor:**
    * Armazena cores padrão em um arquivo **JSON** para persistência de dados.
    * Permite ao usuário **Criar, Editar e Deletar** presets de cor diretamente na interface do HoloLens.
    * Funcionalidade de "Captura de Cor" para criar novos presets a partir de amostras físicas.

## 🛠️ Tecnologias Utilizadas

* **Hardware:** HoloLens 2
* **Engine:** Unity 2022.3.x LTS
* **Framework:** Mixed Reality Toolkit (MRTK) v2
* **Linguagem:** C#
* **Plataforma Alvo:** Universal Windows Platform (UWP) - ARM64



## 🙏 Agradecimentos

* À universidade **UNESC** e à empresa **ADITT** pela parceria e oportunidade.
* Aos mentores e à equipe de desenvolvimento do estágio.
