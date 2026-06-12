# Relogio de Estudo

Uma app simples para escolher tempo de estudo, intervalos e ciclos, com toques sonoros quando muda de fase.

## Como publicar no GitHub Pages sem erro de Actions

1. Cria um repositorio no GitHub.
2. Envia estes ficheiros para a raiz do repositorio:
   - `index.html`
   - `site.webmanifest`
   - `.nojekyll`
3. No GitHub, vai a `Settings` > `Pages`.
4. Em `Build and deployment`, escolhe `Deploy from a branch`.
5. Escolhe a branch `main` e a pasta `/root`.
6. Guarda. O GitHub vai criar um link do tipo:
   `https://teu-utilizador.github.io/nome-do-repositorio/`

Se quiseres um link mais curto, cria o repositorio com o nome `teu-utilizador.github.io`.

Nota: este site nao precisa de GitHub Actions. Se aparecer um deploy antigo a falhar, podes ignorar depois deste commit ou cancelar esse workflow no separador `Actions`.
