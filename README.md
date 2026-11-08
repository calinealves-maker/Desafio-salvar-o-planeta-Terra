# Desafio: salvar o planeta Terra

Aula virtual de **Língua Portuguesa** para o **8º ano A**, feita para uso dos alunos · 50 minutos.

Tema: texto argumentativo (tese, argumentos, fato e opinião, conectivos) com o tema ambiental.

## O que tem na página

- Leitura, 3 missões interativas (fato ou opinião, tese e argumentos, conectivos) e um termômetro que esfria a cada acerto.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `aula-planeta`).
2. Envie os arquivos `index.html` e `README.md` (botão **Add file → Upload files**).
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e clique em **Save**.
5. Em cerca de 1 minuto, a aula estará em `https://SEU-USUARIO.github.io/aula-planeta/`.

Pelo terminal:

```bash
git init
git add .
git commit -m "Aula virtual: salvar o planeta Terra"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/aula-planeta.git
git push -u origin main
```

## Personalizar

- Textos e questões: edite os blocos no HTML e os arrays `fo`, `q` e `cx` no final do arquivo.
- Pontuação máxima: a constante `MAX` (hoje 11) deve ser igual ao total de pontos das missões.

## Licença

Uso livre para fins educacionais.
