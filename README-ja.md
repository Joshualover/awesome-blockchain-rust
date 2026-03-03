# Awesome Blockchain Rust 🇯🇵

*Rust でブロックチェーンを構築するための有用なコンポーネント。暗号、分散、p2p、コンセンサスなどを含みます。*

> **日本語翻訳** - ウォレット：`joshualover-dev`

- [ブロックチェーン](#blockchains)
- [ブロックチェーンフレームワーク](#blockchain-frameworks)
- [クロスチェーン](#cross-chain)
- [仮想マシン](#virtual-machines)
- [汎用コンセンサス](#general-purpose-consensus)
- [P2P ネットワークライブラリ](#p2p-network-libraries)
- [暗号](#cryptography)
- [Layer2](#layer2)
- [Dapps](#dapps)
- [その他](#other)
- [貢献](#contribute)
- [ライセンス](#license)

## Blockchains
- [Aleo](https://github.com/AleoNet/snarkOS).
  ゼロ知識アプリケーションのための分散型オペレーティングシステム。
- [Aleph Zero](https://github.com/aleph-zero-foundation).
  DAG、PoS、snark スマートコントラクト（substrate ベース）。
- [Anoma.network](https://github.com/anoma).
  プライバシーを備えた PoS ブロックチェーン。
- [Aptos Network](https://github.com/aptos-labs).
  最も安全でスケーラブルな Layer 1 ブロックチェーンを構築。
- [Bitcoin Cash](https://github.com/be-cash/bitcoin-cash).
  Bitcoin Cash トランザクションの作成と解析のためのライブラリ。
- [Casper](https://github.com/casper-network/casper-node).
  企業と開発者の導入を加速するために設計された分散型 L1 PoS ブロックチェーン。
- [Chainflip](https://github.com/chainflip-io/chainflip-backend/).
  ネイティブクロスチェーンスワップ。
- [CITA](https://github.com/cryptape/cita).
  企業ユーザー向けの高性能ブロックチェーンカーネル。
- [CodeChain](https://github.com/CodeChain-io/codechain).
  プログラム可能なマルチアセットチェーン。
- [Concordium](https://github.com/Concordium).
  プライバシー中心（zk）の PoS チェーン、組み込み ID と rust スマートコントラクト付き。
- [Conflux](https://github.com/Conflux-Chain/conflux-rust).
  Conflux プロトコルの Rust 実装。
- [Darwinia](https://github.com/darwinia-network/darwinia).
  Darwinia Network のリレーチェーン、Polkadot モデルでパラチェーンとして Polkadot に接続可能。
- [Dusk.network](https://github.com/dusk-network).
  zk（plonk）を使用したプライバシー PoS。
- [Enigma](https://github.com/enigmampc/enigma-core) 分散型ウェブを保護。
- [Ethrex](https://github.com/lambdaclass/ethrex).
  Rust での Ethereum プロトコルのミニマリストで高速な実装。L1 および L2 実行クライアント。
- [MultiversX](https://github.com/multiversx).
  PoS コンセンサスメカニズムを備えたシャーディングされたスマートコントラクト実行プラットフォーム。
- [Exonum](https://github.com/exonum/exonum).
  プライベート/パーミッションドブロックチェーンアプリケーションを作成するための拡張可能なオープンソースフレームワーク。
- [Forest](https://github.com/ChainSafe/forest).
  Rust で書かれた Filecoin の実装。
- [Fuel](https://github.com/FuelLabs/fuel-core).
  Fuel プロトコルの Rust フルノード実装。
- [Gear](https://github.com/gear-tech/gear).
  Polkadot ネットワークの計算コンポーネント。
- [Grin](https://github.com/mimblewimble/grin).
  MimbleWimble プロトコルのミニマル実装。
- [Holochain](https://github.com/holochain/holochain).
  Rust で書かれたコア Holochain フレームワーク、コンテナ、Zomes を書くための hdk-rust ライブラリ。
- [Interledger](https://github.com/interledger-rs/interledger-rs).
  Rust で書かれた使いやすい高性能 Interledger 実装。
- [Internet Computer Protocol (ICP)](https://github.com/dfinity/ic).
  ウェブ速度で動作し、容量を無制限に増やすことができる世界初のブロックチェーン。
- [Internet of People](https://github.com/Internet-of-People/iop-rs).
  分散型社会をサポートするための構築ブロックとツールを提供する分散型ソフトウェアスタック。
- [Libra](https://github.com/libra/libra).
  何十億もの人々を力づけるグローバル通貨と金融インフラ。
- [Lighthouse](https://github.com/sigp/lighthouse).
  高速で安全な Ethereum 2.0 クライアント。
- [Namada](https://github.com/anoma/namada).
  インターチェーンアセットアグノスティックプライバシーのための Proof-of-Stake L1。
- [NEAR](https://github.com/nearprotocol/nearcore).
  NEAR Protocol - スケーラブルで使いやすいブロックチェーン。
- [Nervos CKB](https://github.com/nervosnetwork/ckb).
  Nervos CKB はパブリックパーミッションレスブロックチェーン、Nervos ネットワークの共通知識レイヤー。
- [NYM](https://github.com/nymtech/nym).
  メタデータ分析を防ぐミックスネットによる選択的プライバシー。
- [Nomic](https://github.com/nomic-io/nomic).
  Nomic は Cosmos ネットワークの一部である高性能 Bitcoin サイドチェーン。
- [Mina Protocol](https://github.com/ChainSafe/mina-rs).
  mina 簡潔ブロックチェーンの rust 実装。
- [Mir Protocol](https://github.com/mir-protocol).
  ゼロ知識証明によって駆動される簡潔なブロックチェーン。（plonk ベース）
- [OpenEthereum](https://github.com/openethereum/openethereum).
  Ethereum Rust クライアント
- [Parity Bitcoin](https://github.com/paritytech/parity-bitcoin).
  Parity Bitcoin クライアント。
- [Parity Ethereum](https://github.com/paritytech/parity-ethereum).

---

## 貢献

貢献を歓迎します！まず [貢献ガイドライン](CONTRIBUTING.md) をお読みください。

## ライセンス

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

法律で許可される最大限の範囲で、[著者名] はこの作品のすべての著作権および関連権利を放棄しました。

---

**日本語コミュニティのために ❤️ で翻訳**

RTC ウォレット：`joshualover-dev`
