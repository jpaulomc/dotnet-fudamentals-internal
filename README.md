# dotnet-fudamentals-internal
Quero aqui, registrar meus estudos e aprendizados sobre dotnet, como funciona por baixo dos panos, para que eu possa relembra-los futuramente e ajudar quem precisa desses conhecimentos.

O que é o .NET?
O .NET é um ecossistema de desenvolvimento de software de código aberto (Open Source), criado pela Microsoft e mantido por ela e pela comunidade global. É uma das plataformas mais robustas e versáteis do mercado, sendo a escolha principal para o ambiente corporativo devido à sua alta performance, segurança e escalabilidade.

O que ele oferece?
O .NET fornece bibliotecas e ferramentas especializadas para diversas finalidades:

 - Web: ASP.NET Core (APIs e MVC) e Blazor (Front-end com C#).
 - Mobile: .NET MAUI (Android, iOS, macOS).
 - Desktop: WPF, WinForms e MAUI.
 - Background: Worker Services (Processamento em segundo plano).
 - Real-Time: SignalR (Notificações e chats em tempo real).
 - Performance/RPC: gRPC (Comunicação de baixa latência entre serviços).
 - Azure: Cloud

![Ecossistema DotNet.png](https://github.com/jpaulomc/dotnet-fudamentals-internal/blob/master/Ecossistema%20DotNet.png)

Como o .NET funciona por baixo dos panos?
O .NET suporta linguagens de alto nível como C# e F#. Para que o computador entenda esse código, ele passa por dois processos de "tradução":

 - C# para IL (Intermediate Language): Quando você compila o projeto, o C# é transformado em um código intermediário (independente de sistema operacional).
 - O papel da CLR (Common Language Runtime): É o "coração" do .NET. Ela gerencia a execução, cuida da memória (Garbage Collector) e da segurança.
JIT (Just-In-Time): Um componente dentro da CLR que traduz o código IL para Linguagem de Máquina (binário) no momento em que o programa está rodando, otimizando-o para o processador específico daquela máquina.

Como instalar e verificar?
Baixe o SDK oficial em: dotnet.microsoft.com/download

Após a instalação, abra o terminal (CMD ou PowerShell) e digite o comando para listar as versões instaladas:

Bash:

dotnet --list-sdks
