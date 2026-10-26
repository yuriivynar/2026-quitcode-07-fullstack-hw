# Здача WS7

## Дані

- Роль: dev
- Команда: property-workflows
- GitHub-логін: yuriivynar
- Ваше репо: https://github.com/yuriivynar/property-workflows
- SHA: d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6
- Репо вимог PM: https://github.com/solomchaak/property-workflows-spec
- Прод-URL: https://property-workflows-eta.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: Вимоги: https://github.com/solomchaak/property-workflows-spec · джерело: issues · знімок 2026-10-25
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/yuriivynar/property-workflows/pull/12
- PR «Оновлення вимог» після уточнень PM (A): /requirements-sync 2026-10-26: Вимоги актуальні
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/solomchaak/property-workflows-spec/issues/25, https://github.com/solomchaak/property-workflows-spec/issues/26, https://github.com/solomchaak/property-workflows-spec/issues/27, https://github.com/solomchaak/property-workflows-spec/issues/28, https://github.com/solomchaak/property-workflows-spec/issues/29, https://github.com/solomchaak/property-workflows-spec/issues/30, https://github.com/solomchaak/property-workflows-spec/issues/31, https://github.com/solomchaak/property-workflows-spec/issues/34 (пропозиція), коментар https://github.com/solomchaak/property-workflows-spec/issues/26#issuecomment-6403641883
- PR «Специфікація» з `add-<зріз2>` (A): https://github.com/yuriivynar/property-workflows/pull/14
- Дизайн-система — PR (B): https://github.com/yuriivynar/property-workflows/pull/13
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/DESIGN.md · джерело: AI-чат: Claude Code (Claude Opus 5.5), промпт — в описі PR #13
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/yuriivynar/property-workflows/actions/runs/40398243673
- Знімки «до/після» (B): https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/docs/img/ws7-before-runs-light.png, https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/docs/img/ws7-after-runs-light.png (усі — `docs/img/ws7-before-*`, `docs/img/ws7-after-*`, у PR #13)
- Зміна `impl-<зріз2>` (C): https://github.com/yuriivynar/property-workflows/tree/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/openspec/changes/archive/2026-10-26-impl-template-versions (PR «Специфікація» https://github.com/yuriivynar/property-workflows/pull/15)
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/yuriivynar/property-workflows/pull/17, https://github.com/yuriivynar/property-workflows/pull/18, https://github.com/yuriivynar/property-workflows/pull/19
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/yuriivynar/property-workflows/actions/runs/40333425879 (AC-EDITOR-08), https://github.com/yuriivynar/property-workflows/actions/runs/40333927209 (AC-EDITOR-02)
- ADR (D): https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/docs/decisions/0003-authz-in-actions-and-database.md, https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/docs/decisions/0002-template-versions-jsonb-snapshot.md
- Архітектурне правило, крім `check:design` (D): job «Перевірка входу й ролі в кожній дії» (`scripts/check-actions-claims.mjs`) і «Секретний ключ лише на сервері»; доказ — вивід скрипта на навмисних порушеннях в описі PR https://github.com/yuriivynar/property-workflows/pull/19 (розділ «Доказ, що правило ловить порушення»); job зелений на main: https://github.com/yuriivynar/property-workflows/actions/runs/40398243673
- Акаунти для PM (E): pm-manager@example.test (manager), pm-admin@example.test (admin)
- Скріни за ролями (E): https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/docs/img/ws7-role-admin-templates.png, https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/docs/img/ws7-role-admin-editor.png, https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/docs/img/ws7-role-admin-editor-error.png, https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/docs/img/ws7-role-admin-versions.png, https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/docs/img/ws7-role-manager-template.png, https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/docs/img/ws7-role-manager-editor-denied.png, https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/docs/img/ws7-role-manager-runs-empty.png, https://github.com/yuriivynar/property-workflows/blob/d2cb7f72ed78b839867f2ac6d57f59ed5b6f39e6/docs/img/ws7-role-visitor-run-link.png (також в описі PR https://github.com/yuriivynar/property-workflows/pull/19)
- AC зрізу 2 (E): AC-EDITOR-01 … AC-EDITOR-09 (реалізовано), AC-DSYS-01 … AC-DSYS-04 (реалізовано)
- Відхилення від PM (E): не надходило

## Бонус

Цикл візуальної перевірки в браузері агента (Playwright MCP) — PR https://github.com/yuriivynar/property-workflows/pull/13, розділ «Бонус»: агент зняв 5 сторінок у світлій і темній темі, порівняв з `DESIGN.md` і знайшов відхилення, якого не ловить `check:design`: посилання мали колір акценту (`text-primary` — формально токен), тож головна дія губилась серед них, а «Вигляд і тон» відводить акцент лише головній дії. Виправлено (`TextLink` — колір тексту), правило записано в `DESIGN.md`, знімки до/після — у PR. Висновок: скрипт перевіряє синтаксис (токен чи ні), а браузерна перевірка — зміст (той токен чи ні); дизайн-системі потрібні обидві.
