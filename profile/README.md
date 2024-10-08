
  ![Sirk-Tek logo](https://github.com/sirktek/.github/blob/712e0fb32211d11095d7602c6daef9538dc20f2b/profile/img/sirk-tek-logo.png)
  
Sirk-Tek AS is a Norwegian tech company developing systems and tools to realize
the circular economy.

```mermaid
stateDiagram-v2
    Production --> In_use
    In_use --> Service
    Service --> In_use
    Service --> Disposal
    Disposal --> Service: Reuse of parts
    Disposal --> Production: Recycling
    Disposal --> [*]: Destruction
```

## Sirk-Tek Assured Quality

The [Sirk-Tek Assured Quality (STAQ)](https://github.com/sirktek/sirk-tek-assured-quality/tree/main/) is the internal quality managment system.

## Developer information
- [Development process](https://github.com/sirktek/sirk-tek-assured-quality/tree/main/4-devops)
- [Architecture](https://github.com/sirktek/sirk-tek-documentation/tree/main/architecture)
- [Current implementation](https://github.com/sirktek/sirk-tek-documentation/tree/main/implementation)
- [Design guidelines](https://github.com/sirktek/sirk-tek-design)


### The SIRK:tag application

The [SIRK:tag](https://tag.sirktek.com) application is a service to tag and manage assets and inventory.
Tracking and managing the life cycle of assets  makes it possible to reuse, redesign
and if necessary recycle whole or parts of these assets.

- [sirk.app Frontend](https://github.com/sirktek/sirk-app-frontend)
- [sirk.app Backend](https://github.com/sirktek/sirk-app-backend)
