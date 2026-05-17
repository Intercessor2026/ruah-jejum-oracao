# Jejum & Oração — RUAH 2026

Ferramenta web interativa para inscrição de intercessores em jejum e oração
pelo evento RUAH 2026 (16/05 – 19/09) com Relógio de Oração (20/09 – 03/10).

## Tecnologias
- React 18 + Vite
- Tailwind CSS
- lucide-react (ícones)

## Como rodar localmente
```bash
npm install
npm run dev
```

## Build de produção
```bash
npm run build
```

## Armazenamento
O app usa uma camada `storage` que tenta `window.storage` (Claude Artifacts)
e cai para `localStorage` quando não disponível. Para deploy em produção
com dados compartilhados entre usuários, recomenda-se substituir por
Firebase Firestore, Supabase ou similar.
