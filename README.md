# training


```mermaid
graph TD;
    A(リプロシーケンス開始)-->B
    B[ファイルの収集]-->C;
    C{結果評価}-->|成功|D;
    C-->|失敗|E;
    D-->E;
```
