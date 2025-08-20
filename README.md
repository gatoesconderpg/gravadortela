

1. HTML2Canvas + MediaRecorder
Esta é a abordagem que implementei combina:

HTML2Canvas para capturar a tela como imagem

MediaRecorder para gravar essas imagens como vídeo

2. WebRTC Screen Capture
Além do getDisplayMedia, o WebRTC oferece outras APIs para captura de tela que podem ser mais adequadas para cenários específicos.

3. Extensões de Navegador
Para mais controle e funcionalidades, você pode considerar desenvolver uma extensão de navegador.

4. Serviços de Terceiros
Existem bibliotecas JavaScript especializadas em gravação de tela, como:

RecordRTC

MediaStreamRecorder

Whammy.js (para gravação WebM)

5. APIs Nativas (Electron/Node.js)
Se você estiver desenvolvendo um aplicativo desktop com Electron, pode usar APIs nativas do sistema operacional para gravação de tela.

Esta implementação oferece uma alternativa viável à API MediaDevices pura, com a vantagem adicional de capturas de tela estáticas.
