# MB Finanças — Júnior Back-end

Materiais oficiais do projeto incremental do curso Júnior Back-end da
[MB Academy](https://github.com/MBrunoS/mb-academy).

O curso ainda está em preparação, mas seu contrato e projeto já podem ser
explorados.

## Conteúdo

- `student-starter/`: NestJS mínimo com health check;
- `sprints/`: especificação das seis entregas;
- `kit/contract/`: contrato OpenAPI e coleção HTTP;
- `kit/contract-tests/`: suíte externa de conformidade;
- `kit/reference-web/`: cliente React para validar sua API;
- `kit/reference-api/`: comportamento oficial executável para comparação.

```bash
git clone https://github.com/MBrunoS/junior-backend-financas.git
cd junior-backend-financas/student-starter
pnpm install
pnpm dev
```

As tags imutáveis `sprint-N-materials` identificam os materiais de cada etapa.
A implementação de referência em NestJS será publicada junto das aulas
completas; até lá, a API sem dependências em `kit/reference-api` define o
comportamento esperado.
