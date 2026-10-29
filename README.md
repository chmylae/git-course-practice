# Git и GitHub — практикум по урокам 16–25

Это рабочая область из **10 отдельных папок/мини-проектов**, а не один общий сайт вместо всех упражнений. Откройте `git-course-lessons.code-workspace` в VS Code: каждая папка урока появится отдельно.

## Папки уроков

- [16 — ветки, fix и разрешение конфликта](lessons/16-merge/README.md)
- [17 — отдельный README-проект](lessons/17-readme/README.md)
- [18 — синтаксис Markdown](lessons/18-markdown/README.md)
- [19 — настройки и рекомендации VS Code](lessons/19-settings-sync/README.md)
- [20 — Gist](lessons/20-gist/README.md)
- [21 — мини-сайт для Pages](lessons/21-pages/README.md)
- [22 — README профиля](lessons/22-profile/README.md)
- [23 — Fork и Pull Request](lessons/23-fork-pull-request/README.md)
- [24 — `.gitignore`](lessons/24-gitignore/README.md)
- [25 — итоги курса](lessons/25-summary/README.md)

## Урок 16 в Git-истории

На ветке `fix` исправлен подвал, а в `main` сделано другое изменение той же строки. Слияние вызвало настоящий конфликт; файл исправлен вручную, затем создан merge-коммит. Проверьте граф:

```bash
git log --oneline --graph --decorate --all
```

## Опубликованный портфолио-проект

- [Репозиторий](https://github.com/chmylae/git-course-practice)
- [GitHub Pages](https://chmylae.github.io/git-course-practice/)
- [Профиль](https://github.com/chmylae)
- [Gist](https://gist.github.com/chmylae/b271872a39a7cca6e36893a97254940a)
- [Pull Request №1](https://github.com/chmylae/git-course-practice/pull/1)
