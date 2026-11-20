# Cifras - Visualizador e Gerenciador de Cifras Musicais

## 1. Objetivo e Finalidade
Aplicação web para visualização, transposição de tons e organização de repertórios e cifras musicais.

## 2. Tecnologias Utilizadas
- React, TypeScript, Vite, Tailwind CSS, Firebase (Auth/Firestore), Lucide React

## 3. Arquitetura e Estrutura de Diretórios
Frontend SPA em React com Vite e estilização via Tailwind CSS. Armazenamento de repertórios e preferências musicais no Firebase Firestore.

## 4. Principais Arquivos e Responsabilidades
- `src/App.tsx`: Visualizador de letras com cifras e controle de transposição.
- `firebase.json`: Regras de hosting e segurança Firebase.
- `firestore.rules`: Regras de controle de acesso ao acervo musical.

## 5. Funcionalidades Identificadas
- Exibição formatada de letras e cifras musicais
- Transposição dinâmica de tom musical
- Organização de listas de reprodução por eventos ou cultos
- Sincronização em nuvem com Firebase

## 6. Como Compilar ou Executar
```bash
npm install
npm run dev
# Build de produção: npm run build
```

## 7. Estado Atual do Projeto
**Completo**

## 8. Pendências e Limitações Identificadas
Adicionar rolagem automática de tela e modo noturno de alta legibilidade.
