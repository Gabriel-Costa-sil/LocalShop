AppLocalShop
Projeto desenvolvido para a faculdade. É um app mobile que permite listar, cadastrar, editar e excluir lojas locais. O frontend foi feito em React Native com Expo e o backend é uma API simples em Node.js conectada ao Firebase Firestore.

Tecnologias usadas
No frontend usei React Native com Expo, TypeScript, React Navigation pra navegação entre telas e Axios pra fazer as chamadas pra API.
No backend usei Node.js com Express e TypeScript. O banco de dados é o Firebase Firestore, acessado pelo Firebase Admin SDK.

O que o app faz
Na tela inicial aparece uma lista com todas as lojas cadastradas. Dá pra clicar em qualquer uma pra ver os detalhes, como categoria, distância e descrição.
Tem um botão na tela inicial pra cadastrar uma loja nova, onde você preenche nome, categoria, imagem, distância e descrição.
Dentro dos detalhes de uma loja tem a opção de editar ou excluir ela.

Observação
O arquivo firebase-key.json nunca deve ser enviado pro GitHub. Verifique se ele está no .gitignore antes de fazer qualquer commit.
