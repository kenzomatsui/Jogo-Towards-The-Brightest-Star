# Towards the Brightest Star

**Desvie dos obstáculos, colete energia e avance.**

Protótipo de jogo 2D em Unity, distribuído como um pacote de assets. A implementação reúne movimentação com as setas, obstáculos, itens de recuperação e boosts, com indicadores de vida, distância e energia.

## Controles implementados

| Tecla | Ação |
| :--- | :--- |
| Setas | Movimentar o personagem. |
| Espaço | Ativar o boost quando a energia chega a 100. |

O boost dura cinco segundos e altera o avanço e a velocidade dos obstáculos. O código também inclui recuperação de vida e proteção temporária ao coletar itens específicos.

## Abrir o protótipo

1. Baixe [`Towards the Brightest Star - 01.unitypackage`](Towards%20the%20Brightest%20Star%20-%2001.unitypackage).
2. Crie um projeto 2D no Unity.
3. Use **Assets → Import Package → Custom Package** e selecione o arquivo.
4. Confira as cenas `Assets/Scenes/Menu.unity` e `Assets/Scenes/Scene1.unity`, as referências no Inspector e as tags usadas pelos scripts.
5. Inclua as cenas na lista de cenas da compilação para permitir a navegação pelo menu.

O pacote não contém `ProjectSettings` nem `Packages`, portanto a versão original do editor e todas as configurações do projeto não estão registradas. Pode ser necessário ajustar dependências, tags e configurações de entrada. Os controles usam a API clássica `UnityEngine.Input`.

## O que há no pacote

- Cenas de menu e jogo.
- Scripts C# de movimentação, obstáculos, geração de itens e interface.
- Assets e referências usados pelo protótipo.

O arquivo `Player.cs` reúne as regras de vida, energia e movimentação; os scripts `HealthBar`, `DistanceBar` e `BoostBar` controlam os indicadores.

**Estado:** protótipo distribuído em `.unitypackage`, sem executável publicado neste repositório.
