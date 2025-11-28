<h1 align="center">🌿 Jardim AR – Visualizador de Plantas</h1>

<p align="center">
  Uma experiência imersiva para visualizar plantas em <b>3D</b> e <b>Realidade Aumentada</b> direto no navegador.
  <br>
  Explore modelos, descubra detalhes botânicos e teste como elas ficam na sua casa.
</p>

<p align="center">
  <a href="#-funcionalidades">Funcionalidades</a> •
  <a href="#-demonstração">Demonstração</a> •
  <a href="#-tecnologias-utilizadas">Tecnologias</a> •
  <a href="#-como-executar-localmente">Como Executar</a> •
  <a href="#-autor">Autor</a>
</p>

---

## 🔗 Acesse o Projeto

<div align="center">

### [🌐 Clique aqui para ver a Versão Online](https://jade-paz.github.io/RA/index.html)

</div>

---

## 🚀 Funcionalidades

### ✔ Visualização 3D
- Modelos `.glb` otimizados e realistas.
- Controles de **Zoom**, **Rotação** e **Interação fluida**.

### ✔ Realidade Aumentada (AR)
- Compatível com **WebXR**, **Scene Viewer** (Android) e **Quick Look** (iOS).
- Projeção da planta no ambiente real usando a câmera do celular.
- Rastreamento de superfície estável.

### ✔ Informações Botânicas
Cada planta possui uma ficha técnica interativa contendo:
- 📛 Nome comum e científico
- 📝 Descrição breve
- ☀ Tipo de luz e Ambiente ideal
- 💧 Frequência de rega
- ✨ Benefícios da espécie

### ✔ Interface Amigável
- Cards elegantes com preview 3D.
- Carrosséis horizontais para navegação.
- Modais informativos e tutoriais de uso integrados.

---

## 📸 Demonstração

> **Nota:** As imagens abaixo são ilustrativas do projeto.

<div align="center">
  <img src="assets/plant.png" alt="Preview da aplicação" width="300">
  <img src="assets/plant1.png" alt="Card de planta" width="300">
  <img src="assets/plant2.png" alt="Modo AR" width="300">
</div>

---

## 🛠 Tecnologias Utilizadas

| Tecnologia | Função / Uso |
| :--- | :--- |
| **HTML5** | Estrutura semântica do projeto |
| **CSS3** | Estilização, UI moderna e responsividade |
| **JavaScript** | Lógica da aplicação, manipulação do DOM e modais |
| **Model Viewer** | Componente do Google para renderização 3D e WebXR |
| **A-Frame** | Framework para experiências VR/AR (experimentos) |
| **MediaPipe** | Rastreamento de mãos (Hands Tracking) |
| **Sketchfab** | Fonte dos modelos 3D (GLB/GLTF) |

---

## 📂 Estrutura do Projeto

```bash
📁 RA
│
├── 📄 modelos.html       # Página principal (Galeria e AR)
├── 📄 camera.html        # Experimentos de câmera
├── 📄 camera2.html       # Experimentos secundários
│
├── 🎨 style.css          # Estilos principais
├── 🎨 style2.css         # Estilos experimentais
│
├── 📁 assets             # Pasta de recursos
│   ├── 📦 monstera.glb
│   ├── 📦 indoor_plant.glb
│   ├── 📦 rhyzome_plant.glb
│   ├── 📦 blanket_phlox.glb
│   ├── 📦 flower_armeria.glb
│   ├── 📦 orchidea.glb
│   ├── 📦 rosa.glb
│   └── 🖼️ (imagens e ícones)
│
└── 📝 README.md

```
Como Executar Localmente
Para rodar este projeto na sua máquina, siga os passos abaixo:

1. Clone o repositório
   ```
   git clone [https://github.com/jade-paz/RA.git](https://github.com/jade-paz/RA.git)

2. Entre na pasta do projeto
   ```
   cd RA
   ```
3. Execute um servidor local

Para que a Realidade Aumentada (WebXR) funcione corretamente e evite bloqueios de segurança (CORS) ao carregar os modelos 3D, é necessário usar um servidor local (https ou localhost).

Se você tem Node.js instalado:
```
npx live-server
```
4. Acesse no navegador

Abra o endereço exibido no terminal (geralmente http://127.0.0.1:5500/modelos.html).

♻ Créditos
Os modelos 3D utilizados neste projeto possuem licenças Creative Commons e atribuição aos seus respectivos autores no Sketchfab. 
A lista detalhada de créditos e autores encontra-se disponível na seção "Créditos" dentro da aplicação.

👩‍💻 Desenvolvedora
<table align="center"> <tr> <td align="center">

<b>Jade Paz</b>
