# Table of contents

## Getting Started

* [🤖 Welcome to OpenAdapt!](README.md)
  * [Quick Start](getting-started/welcome-to-openadapt/quick-start.md)

## Reference

* [API Reference](reference/api-reference/README.md)
  * [openadapt (module)](reference/api-reference/openadapt-module/README.md)
    * [📦 app (module)](reference/api-reference/openadapt-module/app-module/README.md)
      * [🏀 objects](reference/api-reference/openadapt-module/app-module/objects/README.md)
        * [📁 LocalFilePicker (local\_file\_picker.py)](reference/api-reference/openadapt-module/app-module/objects/localfilepicker-local\_file\_picker.py.md)
        * [🗒 Console (console.py)](reference/api-reference/openadapt-module/app-module/objects/console-console.py/README.md)
          * [write (function)](reference/api-reference/openadapt-module/app-module/objects/console-console.py/write-function.md)
          * [flush (function)](reference/api-reference/openadapt-module/app-module/objects/console-console.py/flush-function.md)
          * [reset (function)](reference/api-reference/openadapt-module/app-module/objects/console-console.py/reset-function.md)
      * [🔨 build.py](reference/api-reference/openadapt-module/app-module/build.py.md)
      * [🎮 main.py](reference/api-reference/openadapt-module/app-module/main.py.md)
      * [⚙ util.py](reference/api-reference/openadapt-module/app-module/util.py/README.md)
        * [set\_scrub (function)](reference/api-reference/openadapt-module/app-module/util.py/set\_scrub-function.md)
        * [get\_scrub (function)](reference/api-reference/openadapt-module/app-module/util.py/get\_scrub-function.md)
        * [set\_dark (function)](reference/api-reference/openadapt-module/app-module/util.py/set\_dark-function.md)
        * [clear\_db (function)](reference/api-reference/openadapt-module/app-module/util.py/clear\_db-function.md)
        * [on\_import (function)](reference/api-reference/openadapt-module/app-module/util.py/on\_import-function.md)
        * [on\_export (function)](reference/api-reference/openadapt-module/app-module/util.py/on\_export-function.md)
      * [☀ cards.py](reference/api-reference/openadapt-module/app-module/cards.py/README.md)
        * [recording\_prompt (function)](reference/api-reference/openadapt-module/app-module/cards.py/recording\_prompt-function.md)
        * [settings (function)](reference/api-reference/openadapt-module/app-module/cards.py/settings-function.md)
        * [select\_import (function)](reference/api-reference/openadapt-module/app-module/cards.py/select\_import-function.md)
        * [stop\_record (function)](reference/api-reference/openadapt-module/app-module/cards.py/stop\_record-function.md)
        * [quick\_record (function)](reference/api-reference/openadapt-module/app-module/cards.py/quick\_record-function.md)
      * [🤖 tray.py](reference/api-reference/openadapt-module/app-module/tray.py/README.md)
        * [SystemTrayIcon (class)](reference/api-reference/openadapt-module/app-module/tray.py/systemtrayicon-class/README.md)
          * [populate\_menu (function)](reference/api-reference/openadapt-module/app-module/tray.py/systemtrayicon-class/populate\_menu-function.md)
          * [update\_tray\_icon (function)](reference/api-reference/openadapt-module/app-module/tray.py/systemtrayicon-class/update\_tray\_icon-function.md)
          * [\_quick\_record (function)](reference/api-reference/openadapt-module/app-module/tray.py/systemtrayicon-class/\_quick\_record-function.md)
          * [\_visualize (function)](reference/api-reference/openadapt-module/app-module/tray.py/systemtrayicon-class/\_visualize-function.md)
          * [\_replay (function)](reference/api-reference/openadapt-module/app-module/tray.py/systemtrayicon-class/\_replay-function.md)
          * [show\_app (function)](reference/api-reference/openadapt-module/app-module/tray.py/systemtrayicon-class/show\_app-function.md)
          * [run (function)](reference/api-reference/openadapt-module/app-module/tray.py/systemtrayicon-class/run-function.md)
    * [privacy (package)](reference/api-reference/openadapt-module/privacy-package/README.md)
      * [\_\_init\_\_.py](reference/api-reference/openadapt-module/privacy-package/\_\_init\_\_.py.md)
      * [base.py](reference/api-reference/openadapt-module/privacy-package/base.py.md)
      * [providers (package)](reference/api-reference/openadapt-module/privacy-package/providers-package/README.md)
        * [presidio.py](reference/api-reference/openadapt-module/privacy-package/providers-package/presidio.py.md)
        * [aws\_comprehend.py](reference/api-reference/openadapt-module/privacy-package/providers-package/aws\_comprehend.py.md)
        * [\_\_init\_\_.py](reference/api-reference/openadapt-module/privacy-package/providers-package/\_\_init\_\_.py.md)
    * [productivity.py](reference/api-reference/openadapt-module/productivity.py.md)
    * [scripts (module)](reference/api-reference/openadapt-module/scripts-module/README.md)
      * [generate\_dataset.py](reference/api-reference/openadapt-module/scripts-module/generate\_dataset.py.md)
      * [tag\_dataset.py](reference/api-reference/openadapt-module/scripts-module/tag\_dataset.py.md)
      * [reset\_db.py](reference/api-reference/openadapt-module/scripts-module/reset\_db.py.md)
    * [strategies (module)](reference/api-reference/openadapt-module/strategies-module/README.md)
      * [mixins](reference/api-reference/openadapt-module/strategies-module/mixins/README.md)
        * [OpenAIReplayStrategyMixin (openai.py)](reference/api-reference/openadapt-module/strategies-module/mixins/openaireplaystrategymixin-openai.py.md)
        * [OCRReplayStrategyMixin (ocr.py)](reference/api-reference/openadapt-module/strategies-module/mixins/ocrreplaystrategymixin-ocr.py.md)
        * [ASCIIReplayStrategyMixin (ascii.py)](reference/api-reference/openadapt-module/strategies-module/mixins/asciireplaystrategymixin-ascii.py.md)
        * [LLMReplayStrategyMixin (huggingface.py)](reference/api-reference/openadapt-module/strategies-module/mixins/llmreplaystrategymixin-huggingface.py.md)
      * [BaseReplayStrategy (base.py)](reference/api-reference/openadapt-module/strategies-module/basereplaystrategy-base.py.md)
      * [StatefulReplayStrategy (stateful.py)](reference/api-reference/openadapt-module/strategies-module/statefulreplaystrategy-stateful.py.md)
      * [NaiveReplayStrategy (naive.py)](reference/api-reference/openadapt-module/strategies-module/naivereplaystrategy-naive.py.md)
    * [window (module)](reference/api-reference/openadapt-module/window-module.md)
    * [vision (module)](reference/api-reference/openadapt-module/vision-module/README.md)
      * [instructblip.py](reference/api-reference/openadapt-module/vision-module/instructblip.py.md)
      * [blip2.py](reference/api-reference/openadapt-module/vision-module/blip2.py.md)
      * [minigpt4.py](reference/api-reference/openadapt-module/vision-module/minigpt4.py.md)
      * [otter.py](reference/api-reference/openadapt-module/vision-module/otter.py.md)
    * [extensions (module)](reference/api-reference/openadapt-module/extensions-module.md)
    * [📷 record.py](reference/api-reference/openadapt-module/record.py.md)
    * [🔬 visualize.py](reference/api-reference/openadapt-module/visualize.py.md)
    * [📺 replay.py](reference/api-reference/openadapt-module/replay.py.md)
    * [🧰 utils.py](reference/api-reference/openadapt-module/utils.py/README.md)
      * [image2utf8 (function)](reference/api-reference/openadapt-module/utils.py/image2utf8-function.md)