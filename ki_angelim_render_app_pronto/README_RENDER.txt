KI Angelim Dashboard no Render

Passo a passo
1. Crie um repositorio no GitHub.
2. Envie todos os arquivos desta pasta para o repositorio.
3. Entre no Render.
4. Clique em New e depois Web Service.
5. Conecte o repositorio.
6. Se o Render ler o arquivo render.yaml, confirme a criacao.
7. Se pedir configuracao manual, use:
   Build Command: pip install -r requirements.txt
   Start Command: uvicorn main:app --host 0.0.0.0 --port $PORT
8. Aguarde o deploy terminar.
9. Abra a URL onrender.com gerada.

Observacoes
- A versao Free dorme apos 15 minutos sem acesso.
- No proximo acesso ela volta, com uma espera inicial.
- Enquanto houver uso, a navegacao continua normal.
- Os arquivos Excel e PDF ja estao dentro do projeto.
- O app usa Flet dinamico com backend Python no servidor.
