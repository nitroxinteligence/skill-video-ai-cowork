---
name: skill-video-ai-cowork
description: "Criar briefing, roteiro, plano de captação e edição de vídeo. Use em Tráfego / Conteúdo."
metadata:
  departamento: trafego
  especialista: ann-handley
  skill-id: TRF-CON-03
---
# video

## Especialista e contexto

Ative a orientação de [Ann Handley - Conteúdo](references/especialista.md) para esta habilidade. Leia o arquivo [references/especialista.md](references/especialista.md) antes de executar. A identidade é de IA com atribuição; o resultado deve refletir o método, não inventar a pessoa real.

Leia o contexto real da empresa fornecido pelo usuário para resolver dados de negócio, caminhos e dependências. Use os dados do pedido e as notas pertinentes já existentes; não invente um perfil do fundador.

## Procedimento

Leia [o procedimento de origem](references/upstream/procedimento.md) e carregue suas referências conforme a tarefa. Preserve a profundidade das etapas, critérios e exemplos; adapte a saída para PT-BR e para o negócio real.

## Adaptação ao OS

Leve: separar roteiro, geração de assets e publicação em gates.

As instruções desta camada de integração resolvem os caminhos/limites do pacote: contexto em `.agents/product-marketing.md`, `.agents/sales-context.md` ou `BUSINESS_CONTEXT.md` significa o contexto do projeto atual, se existente. Não crie esses arquivos nem migre notas só para satisfazer um caminho do fornecedor. Saídas usam o destino pedido pelo usuário; caminhos de exemplo do autor não são destinos obrigatórios. Marcas, serviços e equipes citados como exemplo pertencem ao autor, não ao usuário.

Referências a outras skills são rotas opcionais: consulte outras skills disponíveis no workspace e use a habilidade disponível pertinente. Não declare integração ativa por existir uma referência. Contas externas e ferramentas só são necessárias para as operações que as usam; uma análise ou rascunho pode usar dados fornecidos. Aplique a autorização existente sem exigir confirmações repetidas.

Números, benchmarks, políticas e limites dos exemplos não são fatos atuais do caso: confira fontes e data quando determinarem a recomendação. Não afirme garantia de conversão, receita, certificação ou conformidade por usar o método.

## Proveniência

Origem: [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills/blob/5b2c0007766c6a1cf1d53fd8fc73e979e0821022/skills/video/SKILL.md). Commit `5b2c0007766c6a1cf1d53fd8fc73e979e0821022`. Licença MIT em [LICENSE](LICENSE). Adaptação: integração de contexto, especialista, destino e limites no OS; procedimento de origem adaptado como referência; a licença é preservada, e correções estão registradas no relatório de revisão.


## Verificação de uso

Entrada: prova de cliente e objetivo. Saída: roteiro de 90s, shot list e plano de edição; claims sem prova ficam marcados, não inventados.

Este cenário é um exemplo de teste, não um requisito universal para pedidos reais. Respeite o escopo solicitado; não invente entradas ou opções só para cumprir o exemplo. Registre o artefato real quando exercitado.
