# 📱 Frontend – App Flutter do BuildPrice

Este diretório contém o código-fonte do aplicativo Flutter responsável por toda a experiência visual e interação com o usuário final.

---

## 🚀 Tecnologias Utilizadas

- Flutter SDK
- Dart
- Provider (gerenciamento de estado)
- HTTP (requisições REST)
- Firebase/Supabase (futuro login)
- Android SDK + Emulador

---

## 📦 Como Rodar o App

### 1. Pré-requisitos:

- Flutter instalado: https://docs.flutter.dev/get-started/install
- Android Studio (SDK + Emulador)
- VSCode com extensões:
  - Dart
  - Flutter

### 2. Instalação:

```bash
cd frontend
flutter pub get
```

### 3. Executar:

```bash
flutter run
```

> Você pode usar um dispositivo físico (via USB) ou um emulador Android configurado.

---

## 📂 Estrutura Recomendada

```
frontend/
├── lib/
│   ├── screens/       # Telas do app
│   ├── widgets/       # Componentes reutilizáveis
│   ├── models/        # Classes de dados
│   ├── services/      # Serviços REST ou locais
│   └── main.dart      # Ponto de entrada do app
```

---

## 🧪 Em breve

- Autenticação de usuários
- Salvamento de orçamentos no Supabase
- Cálculo de obras baseado em metragem