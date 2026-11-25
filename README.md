# devops-docs

Документация в docs/ собирается MkDocs. В .github/workflows/quality.yml проверяются Python и Markdown, в pages.yml публикуется каталог site/ через GitHub Pages. Каталог site/ генерируется при сборке.

Локальная проверка: python -m pip install -r requirements-dev.txt, python -m pylint src/status.py --score=no, python -m mkdocs build --strict.
