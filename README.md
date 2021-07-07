# Script de suporte

https://thiagoalexandria.com.br/assets/img/menu.png

# Comandos
|Comando| Função|
|---|---|
|apache_status| Fullstatus do Apache|
|edit_http| Abre o arquivo pre_virtualhost_global.conf para edição|
|restrict_http| Bloqueia o acesso web da conta cPanel|
|disable_spamdel| Desabilitar Auto Delete do SpamAssassin de uma conta|
|enable_spamass| Ativar SpamAssassin para uma conta|
|conf_spamass| Configurar score do SpamAssassin de uma conta|
|global_spambox| Habilitar Spam Box para todos do servidor|
|mailogin_history|  Relatório de login das contas de e-mail de um domínio|
|mail_usage_report|  Relatório de todas as contas de e-mail do servidor|
|cpusermail_usage|  Relatório das contas de e-mail de uma conta cPanel|
|changemail_password|  Alterar senha de conta para uma aleatória|
|nomail| Desabilitar envio de e-mail de uma conta cPanel|
|yesmail| Habilitar envio de e-mail de uma conta cPanel|
|delfrozen| Remover e-mails frozen da fila|
|deldonmail| Remover e-mails de todo domínio da fila|
|delusermail| Remover e-mails de uma conta da fila|
|sendmail| Enviar e-mail|
|mq| Fila de e-mail para auditoria|
|checkmx| Verifica roteamento de e-mail e entradas MX do domínio|
|cpanel_session| Acesso cPanel sem senha|
|suspend_reseller| Suspender Reseller|
|unsuspend_reseller| Remover suspensão do Reseller|
|autossl| Gerar certificado ssl para conta|
|servicestatus| Verificar status de serviços mais comuns|
|restrict_mailacct| Desabilitar conta de e-mail Login/Envio/Recebimento|
|unrestrict_mailacct| Remover bloqueio de conta de e-mail Login/Envio/Recebimento|
|create_backup| Gerar backup da conta em sua home|
|check_backup| Verificar backups disponíveis para a conta|
|phpinfo| Adiciona o phpinfo no diretório atual|

# Utilização

|Comando| Exemplo|
|---|---|
|apache_status| apache_status|
|edit_http| edit_http|
|restrict_http| restrict_http `usuario_cpanel`|
|disable_spamdel| disable_spamdel `usuario_cpanel`|
|enable_spamass| enable_spamass `usuario_cpanel`|
|conf_spamass| conf_spamass `usuario_cpanel`|
|global_spambox| global_spambox|
|mailogin_history| mailogin_history `dominio`|
|mail_usage_report| mail_usage_report|
|cpusermail_usage| cpusermail_usage `usuario_cpanel`|
|changemail_password| changemail_password `endereco_email`|
|nomail| nomail `usuario_cpanel`|
|yesmail| yesmail `usuario_cpanel`|
|delfrozen| delfrozen|
|deldonmail| deldonmail `dominio`|
|delusermail| delusermail `endereco_email`|
|sendmail| sendmail `origem` `destino`|
|mq| mq|
|checkmx| checkmx `dominio`|
|cpanel_session| cpanel_session|
|suspend_reseller| suspend_reseller `usuario_cpanel`|
|unsuspend_reseller| unsuspend_reseller `usuario_cpanel`|
|autossl| autossl `usuario_cpanel`|
|servicestatus| servicestatus|
|restrict_mailacct| restrict_mailacct `endereco_email`|
|unrestrict_mailacct| unrestrict_mailacct `endereco_email`|
|create_backup| create_backup `usuario_cpanel`|
|check_backup| check_backup `usuario_cpanel`|
|phpinfo| phpinfo|
