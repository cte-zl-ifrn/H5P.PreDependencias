**Guia Passo a Passo para Compactar e Integrar Bibliotecas H5P no Moodle:**

Este guia oferece instruções detalhadas sobre como compactar uma biblioteca para a extensão do H5P e integrá-la ao Moodle. Certifique-se de seguir cada passo cuidadosamente para garantir uma instalação bem-sucedida.

1. **Instalação da CLI do H5P:** Utilize o comando para instalar a CLI do H5P globalmente**:** `npm install -g h5p` 
2. **Navegação até a Pasta da Biblioteca:** Acesse a pasta da biblioteca desejada utilizando o comando, ex.: `cd h5p-column` 
3. **Compactação da Biblioteca em .h5p:** Execute o seguinte comando para compactar a pasta em um arquivo .h5p: `h5p pack h5p-column`
4. **Acesso ao Moodle:** Abra o Moodle e acesse a seção de Administração do Site.
5. **Gerenciamento de Tipos de Conteúdo H5P:** Navegue até "Administração do Site" e selecione "Gerenciar Tipos de Conteúdo H5P".
6. **Upload da Biblioteca Compactada:** Na área de "Enviar Tipos de Conteúdo H5P", faça o upload do arquivo .h5p recém-criado.
7. **Mensagem de Confirmação:** Uma mensagem de sucesso será exibida, confirmando a integração bem-sucedida da biblioteca.

Obs.: Alguns conteúdos podem dar erro pois existem eles possuem pre dependencias, caso voce tente enviar esse conteudo antes de enviar sua dependencias, uma mensagem de erro será apresentada. Então faça o upload das pre dependencias primeiro.
