# Dota 1v1 - Frontend

Para servir localmente o site execute `npm run start:local`

## Resoluções suportadas

1024 x 768 -> 4K

## Atividades

- Criar botões
  - resultado imediato da batalha
  - acelerar batalha
  - desacelerar batalha
  
  
- Melhorar usabilidade da caixa de log
  - Aumentar tamanho do log
  - Criar forma de seleciona todo log com facilidade



- Criar seleção de herois
  - nova página (ok)
    - Criar novo arquivo
    - Considerar copiar estilo da página de batalha
    - Tentar acessá-la
  - dispor heróis por atributo
    - requisitar herois p/ backend (ok)
    - agrupar herois por atributo
      - Mudar o backend para ter o atributo do heroi (ok)
      - Agrupar no front pelo atributo (ok)
    - para cada grupo de herois vamos mostrar uma linha com os nomes dos herois (ok)
      - No futuro vamos substituir por imagens (ok)
      - Colocar o nome do heroi na parte de inferior direita da imagem
        - Nome deve acompanhar a posição inferior direita ao expandir o ícone
        - Nome não deve aparecer enquanto o mousehover for acionado
      - Aplicar alterações de ícones p/ todos hérois
      - Substituir as imagens quebradas (ok)
  - como funciona o pick:
    - Ao passar o mouse em cima do heroi, a caixa dele deve aumentar de tamanho e sobrepor as outras
    - Ao clicar no heroi aumentado deve haver um popup de confirmação do heroi para o player x
    - Ao confirmar, o heroi deve ser fixado para o player correspondente
  - Ao pickar dois herois:
    - Bloquearemos a tela para mais ações e ofereceremos dois botões
      - Batalhar
      - Resetar
  - Trocar para imagem da nova api
    - Que tem animação tbm https://rapidapi.com/snldnc-kpCtDKbxo_F/api/dota2-heroes/

- Aula amanhã:
  - Ajustar o tamanho da div agiHeroCard de acordo com a imagem pra crescerem juntos.
- P/ aula 30.11:
  - Ajustar quebra do nome do heroi. (quando nome é grande) o/k
  - Adicionar margem ao lados dos grupos
  - Retratos poderiam ser maiores. ok
  
  - Colocar imagem dos atributos por heroGroup (pensar onde posicionar)
  - Ajustar a margem da heroPortrait ok
  - Ajustar distancias entre heroGroups ok
  