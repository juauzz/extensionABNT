# Extensão ABNT para Quarto

Esta extensão permite gerar documentos PDF formatados de acordo com as normas ABNT usando o [Quarto](https://quarto.org/). Ela inclui um template LaTeX personalizado e um estilo de citação (CSL) compatível com as normas ABNT.

## Recursos

- **Template LaTeX**: Formatação automática de margens, fontes, títulos e seções.
- **Estilo de Citação (CSL)**: Compatível com as normas ABNT para referências bibliográficas.
- **Exemplo Pronto**: Um arquivo de exemplo (`example.qmd`) para você começar rapidamente.

## Instalação

Para usar esta extensão, siga os passos abaixo:

1. **Clone este repositório**:
   ```bash
   git clone https://github.com/juauzz/extensionABNT.git


PARA USO 

-title: "Meu Documento ABNT"
-author: "Seu Nome"
-format:
  -pdf:
    -extensions: [extensionABNT]
