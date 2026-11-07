# trypost instructions

Read [preserved upstream policies](agent-notes.md) before editing this scope.

Laravel/PHP backend and Vue/Inertia frontend.

Local commands: `php artisan test`, `vendor/bin/pint --test`, `npm run build`, `npm run format:check`, `npx eslint .` (the existing npm lint script writes fixes). Use isolated test DB; do not run migrations against production.

Oomor-only identity: kashik0i; origin must be oomor-hq/trypost.
This branch changes docs only. No paid calls, production operations, public
signup changes, CI enabling or source refactors. Coordinator review before PR/merge.
