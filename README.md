# xupertv-config

Repositorio de configuracion para XuperTV.

## Archivos

- `config.json` — usuarios, credenciales VPN y servidor OpenVPN
- `index.html` — panel admin (vista cliente + panel)

## Cloudflare Pages

1. En GitHub → Settings → Secrets → Actions, agregar:
   - `CLOUDFLARE_API_TOKEN`
   - `CLOUDFLARE_ACCOUNT_ID`
2. El workflow `.github/workflows/cloudflare-pages.yml` despliega automaticamente en cada push a `main`.
3. Proyecto Cloudflare: `xupertv-panel`

Tambien podes conectar el repo directamente en Cloudflare Pages (Build command vacio, output `/`).

## App Android

URL publica del JSON:
`https://raw.githubusercontent.com/vbustamante662-hash/xupertv-config/main/config.json`
