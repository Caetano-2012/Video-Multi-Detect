<h1 align="center">🚶 Detecção de Pessoas em Movimento</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge">
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-success?style=for-the-badge" alt="Status Badge">
</p>

<p align="center">
  <i>Detecção de pessoas caminhando em um vídeo utilizando OpenCV.</i><br>
  <b>Autor:</b> Caetano Bordin
</p>

---

## 🧩 Sobre o Projeto

Este projeto utiliza **OpenCV** para detectar pessoas caminhando em um vídeo. A cada frame, o programa identifica os corpos detectados e desenha retângulos ao redor deles, atualizando a visualização conforme o vídeo avança.

## 🧰 Tecnologias Utilizadas

- **Python**
- **OpenCV (cv2)**
- **Haar Cascade** — classificador para detecção de corpos.

## ⚙️ Funcionalidades

- 🎞️ Leitura do vídeo `walking.avi`;
- ⚫ Conversão dos frames para escala de cinza;
- 🔍 Detecção de corpos humanos;
- 🟦 Delimitação das pessoas detectadas com retângulos;
- 🔄 Atualização da detecção durante a reprodução do vídeo;
- ⏹️ Encerramento ao pressionar a barra de espaço.

## 📚 Aprendizados

- Leitura de vídeos com `cv2.VideoCapture()`;
- Processamento de frames;
- Detecção de objetos com `detectMultiScale()`;
- Desenho de retângulos com `cv2.rectangle()`;
- Aplicação do Haar Cascade na detecção de corpos.

## 🕹️ Como Executar

1. Instale o OpenCV:

```bash
pip install opencv-python
```

2. Coloque os arquivos `walking.avi` e `haarcascade_fullbody.xml` na mesma pasta do programa.

3. Execute o arquivo Python:

```bash
python main.py
```

4. O vídeo será processado com a detecção de corpos. Para encerrar, pressione a **barra de espaço**.

## 📜 Licença

O código pode ser usado somente para **fins educacionais**.

É permitida a modificação e redistribuição, desde que os autores sejam citados e a licença original seja mantida.

O software é fornecido **"como está"**, sem garantias de qualquer tipo. Os autores não são responsáveis por danos decorrentes de seu uso.

## 👨‍💻 Autor

**Caetano Bordin**

🔗 [@Caetano-2012](https://www.github.com/Caetano-2012)

---
