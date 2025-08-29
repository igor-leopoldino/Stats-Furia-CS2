Esse projeto prático passou por todas as etapas: pegar os dados atualizados do site hltv.org e levá-los para dentro do ambiente do Google Colab para tratá-los.

Após a importação e tratamento das informações, fiz algumas linhas de código para uma rápida análise dos jogadores e seus respectivos K/Ds e Ratings em 2025, do T-Side e CT-Side.

Após isso, salvei os dataframes em formato CSV e subi para o Power BI para uma análise mais visual.

No Power BI fiz alguns tratamentos básicos nos dados para deixá-los prontos para o dashboard.

Adicionei as informações necessárias aos gráficos e por fim salvei em PDF.

Fiz o upload do código em Python, o arquivo Power BI e o PDF salvo, no Github para deixar tudo em nuvem.

Com essas informações percebi que: 
- o T-side da Furia é muito mais "equilibrado" que o CT-side (que é um tanto quanto mais dependente de Molodoy e Kscerato);
existe uma diferença de 0.02 de Rating entre os lados (a mais para o CT);
- o K/D de Fallen e Yekindar são um tanto quanto mais baixos em relação ao resto do time, porém isso se dá pelas funções que cada um designa no time (doando-se mais) em algumas situações. São dados baixos, porém que precisam ser levados em consideração, que é completamente normal.
- quaisquer jogadores que vão mais para o combate, tendem a morrer mais, porém abrem um espaço bom para o time, que não são mostrados nos dados.
