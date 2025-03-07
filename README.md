<h1>FlutterPower</h1>

FlutterPower é uma ferramenta de linha de comando open-source que facilita a criação da estrutura inicial de projetos Flutter. Com **FlutterPower**, desenvolvedores podem gerar rapidamente as telas básicas necessárias para um aplicativo Flutter, como tela de apresentação, login, cadastro, e outras funcionalidades essenciais. Isso permite que você economize tempo configurando a arquitetura inicial e se concentre no desenvolvimento das funcionalidades do seu app.

## Características:
- Geração de estrutura de pastas organizada para projetos Flutter.
- Templates de código prontos para telas de apresentação, login e cadastro.
- Facilita o desenvolvimento ao fornecer uma base inicial já configurada.
- Open-source e totalmente personalizável para as necessidades do desenvolvedor.
- Suporta a criação de projetos com as melhores práticas de organização de código.

## Instalação:
Para usar o **FlutterPower**, você precisa ter o **Dart** instalado no seu sistema. Se ainda não tiver o Dart, siga as instruções de instalação do [Dart](https://dart.dev/get-dart).

### Instalar o FlutterPower:
1. Instale a ferramenta globalmente com o seguinte comando:
   ```bash
   dart pub global activate flutter_power
   ```

2. Depois de instalado, você pode verificar se está funcionando corretamente com:
   ```bash
   flutter_power --version
   ```

## Como Usar:
Depois de instalar o **FlutterPower**, você pode criar um novo projeto Flutter com a estrutura básica gerada automaticamente.

### Criar um Novo Projeto Flutter:
Para criar um novo projeto com a estrutura básica do Flutter, execute o comando abaixo:
```bash
flutter_power create --projectName meu_app
```
Esse comando criará um novo projeto Flutter com as seguintes características:
- **Tela de Apresentação**: Um design simples para introdução ao app.
- **Tela de Login**: Estrutura básica de login com campos para usuário e senha.
- **Tela de Cadastro**: Tela para criação de uma nova conta de usuário.
- **Estrutura de Pastas**: Organiza o código do projeto para garantir boas práticas desde o início.

### Estrutura do Projeto Gerado:
O projeto gerado terá a seguinte estrutura:
```
meu_app/
│
├── lib/
│   ├── main.dart
│   ├── screens/
│   │   ├── login_screen.dart
│   │   ├── register_screen.dart
│   │   ├── splash_screen.dart
│   └── models/
├── pubspec.yaml
└── README.md
```

## Contribuições:
Contribuições são bem-vindas! Se você gostaria de melhorar o **FlutterPower**, basta seguir os seguintes passos:

1. Faça um **fork** deste repositório.
2. Crie uma nova **branch** para suas alterações.
3. Envie um **pull request** explicando as mudanças feitas.

### Como Contribuir:
- Faça um fork deste repositório.
- Crie uma nova branch para suas alterações (ex.: `feature/adicionar-nova-tela`).
- Envie um pull request com uma descrição clara do que foi alterado e o motivo.
- Certifique-se de que o código está bem documentado e que os testes foram feitos para garantir a estabilidade.

## Licença:
Este projeto é licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

### Contato:
Se você tiver dúvidas ou sugestões, não hesite em abrir uma **issue** no repositório ou me contatar diretamente.

```
By Destiny7.Softwares & Solutions 2025@ Maurício Henrique NNS.
