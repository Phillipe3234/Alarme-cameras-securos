# Sistema de Alarmes - Integração com Media Client (SecurOS)

Este projeto é uma interface web para **monitoramento de alarmes de câmeras** integrada ao **Media Client do SecurOS**.  
Ele permite exibir alarmes em tempo real em uma tabela e abrir as câmeras diretamente no Media Client no layout 1x1 e possui um botão que tem a funcionalidade de mostrar todas as cãmeras que tiverem o alarme de movimento acionados, em um layout 4x4 dentro do Media Client.


## Funcionalidades
- Exibição das informações dos **eventos de alarme** em uma tabela dinâmica.
      - IDs das câmeras alarmadas
      - Nome das câmeras alarmadas
      - Hor´raio do alarme
- **Abertura individual de câmeras** no modo 1x1 com **duplo clique**.
- **VideoWall 4x4**: abre até 16 câmeras alarmadas simultaneamente.
- Integração com Media Client (Dektop, objeto do Securos).
- Fallback para integração.
- Interface simples e responsiva, em **HTML + CSS+ JavaScript + NodeJS**.

---

## Tecnologias Utilizadas
- **HTML5**
- **CSS3**
- **JavaScript**
- **ISScustomAPI (SecurOS)**
- **NodeJS**
- **Securos**

## Como usar

- **Configurar câmeras dentro do securos**
- **Criar um script nodejs dentro do securos para pegar os dados das câmeras configuradas**
- **Desktop (objeto securos)**
