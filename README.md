# Image Cleaner Pro

> Software desktop para higienizacao em lote e reescrita profunda de metadados em imagens digitais, com sistema de licenciamento por hardware fingerprint.

---

## Visao Geral

O **Image Cleaner Pro** e um software Windows desenvolvido em Python, voltado para privacidade e tratamento de imagens digitais. Realiza a remocao e reescrita profunda de metadados (EXIF, GPS, timestamps) em lote, com diversas tecnicas de ofuscacao de identidade digital.

---

## Funcionalidades

### Configuracoes de Limpeza
| Feature | Descricao |
|---|---|
| **Remover EXIF** | Remove GPS, camera, timestamp e todos os metadados |
| **Resize Trick** | Altera interpolacao para quebrar fingerprint de resolucao |
| **Double Pass JPEG** | Muda tabelas JPEG internas |
| **Sharpen** | Unsharp mask suave para alteracao de frequencias |
| **Injecao de Ruido** | Quebra pHash perceptual |
| **LSB Noise** | Altera bits menos significativos dos pixels |
| **Timestamp Fake** | Injeta data aleatoria do SO |
| **Micro Crop** | Recorte imperceptivel de borda |
| **Color Shift** | Ajuste sutil de brilho/contraste |
| **Micro Rotacao** | Rotacao de 0.1 a 0.5 graus |

### Injecao de Identidade
| Feature | Descricao |
|---|---|
| **Injetar Dispositivo** | Simula iPhone, Samsung, Xiaomi nos metadados |
| **GPS Brasil** | Injeta coordenadas reais de cidade brasileira |
| **Nome Realista** | Renomeia arquivo para padrao de camera (IMG_4821.jpg) |
| **UUID Unico** | ImageUniqueID por foto |
| **Milissegundos** | SubSecTimeOriginal para maior realismo |
| **Fuso -03:00** | OffsetTimeOriginal BR |
| **Data = Agora** | Injeta data/hora atual |
| **Thumbnail EXIF** | Miniatura embutida nos metadados |

---

## Stack Tecnologica

![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python)
![Pillow](https://img.shields.io/badge/Pillow-Imagem-green?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-Arrays-013243?style=flat-square&logo=numpy)
![PyInstaller](https://img.shields.io/badge/PyInstaller-Empacotamento-yellow?style=flat-square)
![Windows](https://img.shields.io/badge/Windows-Standalone_EXE-0078D6?style=flat-square&logo=windows)

- **Linguagem:** Python 3.11
- **Processamento:** Pillow, NumPy, piexif
- **Interface:** Tkinter customizado
- **Licenciamento:** Hardware fingerprint (machine ID)
- **Distribuicao:** PyInstaller + InnoSetup (.exe standalone)
- **Compatibilidade:** Windows 10/11 x64

---

## Licenciamento

O software utiliza sistema de licenciamento baseado em **hardware fingerprint (machine ID)**, que vincula a licenca a um dispositivo especifico, impedindo distribuicao nao autorizada.

---

## Visualizacao do Software

![Image Cleaner Pro em operacao](screenshot.png)

---

## Autor

**Paulo Henrique Matos de Souza**
phrobots.com.br | paulohenriquems1975@gmail.com

> Software desenvolvido de ponta a ponta: concepcao, desenvolvimento, empacotamento e sistema de licenciamento.
