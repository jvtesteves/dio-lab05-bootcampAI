# Exploração do OCR com Azure AI e Vision Studio

Este repositório é um resumo pessoal da minha experiência explorando as capacidades de Reconhecimento Óptico de Caracteres (OCR) oferecidas pelo Azure AI Vision, utilizando o Vision Studio. O foco foi detectar e interpretar texto em imagens sem precisar escrever código, buscando compreender melhor como essa tecnologia pode ser aplicada em diferentes contextos. Nele temos as imagens de input e os outputs para cada imagem que Azure forneceu.

## Processo

### Criando um recurso de serviços de IA do Azure

1. Acessei o portal do Azure (https://portal.azure.com) e fiz login com a conta Microsoft associada à minha assinatura do Azure.
2. Cliquei no botão "+Criar um recurso" e procurei por "Serviços de IA do Azure". Selecionei "Criar um plano de serviços de IA do Azure".
3. Configurei o recurso com as seguintes definições:
   - **Assinatura**: Minha assinatura do Azure.
   - **Grupo de recursos**: Selecionei ou criei um grupo de recursos com um nome único.
   - **Região**: Leste dos EUA.
   - **Nome**: Dei um nome único ao recurso.
   - **Nível de preço**: Padrão S0.
4. Após configurar, selecionei "Revisar + criar" e depois "Criar" e aguardei a conclusão da implantação.

### Conectando meu recurso de serviços de IA do Azure ao Vision Studio

1. Naveguei até o Vision Studio (https://portal.vision.cognitive.azure.com) e fiz login.
2. Na página inicial, selecionei "Ver todos os recursos" sob o cabeçalho "Começando com Vision".
3. Na página "Selecionar um recurso para trabalhar", passei o mouse sobre o recurso criado e marquei a caixa à esquerda do nome do recurso, então selecionei "Selecionar como recurso padrão".

### Extraindo texto de imagens no Vision Studio com Imagens da Internet

1. Fui até "Reconhecimento óptico de caracteres" no Vision Studio e escolhi a opção para extrair texto de imagens.
2. Em vez de utilizar o arquivo `ocr-images.zip` recomendado, pesquisei na internet e encontrei três tipos distintos de imagens que contêm texto. Isso incluiu uma página de livro, uma placa de sinalização e um anúncio com texto sobreposto em imagem.
3. Salvei essas imagens em uma pasta no meu computador.
4. No Vision Studio, selecionei "Procurar por um arquivo" e naveguei até a pasta onde havia salvo as imagens. Escolhi uma das imagens e cliquei em "Abrir" para começar a análise.
5. Observei os atributos detectados e as caixas de delimitação de texto na imagem, notando como o texto foi organizado em estruturas hierárquicas de regiões, linhas e palavras.
6. Repeti o processo para as outras imagens, avaliando os resultados de cada uma para entender melhor a capacidade do OCR em lidar com diferentes tipos de imagens.

## Insights e Possibilidades

- **Automatização de Processos**: Descobri que a capacidade de extrair texto de imagens pode automatizar diversos processos empresariais, como digitalizar formulários impressos e processar automaticamente recibos e faturas.
- **Acessibilidade**: O OCR pode ser usado para tornar documentos impressos acessíveis digitalmente, ajudando pessoas com deficiência visual.
- **Integração de Dados**: As informações extraídas podem ser facilmente integradas a sistemas de gestão de dados, melhorando a coleta e análise de informações.
- **Melhoria Contínua**: Experimentar com diferentes tipos de imagens me deu insights sobre como otimizar a qualidade do texto reconhecido, ajustando fatores como iluminação, ângulo da imagem e clareza do texto.

Explorar o OCR com o Azure AI e o Vision Studio demonstrou a facilidade e eficiência com que a tecnologia pode ser aplicada, oferecendo um leque de possibilidades para inovação e melhoria de processos.
