# QR Code Generator

Este projeto é um script simples em JavaScript para gerar QR Codes. Ele utiliza bibliotecas populares para criar códigos QR de forma rápida e eficiente.

## Funcionalidades

- Geração de QR Codes personalizados.
- Suporte para diferentes tamanhos e cores.
- Fácil integração com projetos existentes.

## Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/qrcode-generator.git
   ```
2. Abra o arquivo `index.html` em um navegador.
3. Insira o texto ou URL no campo de entrada.
4. Clique no botão "Gerar QR Code" para visualizar o código gerado.

## Exemplo de Código

```javascript
const qrCode = new QRCode(document.getElementById("qrcode"), {
  text: "https://exemplo.com",
  width: 128,
  height: 128,
  colorDark: "#000000",
  colorLight: "#ffffff",
  correctLevel: QRCode.CorrectLevel.H,
});
```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
