# 🧠 Primeiros Prompts: Explorando a Imaginação com Engenharia de Prompt

## 📚 Navegação

📂 [`documentacao-de-criacao/`](../)  
└── 📁 [`02-capa/`](./README.md)  
&emsp;&emsp;├── [`01-processo-criativo.md`](./01-processo-criativo.md)  
&emsp;&emsp;└── [`02-capas-geradas-por-ia.md`](./02-capas-geradas-por-ia.md)

> *Neste documento, mergulhamos nos primeiros passos da criação visual utilizando técnicas de prompt para gerar a capa do livro com IA.*

---

## 🎨 Contexto da Criação

A imagem da capa deveria idealmente ser gerada no **Midjourney**, ferramenta conhecida por sua alta qualidade de composição visual. No entanto, por se tratar de um serviço pago, optou-se por utilizar alternativas gratuitas:

- `Meta.ai`
- `ChatGPT`
- `Microsoft Copilot`

**Resultado comparativo:**

| Ferramenta         | Desempenho na geração da capa                                  |
|--------------------|---------------------------------------------------------------|
| **ChatGPT**        | Geração de prompt altamente satisfatória e coerente            |
| **Meta.ai**        | Produziu imagens em modo paisagem (horizontal), não ideal      |
| **Copilot**        | Resultados interessantes, mas com menor precisão visual        |

As imagens geradas por essas ferramentas serão apresentadas no próximo arquivo: [`02-capas-geradas-por-ia.md`](./02-capas-geradas-por-ia.md).

---

## ✍️ Interação com ChatGPT: Criação do Prompt

Foi realizada uma solicitação ao modelo ChatGPT com base em um contexto previamente definido, composto pelo título e subtítulo do livro. Tal abordagem caracteriza o uso da técnica de Contextual Prompting, permitindo ao modelo compreender de forma precisa a proposta temática da obra. Além disso, pode-se observar a aplicação implícita da técnica de Role Prompting, já que o modelo adotou uma postura de especialista em design editorial com foco em ficção científica e tecnologia.

A seguir, reproduz-se a solicitação original:

```
Título: Angular Jedi: Dominando o Império do TypeScript
Subtítulo: Uma jornada prática rumo ao domínio da Força do Front-end Moderno

Agora imagine uma capa para esse livro. Quais elementos devem ter que fazem sentido para esse livro?
```

Em resposta, o modelo apresentou uma composição rica e estruturada de elementos visuais

```
Excelente escolha de título e subtítulo — agora sim estamos no caminho certo para algo marcante! Para criar uma **capa visualmente impactante e coerente com o tema**, aqui estão os **elementos que devem estar presentes**, seguidos de ideias para você usar no Midjourney ou com um designer:

---

### 🎨 **1. Paleta de Cores**

* **Cores dominantes**: tons escuros como **preto**, **roxo profundo**, **azul cósmico** ou **cinza metálico**.
* **Destaques**: **vermelho**, **laranja** ou **amarelo neon** para contrastes de energia (remetendo à Força, luzes de sabre, poder do TypeScript).

---

### 🧑‍🚀 **2. Personagem Principal – O Angular Jedi**

* Figura estilizada de um **“Jedi programador”**, com capa e sabre de luz.
* O **sabre de luz pode ser estilizado como um cursor de código**, ou até ter um brilho com ícones de código (ex: `</>` ou `{}`).
* O **rosto não precisa estar visível** (estilo misterioso, tipo "dev anônimo").

---

### 💻 **3. Elementos de Programação**

* Linhas de **código TypeScript** flutuando no fundo ou no sabre.
* **Componentes visuais de Angular**, como o **ícone do Angular (A em vermelho)** e **ícones como `<app-component>` ou `@Component()`** inseridos sutilmente.
* Uma **janela de editor de código flutuando no espaço**, como se o Jedi estivesse “dominando” aquele ambiente.

---

### 🪐 **4. Cenário / Fundo**

* **Ambiente espacial ou galáctico**: nebulosas, estrelas, uma galáxia em segundo plano.
* **Arquitetura futurista** como uma “base do Império” feita de circuitos ou componentes (fazendo analogia ao sistema Angular).
* Planetas com nomes estilizados como "TypeScript Prime" ou "NgWorld" (bem sutil).

---

### 🧠 **5. Tipografia**

* Fonte futurista, com um toque de **tecnologia e ficção científica**.
* Título em destaque com brilho leve ou contorno iluminado (como se tivesse energia da Força).
* Subtítulo menor, em uma fonte mais limpa e moderna para contraste.

---

### 💡 **Exemplo de descrição para o Midjourney** (em inglês, se for usar lá):

> *A futuristic Jedi developer wearing a cloak, holding a glowing code lightsaber with TypeScript code symbols, standing in front of a galactic battlefield with floating UI components and code windows, deep space background with stars and planets, Angular logo glowing behind, cinematic lighting, digital art, dark sci-fi color palette*
```

Após a sugestão conceitual inicial da imagem de capa, foi realizada uma nova solicitação ao modelo, com o objetivo de obter uma versão refinada e operacional do prompt, pronta para utilização direta em uma ferramenta generativa (Midjourney). Essa abordagem caracteriza o uso da técnica de Prompt de Finalização Sintética, que consiste em transformar uma descrição abstrata em um comando executável com especificações compatíveis com plataformas de geração visual por IA.

O enunciado enviado ao modelo foi:

```
Gostaria de uma versão pronta desse prompt
```

O modelo retorna com a seguinte resposta:

```
Perfeito! Aqui está uma **versão pronta do prompt** para você usar diretamente no **Midjourney**, ideal para gerar a capa do seu ebook **"Angular Jedi: Dominando o Império do TypeScript"**:

---

### 🎯 \*\*Prompt Midjourney (em inglês):

>

**"A futuristic Jedi developer in a hooded cloak, holding a glowing blue lightsaber shaped like a code editor cursor, TypeScript code symbols floating in the air, standing on a space station balcony overlooking a galaxy, Angular logo glowing behind like a hologram, digital sci-fi interface elements in the background, dark space atmosphere with stars and nebulae, cinematic lighting, ultra-detailed, concept art style, 16:9 ratio"**

>

**--v 6 --ar 16:9 --style cinematic --q 2 --quality 2 --stylize 1000**

---

### 🔍 Detalhes incluídos:

* **"futuristic Jedi developer"**: Representa o "Angular Jedi".
* **"glowing blue lightsaber shaped like a code editor cursor"**: Une sabre de luz + mundo da programação.
* **"TypeScript code symbols floating"**: Reforça o conteúdo técnico.
* **"Angular logo glowing behind like a hologram"**: Referência direta ao framework.
* **"space station balcony" + "galaxy"**: Atmosfera épica e galáctica.
* **"cinematic lighting" + "concept art style"**: Aparência profissional, ideal para capa.
* **"--ar 16:9"**: Proporção ideal para capa de ebook widescreen.

```

---

## 🧩 Considerações

A construção desse prompt se mostrou um excelente exemplo de como técnicas de engenharia podem ser utilizadas mesmo em interações espontâneas e naturais. A **clareza na proposta**, combinada com **o contexto do livro**, permitiu que o modelo entregasse uma descrição visual **sofisticada e funcional**.

> 🎯 *No próximo arquivo, veremos como cada ferramenta traduziu essas ideias em imagem.*

---

## 🔗 Navegação Rápida

➡️ [Avançar para `02-capas-geradas-por-ia.md`](./02-capas-geradas-por-ia.md)  
⬅️ [Retornar à introdução da etapa `02-capa`](./README.md)  
🔙 [Voltar para o README principal do repositório](../README.md)
