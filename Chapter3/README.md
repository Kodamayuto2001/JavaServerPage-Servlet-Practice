# JSP/Servletハンズオン

- ## プロジェクト作成
    1. ファイル/新規/プロジェクト
    2. 新規プロジェクト（ウィザードを選択）は、Web/動的Webプロジェクト

- ## jspファイル作成
    1. パッケージエクスプローラー
        jsp3/WebContent/day1/sample01.jspを作成

    2. ソースコードを張り付け

    3. エラー発生
        「説明	リソース	パス	ロケーション	タイプ
        スーパークラス "javax.servlet.http.HttpServlet" が Java ビルド・パスで見つかりませんでした	sample01.jsp	/jsp3/WebContent/day1	行 1	JSP 問題」

    4. 検証1回目
        https://blog.devez.net/ja/418
        できなかった。

    ![image](https://user-images.githubusercontent.com/55943803/151702509-49fb7603-1098-461b-a28d-3e2211fee4ee.png)
    ターゲットランタイムを「Apache Tomcat v9.0」に指定するとエラーはでなくなった。
