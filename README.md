# MarinhoComputers — Museu 3D de hardware

Site estático em HTML, CSS e JavaScript com Three.js carregado via CDN ESM.

## Recursos
- Três modelos de gabinete em 3D estilizados (não CAD real)
- Rotação por arraste, zoom e seleção por clique
- Remoção/reinstalação de CPU, GPU, RAM, placa-mãe, fonte, armazenamento, ventoinhas e gabinete, com animação
- Comparação de faixas estimadas de FPS em 7 jogos
- Comparação qualitativa de tarefas gerais e linha do tempo
- Interface responsiva em português do Brasil

## Publicar na Vercel
1. Envie o conteúdo desta pasta para um repositório GitHub.
2. Importe o repositório em vercel.com/new.
3. Framework preset: Other. Build command: vazio. Output directory: vazio ou `.`.
4. Deploy.

O 3D usa importações de `https://esm.sh/three@0.170.0` e exige conexão à internet. Para testar localmente, execute `python -m http.server 8000` na pasta e abra `http://localhost:8000`.

## Limitações
- Os modelos 3D são representações geométricas conceituais, não réplicas fiéis dos componentes.
- FPS são estimativas indicativas, não medições feitas nos PCs.
- As tarefas usam pontuação qualitativa subjetiva.
