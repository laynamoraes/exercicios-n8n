# 🚀 Projeto de Automação com n8n

Este repositório contém as soluções para dois exercícios práticos focados em automação e desenvolvimento de APIs, utilizando a ferramenta **n8n** para o **Orion Bootcamp** da **Nwe Rizon**.

<br>

## 1. API REST para CRUD de Produtos

O objetivo deste exercício é desenvolver um conjunto de endpoints REST para realizar operações de CRUD de produtos armazenados em uma planilha do Google Sheets.


### 📊 Estrutura de Dados
[cite_start]A planilha de armazenamento deve conter as seguintes colunas[cite: 6]:
* `id`
* `nome`
* `custo`
* `categoria`

### 🛠️ Endpoints
| Método HTTP | Endpoint | Descrição |
| :--- | :--- | :--- |
| `GET` | `/produtos` | Lista todos os produtos |
| `POST` | `/criar-produto` | Cria um novo produto |
| `PUT` | `/editar-produto` | Atualiza um produto existente |
| `DELETE`| `/excluir-produto` | Remove um produto |

<br>

## 2. Gerador Automático de Figurinhas (Stickers) para WhatsApp

Este exercício demonstra uma automação reativa onde o sistema deve converter uma imagem recebida pelo WhatsApp em uma figurinha e enviá-la de volta.

### 🌟 Funcionalidade Principal
**Conversão e Resposta:** Ao receber uma imagem pelo WhatsApp, o sistema deve converter automaticamente essa imagem em uma figurinha (sticker) e enviá-la de volta como resposta na mesma conversa.

### ⚙️ Fluxo de Automação
1.  **Gatilho:** Recebimento de uma imagem via WhatsApp.
2.  **Processamento:** Conversão da imagem para o formato de figurinha (sticker).
3.  **Ação:** Envio da figurinha de volta para a conversa.
