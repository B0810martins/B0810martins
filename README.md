## Olá 👋
Link do site: Gato de Schrödinger
https://gatodeschrodinger.netlify.app
<!--<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>🧬 Gato de Schrödinger: Paradoxo Quântico Completo 🧬</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #0f0f23 0%, #1a0033 50%, #330066 100%);
            color: #ffffff;
            margin: 0;
            padding: 20px;
            min-height: 100vh;
            overflow-x: hidden;
        }
        .container {
            max-width: 1400px;
            margin: 0 auto;
            background: rgba(0, 0, 0, 0.85);
            border-radius: 25px;
            padding: 40px;
            box-shadow: 0 0 60px rgba(138, 43, 226, 0.6);
            border: 3px solid #8a2be2;
            position: relative;
        }
        .container::before {
            content: '';
            position: absolute;
            top: -5px; left: -5px; right: -5px; bottom: -5px;
            background: linear-gradient(45deg, #ff00ff, #00ffff, #ff00ff);
            border-radius: 30px;
            z-index: -1;
            animation: rotate 4s linear infinite;
        }
        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        h1 {
            text-align: center;
            color: #ff00ff;
            text-shadow: 0 0 30px #ff00ff, 0 0 60px #00ffff;
            font-size: 3.5em;
            margin-bottom: 15px;
            animation: glow 2s ease-in-out infinite alternate;
        }
        @keyframes glow {
            from { text-shadow: 0 0 20px #ff00ff, 0 0 40px #00ffff; }
            to { text-shadow: 0 0 40px #ff00ff, 0 0 80px #00ffff; }
        }
        h2 {
            color: #00ffff;
            text-shadow: 0 0 15px #00ffff;
            border-left: 6px solid #00ffff;
            padding-left: 25px;
            margin-top: 40px;
            font-size: 2em;
        }
        .paradoxo {
            background: rgba(255, 0, 255, 0.15);
            padding: 25px;
            border-radius: 20px;
            border: 2px solid #ff00ff;
            margin: 25px 0;
            position: relative;
            overflow: hidden;
        }
        .paradoxo::before {
            content: '🌀 SUPERPOSIÇÃO QUÂNTICA 🌀';
            position: absolute;
            top: -50px; right: -50px;
            color: rgba(0, 255, 255, 0.3);
            font-size: 1.5em;
            transform: rotate(45deg);
        }
        .superposicao {
            background: linear-gradient(90deg, #00ff00, #ff0000, #00ff00);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            font-size: 1.8em;
            font-weight: bold;
            text-align: center;
            animation: shimmer 3s infinite;
        }
        @keyframes shimmer {
            0%, 100% { filter: hue-rotate(0deg); }
            50% { filter: hue-rotate(180deg); }
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            background: rgba(0, 255, 255, 0.12);
            margin: 12px 0;
            padding: 20px;
            border-radius: 15px;
            border-left: 6px solid #00ffff;
            transition: all 0.4s ease;
            position: relative;
        }
        li::before {
            content: '⚛️';
            margin-right: 10px;
        }
        li:hover {
            background: rgba(0, 255, 255, 0.25);
            box-shadow: 0 0 25px rgba(0, 255, 255, 0.6);
            transform: translateX(10px);
        }
        .box {
            background: linear-gradient(45deg, #222, #444);
            border: 4px dashed #ff00ff;
            padding: 40px;
            margin: 30px 0;
            text-align: center;
            position: relative;
            animation: pulse 3s infinite;
            border-radius: 20px;
        }
        .box::after {
            content: '🔒 FECHADA 🔒';
            position: absolute;
            top: 10px; right: 20px;
            color: #ff00ff;
            font-weight: bold;
            text-shadow: 0 0 10px #ff00ff;
        }
        @keyframes pulse {
            0%, 100% { box-shadow: 0 0 30px #ff00ff; }
            50% { box-shadow: 0 0 60px #00ffff; transform: scale(1.02); }
        }
        .interpretacoes {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        .interpretacao {
            background: rgba(255, 165, 0, 0.15);
            border: 2px solid #ff8c00;
            padding: 25px;
            border-radius: 20px;
            text-align: center;
        }
        .interpretacao h3 {
            color: #ff8c00;
            text-shadow: 0 0 15px #ff8c00;
        }
        .timeline {
            position: relative;
            max-width: 1000px;
            margin: 40px auto;
            padding: 20px 0;
        }
        .timeline::before {
            content: '';
            position: absolute;
            left: 50%;
            top: 0;
            bottom: 0;
            width: 4px;
            background: linear-gradient(to bottom, #ff00ff, #00ffff);
            transform: translateX(-50%);
        }
        .evento {
            position: relative;
            width: 45%;
            padding: 20px;
            background: rgba(0, 255, 255, 0.1);
            border-radius: 15px;
            margin-bottom: 30px;
        }
        .evento.left {
            left: 5%;
            border-left: 5px solid #00ffff;
        }
        .evento.right {
            left: 50%;
            border-right: 5px solid #ff00ff;
        }
        .ano {
            font-size: 2em;
            color: #ff00ff;
            text-shadow: 0 0 10px #ff00ff;
        }
        footer {
            text-align: center;
            margin-top: 50px;
            color: #aaa;
            font-size: 1em;
            padding: 20px;
            border-top: 1px solid #8a2be2;
        }
        @media (max-width: 768px) {
            .timeline::before { left: 20px; }
            .evento { width: calc(100% - 40px); left: 40px !important; }
            .evento.right { left: 40px !important; }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🐱 GATO DE SCHRÖDINGER 🐱</h1>
        <p class="superposicao">VIVO E MORTO SIMULTANEAMENTE? ⚛️</p>
        
        <div class="paradoxo">
            <h2>🧪 O Experimento Mental Completo</h2>
            <div class="box">
                <h3>📦 COMPONENTES DA CAIXA:</h3>
                <ul style="text-align: left; display: inline-block;">
                    <li>🐱 Gato vivo</li>
                    <li>☢️ Átomo radioativo (50% chance de decair em 1h)</li>
                    <li>📡 Contador Geiger</li>
                    <li>🔨 Martelo acionado por relés</li>
                    <li>💀 Frasco de veneno (ex: cianeto)</li>
                </ul>
                <p><strong>RESULTADO:</strong> Até abrir a caixa, o gato existe em <span class="superposicao">SUPERPOSIÇÃO QUÂNTICA</span>.</p>
            </div>
        </div>

        <h2>📜 História e Contexto</h2>
        <div class="timeline">
            <div class="evento left">
                <div class="ano">1935</div>
                <p><strong>Erwin Schrödinger</strong> publica artigo criticando <em>Interpretação de Copenhague</em> de Niels Bohr e Werner Heisenberg.</p>
            </div>
            <div class="evento right">
                <div class="ano">1935</div>
                <p>Inspirado em debates com <strong>Albert Einstein</strong> sobre limites quântico-clássico.</p>
            </div>
            <div class="evento left">
                <div class="ano">1964</div>
                <p><strong>John Bell</strong> desenvolve teoremas que testam interpretações quânticas.</p>
            </div>
            <div class="evento right">
                <div class="ano">2020s</div>
                <p>Experimentos reais confirmam superposição em moléculas maiores.</p>
            </div>
        </div>

        <h2>🔬 Interpretações da Mecânica Quântica</h2>
        <div class="interpretacoes">
            <div class="interpretacao">
                <h3>🌊 Copenhague</h3>
                <p>Função de onda colapsa ao observar. Gato vivo OU morto após abrir caixa.</p>
            </div>
            <div class="interpretacao">
                <h3>🌌 Muitos Mundos</h3>
                <p>Universos se ramificam: um com gato vivo, outro morto. Ambos existem.</p>
            </div>
            <div class="interpretacao">
                <h3>📐 Bohmiana</h3>
                <p>Partículas têm trajetórias definidas, superposição é ilusão.</p>
            </div>
            <div class="interpretacao">
                <h3>🎲 QBismo</h3>
                <p>Probabilidades refletem crenças do observador.</p>
            </div>
        </div>

        <h2>⚛️ Conceitos Quânticos Essenciais</h2>
        <ul>
            <li><strong>Superposição:</strong> Sistemas quânticos em múltiplos estados simultâneos até medição.</li>
            <li><strong>Entrelaçamento:</strong> Partículas correlacionadas instantaneamente, independentemente da distância.</li>
            <li><strong>Colapso da Função de Onda:</strong> Medição força escolha de um estado definido.</li>
            <li><strong>Princípio da Incerteza:</strong> Impossível conhecer posição e momento simultaneamente com precisão.</li>
        </ul>

        <h2>🌍 Impacto Científico e Cultural</h2>
        <ul>
            <li>Inspirou <strong>experimentos reais</strong> com superposição em sistemas macroscópicos.</li>
            <li>Popularizou física quântica em <strong>memes, filmes e literatura</strong> (Matrix, Big Bang Theory).</li>
            <li>Base para <strong>computação quântica</strong> e tecnologias emergentes.</li>
            <li>Schrödinger ganhou <strong>Nobel de Física em 1933</strong> pela equação fundamental da mecânica quântica.</li>
        </ul>

        <footer>
            Paradoxo Quântico © 1935 | Feito para mentes curiosas
        </footer>
    </div>
</body>
</html>

**B0810martins/B0810martins** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
