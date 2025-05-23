🔊 VoiceAuth – Autenticação Biométrica por Voz com Python
Este projeto consiste em um sistema de back-end para autenticação de usuários por biometria de voz, utilizando Python. Ideal para aplicações que exigem autenticação rápida, segura e sem necessidade de senha digitada.

💻 Tecnologias Utilizadas
Python 3.10+

Flask (API REST)

Librosa (extração de MFCCs)

Scikit-learn (modelo de machine learning)

Joblib (persistência de modelo)

NumPy, Soundfile, tempfile

⚙️ Funcionalidades
🎙️ Cadastro de novos usuários com amostra de voz.

🔐 Autenticação baseada na comparação de características acústicas (MFCC).

📦 API RESTful com dois endpoints principais:

POST /register: cadastra novo usuário.

POST /auth: realiza a autenticação pela voz.
