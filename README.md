# Secom Drive

Aplicativo do Portal Secom para Windows 10/11 de 64 bits (Intel/AMD).

## Download

[**Baixar a versão mais recente**](https://github.com/secomprodu-cyber/secom-drive/releases/latest)

Na página da versão, abra **Assets** e baixe **Secom-Drive-Windows-x64.zip**.

## Instalação

1. Extraia o ZIP inteiro.
2. Abra **Instalar Secom.cmd** normalmente, sem executar como administrador.
3. Conclua a instalação dos componentes solicitados. O WinFsp pode pedir autorização de administrador.
4. Abra **Secom Drive** e entre na conta autorizada no portal.
5. Selecione **Todas as pastas do portal** ou uma pasta específica para conectar a unidade S:.

É preciso acesso à internet e uma conta autorizada. O instalador não inclui contas, fotos ou caches de usuários.

## Recursos

- Arquivos originais sob demanda e envio das edições ao servidor.
- Miniaturas mantidas em cache entre conexões.
- Até 10 downloads e 10 envios simultâneos.
- Funcionamento em segundo plano e opção de iniciar com o Windows.
- Preparação de pastas para trabalhar e acompanhamento das transferências.

## Atualizações

A partir da versão **1.2.0**, o Secom verifica novas versões ao abrir e a cada seis horas, baixa em segundo plano e instala na próxima abertura, antes de conectar a unidade. Conta, configurações e cache são preservados. A versão instalada e o estado da atualização aparecem no aplicativo. Para consultar imediatamente, use **Verificar atualizações** no ícone junto ao relógio.

**Quem está na versão 1.1.0 precisa instalar a 1.2.0 manualmente uma única vez.** Antes de instalar ou aplicar uma atualização pronta, termine os envios, feche os arquivos de S: e use **Desconectar e sair**. Depois abra o Secom novamente. Fechar apenas a janela mantém o programa em segundo plano.

O canal acompanha Releases estáveis marcadas como Latest, com número maior e os três anexos de distribuição. Enviar commits ao repositório não publica uma atualização do aplicativo.

As versões ficam em [Releases](https://github.com/secomprodu-cyber/secom-drive/releases). Para receber também avisos do GitHub, use **Watch → Custom → Releases**.

O arquivo **Secom-Drive-Windows-x64.zip.sha256.txt** acompanha cada versão para verificar a integridade do download.
