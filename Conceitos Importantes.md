## Por que testar mobile?

Porque tudo está no celular hoje em dia. Absolutamente tudo. Além disso, existem clientes que precisam de aplicações mobile, bem como aplicações híbridas, que, a princípio, são aplicações web, mas têm a capacidade de se adaptar à realidade e ao tamanho dos celulares.

### Tipos de aplicações a serem testadas:

- Aplicações nativas (Android (.apk) / iOS (.ipa))
- Aplicações híbridas
- Web-Mobile

### Desafios:

- Aumento da demanda (lançamentos constantes)
- Evolução contínua dos aplicativos
- Qualidade das versões
- Recursos variados nos dispositivos
- Impacto da velocidade da rede
- Diferenças de desempenho entre navegadores

### Tipos de aplicações

#### Nativas (Feitas para serem executadas no Android/iOS)

- São desenvolvidas usando kits de desenvolvimento (SDK).
- Podem necessitar de testes em todos os dispositivos compatíveis.
- Geralmente possuem melhor desempenho.

#### Web-Mobile (Uma URL "reduzida")

Acessadas por meio de um navegador instalado no celular.

- A automação pode ser levemente diferente, pois se usa o navegador como base do teste.

Podem ser:

- Versões específicas para dispositivos móveis.
- Sites web que são responsivos.
- Aplicativos adaptativos (especificam o tamanho da tela, mas não são totalmente responsivos).

#### Híbridas

- Combinação dos dois mundos.
- Uma mistura de aplicações nativas com web.
- Encapsula o código em um container único, que funciona tanto no Android quanto no iOS.
- Possuem desempenho menor em comparação com apps nativos.

### Responsividade

Capacidade de adaptação de um site às proporções e peculiaridades de um celular.

### Plataformas de desenvolvimento mobile

- **Android Studio**: Aplicações Android.
  - Os testes podem ser executados usando essa ferramenta, com um emulador específico.

- **Xcode**: Aplicações iOS.

- **Visual Studio com .NET MAUI**: Suporte para Android, iOS, MacOS e Windows.

### Emuladores, Simuladores e Dispositivos Reais

#### Diferenças:

- **Emuladores** e **simuladores** são dispositivos virtuais que simulam algo real.

### Simuladores x Emuladores x Dispositivos Reais

#### Dispositivos reais

- São os mais confiáveis para testes manuais, pois são testados em circunstâncias reais, refletindo exatamente o que o usuário vai vivenciar.
- Úteis para verificar questões de performance e integração com eventos relacionados ao hardware.

**Lado ruim**:

- São caros e possuem muitos tipos, dificultando a apuração dos problemas por causa da unicidade de cada aparelho.

#### Emuladores

- Dispositivos virtuais que imitam ou simulam os dispositivos reais.
- São os mais próximos dos dispositivos reais, imitando o software, o hardware e o sistema operacional onde a aplicação é executada.

**Lado ruim**:

- São mais lentos, pois o emulador precisa simular o conjunto de arquitetura do celular (ISA - Instruction Set Architecture), e essa tradução é predominantemente binária.

#### Simuladores

- Testes mais rápidos e muito úteis para computadores menos potentes.
- É possível, por meio deles, testar em outros sistemas operacionais (talvez em um que a aplicação não foi feita).

## Appium

- Open source.
- Automação em aplicações nativas, híbridas, web apps, Windows e desktop.
- Plataforma cruzada (consegue testar muitas ferramentas).

Suporte para:

- iOS
- Android
- Windows
