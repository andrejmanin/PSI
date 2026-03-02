# Info
#### Architektura
 - peer-to-peer (P2P)
 - klient-server
#### Rozlehlosti sítí (Розмір мережі)
 - Osobní - Personal Area Network (PAN) (~ 1 m)
 - Místní - Local Area Network (LAN) (~ 100 m)
 - Městské - Metroolitan Area Network (MAN) (~ 10 km)
 - Roylehlé - Wide Area Network (WAN) (~ 1000 km)

## Základní síťové topologie
**Topologie** - způsob uspořádání linek mezi stanicemi (uzly) v síti.

#### Circle (Kruh)
```mermaid
graph LR
A --- B
B --- C
C --- D
D --- E
E --- F
F --- A
```

#### Star (Hvězda)
```mermaid
graph TD
Center --- A
Center --- B
Center --- C
Center --- D
Center --- E
```

#### Fully Connected (Plně propojená)
```mermaid
graph LR
A --- B
A --- C
A --- D
B --- C
B --- D
C --- D
```

#### Line (Přímá)
```mermaid
graph LR
A --- B --- C --- D --- E --- F
```

#### Tree (Strom)
```mermaid
graph TD
A --> B
A --> C
B --> D
B --> E
C --> F
C --> G
```

#### Bus (Sběrnice)
```mermaid
graph LR
Bus --- A
Bus --- B
Bus --- C
Bus --- D
Bus --- E
```
