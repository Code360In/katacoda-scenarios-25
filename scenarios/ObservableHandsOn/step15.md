# サンプルアプリケーションの可視化  
アプリケーションがより複雑になると、Scopeを使用すると、アプリケーションの構造とパフォーマンスを表示および管理できます。  

これを実証するために、Weaveはマイクロサービス参照アプリケーションを作成しました。 docker composeを使用してリファレンスアーキテクチャを起動します。  

\# `docker-compose -f docker-compose-weavesock.yml up -d`{{execute}}

開始したら、Scopeを使用して、新しいコンテナとコンテナ間の接続を視覚化します。  

**（表示例）**  
![Scope demo](./assets/Step15.png)   