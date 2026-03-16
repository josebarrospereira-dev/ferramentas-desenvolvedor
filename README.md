# Ferramentas Desenvolvedor (HTML único)

Este projeto é uma ferramenta de utilitários para desenvolvedores implementada 100% em HTML + JavaScript + CSS, num único arquivo (ferramentas-desenvolvedor.html).

> A ideia é facilitar o uso como um arquivo .exe leve: basta abrir o HTML no navegador e usar imediatamente, sem precisar instalar nada.

## Visão geral

- Navegação de menu horizontal para alternar entre funcionalidades.
- Tudo executado localmente no browser, sem servidor.
- O app é simples e rápido, ideal para as tarefas de codificação/decodificação e formatação do cotidiano de um desenvolvedor.

## Funcionalidades

1. Base 64 (texto)
   - Converter texto em Base64.
   - Decodificar Base64 para texto.
   - Opção UTF-8 para preservar acentuação e caracteres especiais.
   - Botões para copiar resultados.

2. Base 64 - Arquivo (decodificar para download)
   - Recebe texto em Base64 de um arquivo.
   - Define nome e extensão (padrão: arquivo.pdf).
   - Gera link para download do arquivo.

3. Arquivo - Base 64
   - Seleciona arquivo local.
   - Converte o arquivo em Base64.
   - Exibe o resultado em textarea com botão copiar.

4. JSON Beautify
   - Recebe JSON compactado/sem formatação.
   - Converte para JSON formatado legível.
   - Resultado com botão copiar.

5. XML Beautify
   - Recebe XML não formatado.
   - Converte para XML estruturado com identação.
   - Resultado com botão copiar.

## Uso

1. Abra ferramentas-desenvolvedor.html no navegador.
2. Clique na aba desejada no menu superior.
3. Insira dados, clique em ação (Codificar, Decodificar, Beautify, etc.).
4. Copie ou baixe resultado conforme precisa.

## Observações

- Não há backend: todo processamento é feito no cliente.
- Seguro: Os dados utilizados na ferramenta não são enviados para lugar algum, podendo trabalhar com dados sensíveis sem preocupações.
- Suporta drag-and-drop não implementado.
- Ideal para portabilidade: leve e pronto para funcionar em qualquer máquina com navegador.

## Autor

- Desenvolvedor: josebarrospereira-dev
