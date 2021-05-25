
# Diagram #

## Sequence Diagram ##

```sequence
Yergret->John: You know nothing, John Snow!
Note right of John: I have a wolf, named white-ghost
John-->Yergret: I know I love you!
```

## Flow chart ##

```flow
st=>start: Begin
op=>operation: Be a man!
cond=>condition: Did you kill a White Walker?
e=>end: End

st->op->cond
cond(yes)->e
cond(no)->op
```

```mermaid
	graph TB
	A[Apple]-->B{Boy}
	A---C(Cat)
	B.->D((Dog))
	C==喵==>D
	style A fill:#2ff,fill-opacity:0.1,stroke:#faa,stroke-width:4px
	style D stroke:#000,stroke-width:8px;

```

## Mermaid ##

**1 Sequence Diagram**
```mermaid
%% a demo of sequence diagram using mermaid
sequenceDiagram
    Yergret->>John: You know nothing, John Snow!
    John-->>Yergret: I know I love you!
    Note right of John: I have a wolf, named white-ghost
```

**2 Flow Chart**

```mermaid
%% a demo of flow chart using mermaid
graph TD
st(Start) --> op(Be a man!)
op --> cnd(Did you kill a White Walker?)
cnd --> |Yes| e[End]
cnd --> |No| op
```

**3 Gantt Chart**

```mermaid
gantt
dateFormat MM-DD
    title Project Development Life Cycle (2020)
    section Requirements Review
    Requirements Review     :10-01,10-08
    section Functional Development
    Coding                  :10-07,10-15
    UnitTest                :10-07,10-15
    section Project Testing
    First Round Test        :10-16,10-24
    Second Round Test       :10-25,10-31
```