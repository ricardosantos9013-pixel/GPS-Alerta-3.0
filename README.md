# 🛰️ GPS Alerta 3.0

Central de navegação 3D e monitoramento viário que reúne conceitos do **Waze**, **Google Maps**, **Google Earth**, **OpenSignal** e integração com o **OMR Maps** para deslocamentos e rotas de campo no Brasil.

## ✨ Principais Funcionalidades

* **Busca Rápida por Sigla do OMR Maps:** Digite siglas como `PMOR1`, `SIPMOR1`, `SIMIADTC`, `SIOIN01` ou endereços na barra superior para localizar o site, visualizar coordenadas, detentora da torre e traçar a rota.
* **Importação de Sites (.KML / .CSV):** Importe arquivos `.KML` exportados do Google My Maps (`mid=1MNogDuJ0kYtkUUoZ4l_cnGOx4VGYNqY`) para salvar siglas e pontos de interesse localmente no navegador (`localStorage`).
* **Visualização 3D & Modos de Mapa:** Alternância entre **Nav 3D**, **Google Earth** e **HUD Noturno**, com arraste para rotacionar/inclinar a visão, além de rótulos de condomínios, edifícios, restaurantes, postos de combustíveis e torres.
* **Alertas Viários & Reporte:** Avisos de radares fixos e móveis, bases policiais/PRF, buracos na pista, acidentes, tempestades, pedágios com valores e botão **Reportar** para inserir ocorrências na rota.
* **Camada OpenSignal & Torres:** Indicadores de intensidade de sinal (`dBm`), alertas preventivos de zonas de sombra e referência de operadoras/detentoras (**TIM**, **Vivo**, **Claro**, **SBA Torres**, **Torres Brasil**, **American Tower** e **IHS Towers**).

## 🚀 Como Publicar no GitHub Pages

1. Salve o código principal da aplicação como `index.html` na raiz do repositório.
2. Acesse **Settings** > **Pages** no GitHub.
3. Em **Build and deployment** > **Branch**, selecione `main` e a pasta `/(root)`.
4. Salve e aguarde a geração do link público (`https://SEU-USUARIO.github.io/NOME-DO-REPO/`).

## 📁 Estrutura Atual

```text
├── index.html   # Aplicação completa em HTML5, CSS3 e JavaScript
└── README.md    # Documentação do projeto
```

