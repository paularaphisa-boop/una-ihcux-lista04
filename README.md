O que é Prevenção de Erros (Heurística de Nielsen)

A Prevenção de Erros é uma das heurísticas de usabilidade definidas por Jakob Nielsen.

"O sistema deve evitar que erros aconteçam, ao invés de apenas mostrar mensagens depois que eles ocorrem."

🔗 Conexão entre try-catch e Prevenção de Erros

Embora o try-catch seja uma ferramenta técnica e a heurística seja um princípio de UX, eles se conectam diretamente:

⚠️ 1. try-catch NÃO previne o erro
Ele não impede que o erro aconteça
Ele reage ao erro depois que ele ocorre

👉 Ou seja: é mais tratamento do que prevenção

✅ 2. Mas ele evita falhas graves no sistema

Sem try-catch:

O sistema pode quebrar
A aplicação pode parar
O usuário pode perder dados

Com try-catch:

O erro é controlado
O sistema continua funcionando
O usuário recebe um feedback amigável

👉 Isso melhora a experiência e reduz impacto do erro

🛡️ 3. Ele complementa a Prevenção de Erros

A prevenção real acontece com coisas como:

Validação de formulário (ex: impedir campo vazio)
Máscaras de input
Confirmações antes de ações críticas

Já o try-catch entra como última linha de defesa:

👉 Quando a prevenção falha, ele garante que o erro seja tratado corretamente.
