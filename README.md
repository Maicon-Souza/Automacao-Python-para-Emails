Automatização de Envio de E-mails com Python
Este script em Python utiliza a biblioteca Pandas e a biblioteca smtplib para automatizar o envio de e-mails. O código lê informações de uma planilha (CSV) e envia e-mails personalizados para cada destinatário.

Pré-requisitos
Python 3.x
Biblioteca Pandas
bash
Copy code
pip install pandas
Conta de e-mail (neste exemplo, Gmail é utilizado)
Configuração
Crie um arquivo CSV:

Crie um arquivo CSV contendo as colunas 'Nome' e 'E-mail Alternativo'.
Configurações no Código:

Atualize o caminho_do_csv para o caminho do seu arquivo CSV.
Substitua 'remetente' e 'Senha do email' nas configurações do e-mail.
Execução
Execute o script Python:

bash
Copy code
python script_email.py
Observações
Certifique-se de ativar a opção "Acesso a apps menos seguros" na conta de e-mail se estiver usando o Gmail.
Utilize senhas de aplicativo para autenticação se estiver usando autenticação em dois fatores.
