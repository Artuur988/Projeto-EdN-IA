# Projeto-EdN-IA
Projeto de IA Blue Guardian do Grupo 6 da sala 174 da Escola da Nuvem 
# Blue Guardian - Grupo 12 Sala 174 da Escola da Nuvem

## Sobre o Projeto
Blue Guardian é um assistente de Inteligência Artificial especializado em gestão hídrica, desenvolvido pelo Grupo 6 da sala 174 da Escola da Nuvem. O objetivo do projeto é orientar usuários sobre economia de água em residências, comércios, indústrias e ambientes agrícolas, promovendo práticas sustentáveis e o uso eficiente dos recursos hídricos.

## Funcionalidades
- Chat interativo com IA treinada para gestão hídrica
- Histórico de conversas e gerenciamento de múltiplos chats
- Autenticação de usuário com senha e cookies
- Interface moderna e responsiva via Streamlit

## Tecnologias Utilizadas
- [Streamlit](https://streamlit.io/) (interface web)
- [AWS Bedrock](https://aws.amazon.com/bedrock/) (modelo de IA)
- [Boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html) (integração AWS)
- [PyPDF2](https://pypdf2.readthedocs.io/) (leitura de PDFs)
- [Pandas](https://pandas.pydata.org/) (leitura de CSV)
- Python 3.12+

## Estrutura do Projeto
```
Projeto-EdN-IA/
├── streamlit/
│   ├── app.py
│   ├── auth_middleware.py
│   ├── functions.py
│   ├── logo.jpg
│   ├── .env
│   ├── .env.local
│   └── __pycache__/
├── requirements.txt
└── README.md
```

## Como Executar

1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/Projeto-EdN-IA.git
   cd Projeto-EdN-IA/streamlit
   ```

2. Instale as dependências:
   ```sh
   pip install -r ../requirements.txt
   ```

3. Configure as variáveis de ambiente AWS em `.env` ou `.env.local`:
   ```
   AWS_PROFILE="seu-perfil-aws"
   ```

4. Execute o aplicativo:
   ```sh
   streamlit run app.py
   ```

5. Acesse no navegador: [http://localhost:8501](http://localhost:8501)

## Equipe
- Artur Siqueira [https://github.com/Artuur988]
- Bruno Hackbart Nunes [https://github.com/brunohackbart13]
- Francisco Jonathan Alves Da Costa [https://github.com/JhonCostaDev]
- Rute Moraes [https://github.com/RRDRTTMORAES]
- Wesley dos Santos Freitas[https://github.com/FREITASWES]
