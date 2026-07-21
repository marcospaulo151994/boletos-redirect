# boletos-redirect

Redirecionamento de `boletos.rafano.com.br` para o painel de boletos (Google Apps Script), servido via GitHub Pages.

O destino é a URL `/exec` da implantação do painel. Ela permanece estável desde que as reimplantações usem sempre o mesmo deployment (`npx clasp deploy -i <ID>`). Se um dia a URL mudar, basta atualizar o `index.html` aqui.

O acesso ao painel continua protegido pelo login do Google Workspace — este repositório só encurta o endereço.
