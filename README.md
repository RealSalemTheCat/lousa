# Lousa

Lousa digital para jogos de festa: escreva ou desenhe, gire a tela e mostre para a mesa.

## Publicar no GitHub Pages
1. Envie todos os arquivos desta pasta para a raiz do repositório.
2. Em **Settings › Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. O app fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Jogar em grupo (Jogo › Sala)
- **Online (código):** o anfitrião cria a sala e recebe um código curto (ex.: GATO-27) e um QR com o link. Os outros digitam o código ou escaneiam o QR. A internet é usada só para os celulares se encontrarem (rede pública Nostr); depois a conexão é direta entre eles.
- **Offline (QR):** sem internet. O convidado escaneia o QR do anfitrião e mostra o QR de resposta para a câmera dele. Todos no mesmo Wi-Fi ou no roteador do celular do anfitrião.

Depois da primeira visita, o app abre mesmo sem internet.

## Bibliotecas incluídas
qrcode-generator (MIT), jsQR (Apache-2.0), Trystero (MIT).
