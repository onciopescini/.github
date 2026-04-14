## 📌 Obiettivo e Contesto
<!-- Descrivi brevemente l'impatto di questa PR (Bugfix, Nuova Feature, Refactor Architetturale). Referenzia l'Issue usando "Fixes #XXX" o "Resolves #XXX". -->
Fixes #

## 🕵️‍♂️ Analisi Entanglement (Dipendenze)
<!-- Abbiamo mappato l'impatto di questo codice sui provider chiave della Entanglement Map? -->
- [ ] La modifica tocca `AppProviders.tsx`, Guard routes o Core `auth.users`? Se sì, sii molto esplicito sui side-effects.

## ✅ Checklist dell'Agente / Dev
<!-- Controlla in modo ferreo di rispettare la Governance Rule della nostra CI/CD -->
- [ ] Tutto il codice passa localmente a `npm run typecheck` e `npm run build`.
- [ ] Le Action `build` e `vitest` non hanno warning.
- [ ] Ho aggiornato (se necessario) i mockup o i tipi generati da Supabase `types.ts`.
- [ ] Non vi è NESSUN commit contenente Secret keys, service_roles o stringhe esplicite `VITE_*`.

## 🧪 Deployment Verification
- **Verifica**: L'ambiente Vercel Preview è spinned up con successo? [Sì/No/Pend]
- **QA**: Hai testato i flussi impattati (es. Checkout, Calendario Booking) su Preview? [Sì/No]

## 📸 Mockup o Screenshot (Se tocca la UI Frontend)
<!-- Trascina qui screen del Before/After -->
