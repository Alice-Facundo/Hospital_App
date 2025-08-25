# Hospital App

O Hospital App é um aplicativo móvel desenvolvido com Ionic e Angular, projetado para facilitar o gerenciamento de informações em um ambiente hospitalar, incluindo pacientes, médicos e clínicas. Ele utiliza o Firebase para autenticação, armazenamento de dados em tempo real e armazenamento de arquivos, tornando-o uma solução robusta e escalável.

## Funcionalidades

O aplicativo oferece uma gama de funcionalidades para otimizar a gestão de dados de saúde:

  * **Autenticação de Usuários:** Sistema seguro de login e cadastro de novos usuários.
  * **Gerenciamento de Pacientes:** Permite cadastrar, visualizar, editar e excluir registros de pacientes.
  * **Gestão de Clínicas:** Oferece funcionalidades para adicionar e gerenciar informações sobre as clínicas, incluindo dados de localização.
  * **Cadastro de Médicos:** Ferramentas para manter um registro detalhado dos médicos, incluindo suas especialidades.
  * **Configurações de Perfil:** Os usuários podem visualizar e atualizar suas informações de perfil, incluindo a foto.
  * **Localização e Mapas:** Integração com o Google Maps para visualização da localização de clínicas e endereços.
  * **Funcionalidades Nativas do Dispositivo:** Acesso à câmera e galeria de fotos para upload de imagens, utilizando os plugins do Cordova.

##  Tecnologias Utilizadas

O projeto foi construído com as seguintes tecnologias:

  * **Ionic:** Plataforma para desenvolvimento de aplicativos móveis híbridos.
  * **Angular:** Framework para a construção da interface do usuário.
  * **Firebase:** Utilizado para autenticação, banco de dados em tempo real (Firestore) e armazenamento de arquivos.
  * **Cordova:** Permite o acesso a funcionalidades nativas do dispositivo, como câmera e geolocalização.
  * **TypeScript:** Linguagem de programação principal do projeto.
  * **Sass:** Para estilização avançada dos componentes.

##  Pré-requisitos

Antes de iniciar, certifique-se de ter o seguinte instalado:

  * Node.js e npm
  * Ionic CLI
  * Cordova CLI
  * Angular CLI

##  Instalação e Execução

Siga os passos abaixo para configurar e executar o projeto em seu ambiente local:

**1. Navegue até o diretório do projeto:**

```bash
cd hospital_app
```

**3. Instale as dependências:**

```bash
npm install
```

**4. Execute o projeto no navegador:**

```bash
ionic serve
```

**5. Para compilar e executar em dispositivos móveis:**

  * **Android:**
    ```bash
    ionic cordova platform add android
    ionic cordova run android
    ```

## Firebase

O projeto está configurado para usar o Firebase. As credenciais de configuração podem ser encontradas no arquivo `src/app/app.module.ts`. Para um ambiente de produção, é recomendável substituir essas credenciais pelas do seu próprio projeto Firebase.
