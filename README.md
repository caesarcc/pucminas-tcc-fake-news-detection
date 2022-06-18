# pucminas-tcc-fake-news-detection
## Aplicando Técnicas Modernas de Aprendizado Profundo no Reconhecimento de Notícias Potencialmente Falsas 

Trabalho de Conclusão de Curso apresentado ao Curso de Especialização em Inteligência Artificial e Aprendizado de Máquina. 

Todos notebooks Jupyter estão prontos para ser executados diretamente no Google Colab ao clicar no ícone <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Abrir no Colab"/>

Para rodar os notebooks localmente é necessário executar os seguintes passos:
```
conda create --name tcc python=3.8
conda activate tcc
pip install --no-cache-dir -r requirements.txt
conda install pytorch torchvision torchaudio cpuonly -c pytorch
conda install -c huggingface transformers
conda install -c conda-forge ipywidgets

jupyter nbextension enable --py widgetsnbextension
```
