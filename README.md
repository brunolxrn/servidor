# Minecraft Crossplay Server — Java + Bedrock

Paper + GeyserMC + Floodgate para permitir Java e Bedrock no mesmo servidor.

## Hospedagem

O repositório armazena toda a configuração. O workflow do GitHub Actions consegue executar o servidor em um runner temporário, mas **não mantém um servidor 24/7**. Para acesso público durante a execução, configure um túnel como Playit.gg usando o secret `PLAYIT_AUTH`.

## Iniciar
1. Vá em **Actions → Minecraft Crossplay Server → Run workflow**.
2. Para acesso pela Internet, crie um secret chamado `PLAYIT_AUTH` com o token do seu túnel.
3. Java usa a porta TCP fornecida pelo túnel; Bedrock usa a porta UDP fornecida pelo túnel.

## Componentes
- Paper
- Geyser-Spigot
- Floodgate
- GitHub Actions
