# Cadastro de Usuário - Flutter

 Atividade prática de formulários e validações usando Flutter e Dart.

## O que foi feito

- Campo de nome completo obrigatório.
- Campo de e-mail com validação usando `RegExp`.
- CPF e telefone aceitando somente números.
- Senha com no mínimo 6 caracteres.
- Confirmação da senha.
- Botões para mostrar ou ocultar as senhas.
- Mensagem de erro abaixo de cada campo inválido.
- `SnackBar` vermelho quando há erros e verde quando o cadastro é válido.
- Formulário dentro de `SingleChildScrollView` para evitar problemas com o teclado.

## Como executar

```bash
flutter create .
flutter pub get
flutter run
```

O comando `flutter create .` cria os arquivos de plataforma que estiverem faltando, por exemplo os necessários para Android e Windows.

Este exercício valida os dados na tela. Ele ainda não grava o cadastro em banco de dados nem envia os dados para uma API.
