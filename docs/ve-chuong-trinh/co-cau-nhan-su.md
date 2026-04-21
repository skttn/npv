---
icon: lucide/network
---

# Cơ Cấu Nhân Sự Chương Trình Cơ Bản

``` mermaid
graph TD
    BDH(["Ban Điều Hành"])
    DP(["1. Điều phối"])

    NHT(["Nhóm\nHội Trường"])
    NHC(["Nhóm\nHậu Cần"])
    NHTX(["Nhóm\nHỗ trợ từ xa"])

    MC(["2. MC / HLV"])
    CS(["3. Chăm sóc"])
    TT(["4. Tổ trưởng"])

    KT(["5. Kỹ thuật"])
    SX(["6. Sản xuất"])
    HC(["7. Hậu cần"])

    KTO(["8. Kế toán"])
    TVV(["9. Tư vấn viên"])
    MTT(["10. Media\nTruyền thông"])

    BDH --> DP
    DP --> NHT
    DP --> NHC
    DP --> NHTX

    NHT --> MC
    MC --> CS
    MC --> TT

    NHC --> KT
    KT --> SX
    KT --> HC

    NHTX --> KTO
    NHTX --> TVV
    NHTX --> MTT

    classDef dashed stroke-dasharray: 5 5
    class NHTX dashed
```
