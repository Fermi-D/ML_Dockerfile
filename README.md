最新版のkaggle docker imageをベースに量子シュミレーションライブラリ(qiskit, qutip, qucat)を追加しています。 <br>
また、jupyterの拡張機能として変数の中身を参照できるvariableinspectorも使えるようにしています。 <br>

【使用方法】<br>
cloneしたディレクトリで以下のコマンド <br>
```docker-compose up --build``` <br>
をターミナルで実行し、表示されたURLにアクセスするとそのディレクトリがマウントされたjupyterlabが開きます。
