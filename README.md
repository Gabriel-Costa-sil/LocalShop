AppLocalShop
Projeto desenvolvido para a faculdade. É um app mobile que permite listar, cadastrar, editar e excluir lojas locais. O frontend foi feito em React Native com Expo e o backend é uma API simples em Node.js conectada ao Firebase Firestore.

1- Tecnologias usadas
No frontend usei React Native com Expo, TypeScript, React Navigation pra navegação entre telas e Axios pra fazer as chamadas pra API.
No backend usei Node.js com Express e TypeScript. O banco de dados é o Firebase Firestore, acessado pelo Firebase Admin SDK.

2- O que o app faz
Na tela inicial aparece uma lista com todas as lojas cadastradas. Dá pra clicar em qualquer uma pra ver os detalhes, como categoria, distância e descrição.
Tem um botão na tela inicial pra cadastrar uma loja nova, onde você preenche nome, categoria, imagem, distância e descrição.
Dentro dos detalhes de uma loja tem a opção de editar ou excluir ela.

3- Estrutura do Projeto
AppLocalShop/
├── backend/
│   └── src/
│       └── server.ts          # Toda a API concentrada aqui
├── frontend/
│   ├── App.tsx                # Configura as rotas do app
│   └── src/
│       ├── screens/           # Home, Detalhes, Cadastro, Editar
│       ├── components/        # Cards e outros elementos reutilizáveis
│       ├── hooks/             # Lógica separada (listagem, formulários)
│       └── services/          # Chamadas HTTP para a API

Observação
O arquivo firebase-key.json nunca deve ser enviado pro GitHub. Verifique se ele está no .gitignore antes de fazer qualquer commit.
