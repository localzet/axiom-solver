# axiom-solver v0.2.0

Компилирует поддерживаемый арифметико-логический фрагмент Axiom в SMT-LIB2. В отличие от v0.1, постусловия действительно
транслируются, а не оставляются как TODO. Production-backend должен вызывать Z3/cvc5 и валидировать либо
реконструировать solver evidence.

## Авторство

Сопровождающий собственных изменений: **Ivan Zorin (localzet)** — <creator@localzet.com> · https://www.localzet.com. Copyright © 2026 Localzet Group. Исходное авторство и лицензии сторонних компонентов сохраняются. См. [AUTHORS](.github/AUTHORS.md).
