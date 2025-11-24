# supplychain-sec-test

[SBOMを使ってサプライチェーン攻撃を検出する方法]()のために作った作業リポジトリです。

以下でSBOMを使って脆弱性できます。

```powershell
choco install grype -y
grype db import ".\vulnerability-db_v6.1.3_2025-11-23T00_29_04Z_1763882453.tar.zst"
grype sbom:PenguinCabinet_supplychain-sec-test_9c5c45.json -o table=scan-report.txt
```