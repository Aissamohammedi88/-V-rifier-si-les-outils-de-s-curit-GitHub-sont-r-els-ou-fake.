# -V-rifier-si-les-outils-de-s-curit-GitHub-sont-r-els-ou-fake.
 Tests réussis : 4 / 7 (57%)   Verdict : PARTIELLEMENT RÉELS. Certaines APIs existent, d'autres sont fake ou limitées.

▸ [1/5] CODEQL (Code Scanning)
───────────────────────────────────────────────────────────────
  [OK] L'endpoint CodeQL existe et répond (JSON valide).
  [WARN] Impossible de lire les langages (dépôt peut-être vide).

▸ [2/5] SECRET SCANNING
───────────────────────────────────────────────────────────────
  [OK] L'endpoint Secret Scanning existe et répond.
  [WARN] L'endpoint des patterns n'est pas accessible (normal si pas GHAS).

▸ [3/5] DEPENDABOT
───────────────────────────────────────────────────────────────
  [OK] L'endpoint Dependabot existe et répond.

▸ [4/5] COHÉRENCE DOCUMENTATION vs API
───────────────────────────────────────────────────────────────
  [WARN] CodeQL ne détecte pas Python sur ce dépôt (peut-être vide).

▸ [5/5] RATE LIMIT & RÉPONSES HTTP
───────────────────────────────────────────────────────────────
  [OK] Rate limit cohérent : 54/60 (API réelle).

═══════════════════════════════════════════════════════════════════════
  RAPPORT DE FIABILITÉ DES OUTILS GITHUB
═══════════════════════════════════════════════════════════════════════
  Tests réussis : 4 / 7 (57%)
  Verdict : PARTIELLEMENT RÉELS. Certaines APIs existent, d'autres sont fake ou limitées.
═══════════════════════════════════════════════════════════════════════
