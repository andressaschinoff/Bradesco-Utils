# Pacote AEM (contents)

Neste pacote estão os "contents" com imagens, fragments, queries graphql a serem instalados no AEM.
As intruções servirão para instalar o pacote através do **CRX Package Manager**

## Pré-requisitos

-   Adobe Experience Manager (AEM) em execução

-   Acesso ao CRX Package Manager

-   Permissões de administrador

-   Pacote  `content-bradesco-x.x.x.zip`

## Instruções de Instalação
### 1. Acesso ao Package Manager

Acesse o CRX Package Manager através de uma das seguintes URLs:

-   `http://[seu-servidor]:[porta]/crx/packmgr/index.jsp`

-   Ou através do AEM:  **Ferramentas**  >  **Implantação**  >  **Pacotes**

### 2. Login

Faça login com suas credenciais de administrador do AEM.

### 3. Upload do Pacote

1.  Clique no botão  **"Upload Package"**  (Carregar Pacote) no topo da página

2.  Clique em  **"Browse"**  ou arraste o arquivo  `content-bradesco-x.x.x.zip`

3.  Selecione o arquivo do pacote

4.  Marque a opção  **"Force Upload"**  se necessário (para sobrescrever versões existentes)

Clique em **"OK"** ou **"Upload"**

### 4. Instalação do Pacote

Após o upload bem-sucedido:

-   Localize o pacote  `content-bradesco-x.x.x.zip`  na lista de pacotes

2.  Clique no botão  **"Install"**  (Instalar) ao lado do pacote

3.  Na janela de confirmação, clique em  **"Install"**  para confirmar

### 5. Verificação

Após a instalação:

1.  Verifique se o status mostra  **"Installed"**  (verde)

2.  Revise o log de atividades para confirmar que não há erros

3.  Teste a funcionalidade implementada pelo pacote



## Arquivos

Arquivo fornecido para deploy:


|Arquivo                     |Descrição                      |
|----------------------------|-------------------------------|
|`content-bradesco-x.x.x.zip`|Pacote contents                |

