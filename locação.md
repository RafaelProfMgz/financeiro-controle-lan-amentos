### 1. Definição das Contas (Plano de Contas)

Para o sistema funcionar, você precisa destas categorias:

- **Entrada de Aluguel (Transitória):** Valor bruto que entra do inquilino.
- **Receita de Taxa de Administração:** O seu ganho (os 10%).
- **Repasse a Proprietários:** O valor que deve sair para o dono.
- **Comissão de Corretor (Custo Variável):** O que você paga para quem captou ou administra.

---

### 2. Exemplo Prático (Fluxo de Lançamentos)

**Dados do Exemplo:**

- Aluguel: R$ 1.000,00
- Taxa Adm: 10% (R$ 100,00)
- Comissão Corretor: 20% _sobre a taxa de adm_ (R$ 20,00)

#### Passo 1: O Recebimento (Entrada)

Quando o inquilino paga o boleto de R$ 1.000,00:

- **Lançamento:** Entrada no Banco.
- **Categoria:** Aluguel a Repassar (Passivo).
- **Saldo no Banco:** + R$ 1.000,00.

#### Passo 2: O "Desmembramento" (A mágica da organização)

No momento que o dinheiro entra, você já deve "fatiar" esse valor dentro do sistema:

- **Lançamento A (O que é do dono):** R$ 900,00 (Categoria: Repasse ao Proprietário).
- **Lançamento B (O que é seu):** R$ 100,00 (Categoria: Receita de Taxa de Administração).

#### Passo 3: O Pagamento ao Proprietário (Saída)

Você transfere os R$ 900,00 para o dono:

- **Lançamento:** Saída do Banco.
- **Categoria:** Repasse ao Proprietário (Baixa do passivo).
- **Saldo no Banco agora:** R$ 100,00 (Exatamente a sua comissão).

#### Passo 4: Pagamento do Corretor (Custo)

Se o corretor ganha uma parte dessa taxa de R$ 100,00:

- **Lançamento:** Saída do Banco de R$ 20,00.
- **Categoria:** Comissão de Corretores.
- **Saldo Final Real na conta:** R$ 80,00 (Seu lucro bruto antes de impostos e despesas fixas).

# A verificar:

### Dicas Extras para o seu Sistema:

- **Tratamento de Impostos (IRRF):** Lembre-se que se o locador for Pessoa Física e o locatário Pessoa Jurídica, há retenção de Imposto de Renda. O sistema precisa prever um campo para "Descontos" (como IRRF ou Benfeitorias feitas pelo inquilino).
- **Taxa de Boleto:** Se você cobra a taxa do boleto do inquilino (ex: R$ 5,00), essa entrada deve ser categorizada como "Reembolso de Taxa Bancária" para zerar a despesa que o banco vai te cobrar.
- **Multas e Juros:** Se o inquilino pagar com atraso, você precisa definir se a multa vai 100% para o dono ou se a imobiliária fica com uma parte.

**Resumo do saldo final no seu exemplo:**
Se você recebeu R$ 1.000, pagou R$ 900 pro dono e o corretor ainda não foi pago, seu sistema tem que acusar:

- **Saldo em conta:** R$ 100,00.
- **Contas a pagar:** R$ 20,00 (Corretor).
- **Lucro Projetado:** R$ 80,00.
