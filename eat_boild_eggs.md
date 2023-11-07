```mermaid
flowchart TB
    subgraph one
    a1["ゆで卵を食べる"]
    end
    subgraph two
    b1["卵を買う"]
    b2["ゆで卵を作る"]
    b3["食べる準備をする"]
    a1-->b1
    a1-->b2
    a1-->b3
    end
    subgraph three
    c1["銀行でお金をおろす"]
    c2["スーパーで卵を買う"]
    d1["卵を洗う"]
    d2["湯を沸かす"]
    d3["卵をゆでる"]
    e1["腹筋して腹を減らす"]
    e2["殻を割る"]
    e3["塩をふる"]
    b1-->c1
    b1-->c2
    b2-->d1
    b2-->d2
    b2-->d3
    b3-->e1
    b3-->e2
    b3-->e3
    end
    
    
    ```