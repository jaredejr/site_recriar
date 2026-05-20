# Baseline Spec - Centro Recriar

## 📊 Status Atual (Audit)
- **Google Ads**: ✅ Configurado (AW-18082531759)
- **CRM Integration**: ✅ Implementado e Padronizado (`lib/crm.ts`, `LeadModal.tsx`)
- **SEO**: ✅ Metadata, Robots, Sitemap configurados.
- **Tracking**: ✅ Captura GCLID, FBCLID, MSCLKID e UTMs no `LeadContext` com persistência em sessão.
- **Origem**: ✅ Detecção automática implementada ("Google Ads" se `gclid` presente).

## 🏗️ Stack Técnica
- **Framework**: Next.js 15
- **Styling**: Tailwind CSS 4
- **Components**: LeadModal (interceptação de leads), LeadProvider (gerenciamento de tracking)

## 🔗 Integrações
- **CRM Endpoint**: `/ingest`
- **Data Pattern**: ✅ Totalmente alinhado com a `GENERAL_SPEC.md`.

## 🛠️ Próximos Passos (Melhorias)
- Monitorar a consistência dos dados recebidos no CRM.
