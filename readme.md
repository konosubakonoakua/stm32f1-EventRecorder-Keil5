# HOW TO USE EVENT-RECORDER IN KEIL5 on a [BLUEPILL](http://wiki.stm32duino.com/index.php?title=Blue_Pill)

- Add Compiler Component like this.

  ![](./Doc/pack.png)

  

- Config  Event Recorder.

  ![](./Doc/config.png)

- Add your code.

  The code showed belowing will measure time loss between

  `EventStartA(0);` and `EventStopA(0);`.

  ![](./Doc/code.png)

- Compile your code.

- Config your debugger.

  ![](./Doc/debugger.png)

  ![](./Doc/trace-cfg.png)

- Enter debug mode.

- Enable Event Recorder.

  ![](./Doc/how-to-enable-it.png)

- Then you'll get this.

  ![](./Doc/Event-Statistics.png)

  ![](./Doc/debug-viewer.png)

[EventRecorder overview](http://www.keil.com/pack/doc/compiler/EventRecorder/html/er_overview.html)

