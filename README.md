# Puzzler
Starter project for the Udacity [VR Developer Nanodegree](http://udacity.com/vr) program.

- Course: VR Design
- Project: Puzzler


### Versions Used
- [Unity LTS Release 2017.4.15](https://unity3d.com/unity/qa/lts-releases?version=2017.4)
- [GVR SDK for Unity v1.170.0](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.170.0)
- [iTween](https://assetstore.unity.com/packages/tools/animation/itween-84) v2.0.9


### Directory Structure
- The Unity project is the child directory of the repository and named according to the associated lesson.
- The Unity project is 'cleaned' and includes the `Assets` folder, the `ProjectSettings` folder, and the `UnityPackageManager` folder.


### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is included.
- The `Max Reticle Distance` value for the `GvrReticlePointer` used in the scene is set to `20` instead of the default `10`.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.170.0, make sure you accept any API update pop-up prompts triggered by Unity. Alternatively, you can manually run the API updater (Unity menu `Assets` > `Run API Updater...`) after the import has completed.


### Related Repositories
- [VR Design - Intro to VR Design](https://github.com/udacity/VR-Design_Intro-to-VR-Design/releases)
- [VR Design - Movement Mechanics](https://github.com/udacity/VR-Design_Movement-Mechanics/releases)
- [VR Design - Presenting the Work](https://github.com/udacity/VR-Design_Presenting-the-Work/releases)
- VR Design - Puzzler

# PROJETO ENIGMA - APRENDENDO A APRESENTAR UM PROJETO DE REALIDADE VIRTUAL
### SOBRE O PROJETO
- Enigma é um projeto proposto no curso VR Software Development da Udacity para aprender a documentar e apresentar um projeto de realidade virtual. Adicionalmente, quero despertar o interesse de amigos e familiares pela realidade virtual, e entretê-los.
### SOBRE O APLICATIVO
- O usuário se encontra no meio de montanhas e entra em uma masmorra ao clicar em iniciar. Para ganhar o jogo e sair da masmorra, deve memorizar o padrão de acendimento dos orbes e reproduzir o mesmo padrão logo em seguida. Depois de ganhar o jogo, o usuário tem a opção de reiniciar o jogo.
### PROCESSO DE DESENVOLVIMENTO
- Primeiramente, criei um persona, um usuário final fictício que utilizaria o aplicativo. No geral, quem teria contato com o aplicativo seriam meu marido e meus amigos, que tem muita experiência com produção multimídia mas pouca experiência com realidade virtual.
- HJL, 27 anos, designer-gráfico, gosta de video games e tecnologia mas não gosta de experiências que causam náusea ou desconforto.
- “Quero me divertir e ter experiências novas mas não gosto de passar mal e me preocupo com minha saúde.”
- Depois criei esboços iniciais – ambientes exterior e interior, interfaces de usuário de início e fim
- Construí a cena com os objetos Prefab de pedaços e itens de uma masmorra.
- e configurei o humor do ambiente com point lights e spotlight. Marquei os objetos como estáticos e preparei a iluminação para deixar a aplicação mais leve, sem iluminação em tempo real ou sombras.

### Teste de Usuário 1
- proporcionalidade, rotação da cabeça e sensação do ambiente
- Fiz perguntas ao usuário para obter informações para melhorar na próxima iteração.
- Qual seu tamanho nesse ambiente? O usuário relatou que se sentia como um anão no ambiente;
- O que sente do ambiente? causa a sensação de estar na idade média e parece que vai entrar um monstro pela porta;
- Relatou desconforto visual por causa da sensibilidade da rotação da cabeça

### continuando...
- coloquei os orbes na cena, as interfaces de usuário para iniciar e reiniciar o jogo e testei a mecânica de movimento.

### Teste de Usuário 2
- Leitura das interfaces e movimentação dentro do jogo
- Todas as informações estão legíveis, os botões funcionam e o movimento não causa desconforto ou sensação de colisão.
- Usuário não consegue saber como se joga esse jogo.

### AJUSTES FINAIS
- Os scripts para a lógica do jogo já foram fornecidos pela Udacity para este projeto. Os orbes piscam em um padrão aleatório, emitindo um som quando acende.
- Quando o usuário aponta para o orbe, ele muda de cor. O orbe toca o mesmo tom quando é o orbe certo e um som feio quando é o errado. - - Quando se erra, a mesma sequência se repete.
- Acrescentei ainda um som de sucesso! quando se ganha o jogo, que não estava dentro das instruções do projeto. Também reescrevi os textos em português e acrescentei uma instrução para o jogo na interface inicial.
- O tutorial é para um aplicativo de cardboard, mas como tenho um daydream, procurei tutoriais, documentações e demos da Google VR e adaptei o jogo para o Daydream, que tem um controle na mão para apontar e clicar.

### Teste de Usuário Final
- Game play
- Usuário repetiu o jogo várias vezes e não sentiu enjoo ou desconforto durante a experiência.
Se divertiu muito!

### CONCLUSÃO
- Aprendi a importância e o método da documentação dos projetos. E também a fazer os esboços das ideias e as vantagens de testar cedo e frequentemente.
- Assim eu posso mostrar o processo dos meus trabalhos para o mundo e meus projetos não vão se perder ao longo do tempo.
- Fazer o teste de usuário foi muito divertido e construtivo. Tive a oportunidade de mostrar meu trabalho para meus amigos e eles se divertiram.
- Este projeto foi muito Gratificante e pretendo fazer a documentação de todos os meus projetos de Realidade Virtual.

### DE AGORA EM DIANTE…
- Todos os amigos que vierem me visitar vão ser convidados a ser beta-testers não remunerados e vou anotar o feedback para ir melhorando essa experiência e já levar em conta para o design das próximas aplicações!

