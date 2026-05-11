Nexar - Landing Page SaaS (IA & Dados) 🚀

Este projeto contém o código-fonte de uma landing page premium, desenvolvida com padrões de design de alto nível (padrão Silicon Valley), ideal para startups de Tecnologia, Inteligência Artificial e plataformas SaaS (Software as a Service).

O design utiliza uma abordagem "Dark-Tech" moderna, com efeitos visuais avançados, tipografia arrojada e uma estrutura arquitetónica focada na inovação e na conversão.

✨ Funcionalidades em Destaque

Design "Dark-Tech" & Glassmorphism: Interface escura profunda com elementos translúcidos, menus flutuantes e efeitos de luz/brilho (glow) dinâmicos.

Grelha "Bento Box": Layout assimétrico moderno para a secção de funcionalidades, oferecendo uma hierarquia visual muito mais interessante que o padrão clássico de 3 colunas.

Simulação de Dashboard em CSS: A secção principal (Hero) inclui uma simulação de interface animada construída 100% com CSS (sem imagens pesadas). Este elemento reage de forma 3D ao movimento do rato em ecrãs de computador.

Efeito "Spotlight" Dinâmico: Os cartões da grelha de funcionalidades possuem um rastreador JavaScript que ilumina subtilmente o fundo do cartão, acompanhando com precisão a posição do cursor do rato.

Menu Mobile em Ecrã Inteiro: Navegação para telemóveis totalmente otimizada através de um overlay de ecrã inteiro com efeito de vidro fosco (blur).

Animações de Alta Performance: Efeitos de revelação ao fazer scroll, criados nativamente com IntersectionObserver para garantir máxima fluidez sem bibliotecas pesadas.

🛠️ Tecnologias Utilizadas

Projeto construído puramente com tecnologias web fundamentais (Vanilla - Zero dependências externas):

HTML5: Estrutura semântica otimizada.

CSS3: Variáveis CSS (Custom Properties), Flexbox, CSS Grid, Animações Keyframes e funções de gradiente complexas.

JavaScript (Vanilla): Lógica do menu mobile, Scroll Reveal e cálculos interativos de coordenadas X/Y (para os efeitos 3D e Spotlight).

Google Fonts: Space Grotesk (Para títulos com aspeto tecnológico) e Inter (Para máxima legibilidade no corpo do texto).

🚀 Como Utilizar

A configuração é imediata, não requerendo ferramentas de build ou servidores locais:

Faça o download do ficheiro HTML gerado (novasync.html ou index.html).

Dê um duplo clique no ficheiro para o abrir diretamente no seu navegador web preferido (Chrome, Firefox, Safari, Edge).

Para editar o conteúdo, basta abrir o ficheiro em qualquer editor de código (como o Visual Studio Code, Sublime Text, etc.).

🎨 Como Personalizar (Tema e Cores)

Toda a identidade visual (Cores, Fontes e Tamanhos) é gerida por Variáveis CSS globais no topo do código. Pode transformar completamente a paleta da landing page alterando os valores na secção :root:

:root {
    /* Cores de Fundo */
    --bg-base: #030712;      /* Cor de fundo principal */
    --bg-card: #0f172a;      /* Fundo dos cartões e elementos elevados */
    
    /* Cores de Destaque (Controlam os botões, gradientes e brilhos) */
    --primary: #06b6d4;      /* Cyan */
    --secondary: #8b5cf6;    /* Roxo / Violeta */
    --accent: #ec4899;       /* Rosa */
    
    /* Tipografia */
    --font-heading: 'Space Grotesk', sans-serif;
    --font-body: 'Inter', sans-serif;
}


Altere os códigos hexadecimais ao seu gosto, guarde o ficheiro e atualize o navegador para ver o seu novo tema aplicado instantaneamente!

📄 Licença

Este código é disponibilizado de forma aberta. Sinta-se à vontade para o modificar, estudar ou utilizar como rampa de lançamento para a sua próxima grande startup de tecnologia.
