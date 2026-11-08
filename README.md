# Repolex Knowledge Graph of canonical/charm-relation-interfaces

RDF knowledge graph data for [canonical/charm-relation-interfaces](https://github.com/canonical/charm-relation-interfaces), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download canonical/charm-relation-interfaces
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4cf84d192962b8a31958fdc2ceffd05e2142cf0f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4cf84d192962b8a31958fdc2ceffd05e2142cf0f
│           └── chunk-001.nq.gz
└── blob
    ├── 001ce4f6f2acd6552e6dddd784cd3e88574a7956.nq.gz
    ├── 00e4f2cf7358cc52446b3a38f3a4d2252c76fe7f.nq.gz
    ├── 0363cf967bd11634a865a3b457014a9d533848a4.nq.gz
    ├── 038aada964b074551415529d9548bc6662b741e3.nq.gz
    ├── 049c1bfa82791d3ade10925662bb121c251040e4.nq.gz
    ├── 04ca625ad9d8c5efa857cd79912f9af7352c05c4.nq.gz
    ├── 0650d6f43408e3b20625a4184f3d44b526c120e4.nq.gz
    ├── 07de53dd2ad537b20be6972be46760f48cbeeec0.nq.gz
    ├── 08eba0722ceffa76ad0cb0b1ecdc33edbd3a68d2.nq.gz
    ├── 08fcd82360f87444dc0951153876d6192be14960.nq.gz
    ├── 0b1fc163afa2331a89c199ec4955e827f01e8367.nq.gz
    ├── 0b41844849853ccffc86a4ec1ba9711eee3eb4c3.nq.gz
    ├── 0c2c210091e6b8a041f79e5ce62edaa9edf25e9e.nq.gz
    ├── 0cebce3b386c34b0dcfdaffadf00cccee916b6c8.nq.gz
    ├── 0e5e64390e790190edf472eb1ea3ff1d8743fb6f.nq.gz
    ├── 0ec48aa9296f4b89f102561c6ac5ac3f69bcac9f.nq.gz
    ├── 0f30cbaddd7652ef1091f085fc3f88911fd98e52.nq.gz
    ├── 10355038fe85f86eefaaad1dfda026b00e0af274.nq.gz
    ├── 10d26f821d3a4e58c476764a805fbc748df74096.nq.gz
    ├── 11ab2a01bfee6c3ecabf5735e8e9ce56dd690023.nq.gz
    ├── 12684523e10cabcf19fd57d90d3ff59d28734357.nq.gz
    ├── 15eaeed3773a32767382a6b89fc221802691c0ba.nq.gz
    ├── 179b1761cc05545bf6aeb1f70a143ebd8ab0411f.nq.gz
    ├── 19d1a54663664a24e6cced12cb76f9fdd2e37a72.nq.gz
    ├── 1abec77d98d16839a9b4d823be1913a58670d6b6.nq.gz
    ├── 1ba4586623e3b0168432cb507fb480ba2cabe487.nq.gz
    ├── 1bacf461db5894e564751d682466a676b984d013.nq.gz
    ├── 1eaffccbfc367a9e49f35e1841a0ecf8350fcffc.nq.gz
    ├── 1ec27dd953e68a4543f2f7ea6c5ca25f17260ad5.nq.gz
    ├── 20490282d4d543cee09e2f1c2253ce3c76f4380b.nq.gz
    ├── 209a96a109aa0b3aba2902e652b2ac856790189c.nq.gz
    ├── 20ab07c614ed70a28b21346db239b477842bea1d.nq.gz
    ├── 217987056915b65389f2d3a7b4da737aa2826832.nq.gz
    ├── 2247da1cfc1300a2a8ff987e8ad5f12a3d3c8cce.nq.gz
    ├── 22a4928ea14c3fef322c8f65d3b002d6a3010fb8.nq.gz
    ├── 22b870d0167c46ba313add0d8d2272bc48a95b58.nq.gz
    ├── 234a177f63a2c602eb4495693314b3b0226d8730.nq.gz
    ├── 246b04b4ba1576b810d27d1c55ed97534e446d1b.nq.gz
    ├── 248dcf149ab3b22618bdd95fb589e6c81d86e6f6.nq.gz
    ├── 24ca2be53a0118f6d60b1e586cc1c5037ecc6829.nq.gz
    ├── 25807e2b91a683fea98c55a76061a6b50580138b.nq.gz
    ├── 27333ccdcc8eaead625c85fb5c84240dbc13cf11.nq.gz
    ├── 290d6c80ef4abe53b98f45e3a5eabb5e1e40c855.nq.gz
    ├── 295140cfdc8f61356533931c3d9a6dbe395f0c16.nq.gz
    ├── 29586d01256972f18aa23df56bc7efd3da2b9d0e.nq.gz
    ├── 2ab144532395933d02f2d13268942c9dc7921798.nq.gz
    ├── 2ace380aa9d8f44a3409adac49d9a71180fab34d.nq.gz
    ├── 2cdac790fee9d7523c3e70016bc868316f2f5e68.nq.gz
    ├── 2d99e6bc0fba6083ae85295bc144afeb3ebcb84e.nq.gz
    ├── 2dcbfc8bf87007b982917185edddd461590e5195.nq.gz
    ├── 2eb684f3d28ab366fdf69c55c8ca2546403b2566.nq.gz
    ├── 30146b1d5a0639204f94572e7e61877e12c33d3c.nq.gz
    ├── 305f424b9224f4bff39cfeae8e3bfd9b54fef8a7.nq.gz
    ├── 3091115390707c71306e092630b143961d6af0ed.nq.gz
    ├── 31daa9fc884ff43d259ef7b904cb23ea9519ba63.nq.gz
    ├── 324d2feaf3fb9cbf120bdfec7df3659c2bd22550.nq.gz
    ├── 32e03b517f9a5e531cda2d0c0251414d759d7c0a.nq.gz
    ├── 336fb140aa189e4c6bae8368ac7dc34b52fdde5e.nq.gz
    ├── 338e3504370a42272bf69bd3126288ca7153cce7.nq.gz
    ├── 33a77316b8030bddf279d3d7839272eb91a2ef95.nq.gz
    ├── 33ad9413ac274f435089764424bae6b21f48edd0.nq.gz
    ├── 33f1bebbd9c06e09d06f81d844631915b3ff9d35.nq.gz
    ├── 372182d917f7dcc8f75b9572fbc0d4fef82c1ffc.nq.gz
    ├── 3985a42aa6cca39a540e382c88dfb6ad98825168.nq.gz
    ├── 3a89a6aa14fd60a66a280cbd3cff2a6fd4cb9e64.nq.gz
    ├── 3cc6c2d4b6bc6dbd33622ea067d4cb9de63b7ddc.nq.gz
    ├── 3d48efef43f599943bebde662e1ef5dbe40d6abe.nq.gz
    ├── 3e89bf2b22fc2aa20d5a582564517c6e09b380ac.nq.gz
    ├── 3fbaac585f699576be9538e7d1d2ed6f8aafddcf.nq.gz
    ├── 41242e0eb6718e7aff5ba41cd623c3aa3bbaf157.nq.gz
    ├── 421bff9fd6da123ae8c248cf9715a8eede5780d5.nq.gz
    ├── 432df6cedbc15f904c32b1d759258228f4cd3d47.nq.gz
    ├── 44ff280550af59c24173af537dfd7e0161e1af41.nq.gz
    ├── 462100aa0a1e99428cd0d6478d9d2386d1ffc5f2.nq.gz
    ├── 47ad447c414d20693cec857f94b33c8d790d5868.nq.gz
    ├── 47f2a6e8da962f896f39910e4617ab2ab0e8fdff.nq.gz
    ├── 4891b4f585061cd01b9eae12b8adb2582ae0ebe2.nq.gz
    ├── 4aea3b77e8cbcd808f09376229664b1830119f9d.nq.gz
    ├── 4b21dcb9efc6988f6a7518343055ba30fc73893d.nq.gz
    ├── 4c05248edc41e83f2519e63c1dbee12982dd8a1e.nq.gz
    ├── 4e6e6942e9a2917358c7216d56ef8c1e14d5af3f.nq.gz
    ├── 4f8f319c958e89b303566dd4f00fc43ffc6ee1fb.nq.gz
    ├── 510d2b5d95e78ed4ad5a2d5237a3d45f8f4d4e53.nq.gz
    ├── 511aa54e1dc1812a3531c4a5d95a71128dd2b017.nq.gz
    ├── 54a12871ef40536df8bda4950de4b04bbc1b1479.nq.gz
    ├── 57d74ff86a5a48bbb5ae27fb3641d0664ce37dfe.nq.gz
    ├── 5848d148e0b118c3a53d65dc92e185ba73f329e5.nq.gz
    ├── 5865588e3d225b36cd7427ad9e52f28d1a95e52a.nq.gz
    ├── 5957e8344b3be020ea528b0670f557b2c9815fce.nq.gz
    ├── 59d6dccaa08590e8e6a4e33f46fc79a8a7887884.nq.gz
    ├── 5aed6e207717fb98c760f21f417492e2f6b51d8e.nq.gz
    ├── 5c670653679acfc25bdb59fde4d00041487079eb.nq.gz
    ├── 5d5a1350d27e54249b0f6867025de03faad8c315.nq.gz
    ├── 5f21bdc39441e56456a385583b569de596f614d4.nq.gz
    ├── 5f3d8c47644cf340fb253c977365ecdcf35f3084.nq.gz
    ├── 5f8ae9d4ee7557df149b97a584cb15160eb35b9b.nq.gz
    ├── 61ee6bf6ece6d28bff979f8f6d2b4e1220a225b5.nq.gz
    ├── 640b95c539187721da252dc1e2e60f3379ef98e9.nq.gz
    ├── 65a456713d51b1414c30c3dd985817ef6a5c043d.nq.gz
    ├── 66acfb8558fdf5a31481b417b532d83bef09a4ff.nq.gz
    ├── 66f4883000bfc4bc202e4b99a83e34be65e6628d.nq.gz
    ├── 672864688c42195691881ce90f31f9b628465086.nq.gz
    ├── 68759a710dd01b8507142c9082293761e5a383b6.nq.gz
    ├── 69509901ef421861a5891e77eca24a5dd7ed4480.nq.gz
    ├── 6a6c72089df3a92e648082513b889696a7100c6b.nq.gz
    ├── 6d43f4a4d9cc92f4c0c684b2ebcc499c0bf0099a.nq.gz
    ├── 6d46571fbcd33161d6d49a7f08925da5e72ad00d.nq.gz
    ├── 6e45a1d68ed9801e048991b824058044a4938602.nq.gz
    ├── 6ebb2e529227fd210dde67630274e5224ba02d85.nq.gz
    ├── 6edceeb238fb2b104f5dfa683d3f98ef819fdd38.nq.gz
    ├── 6f9e71b05e741ba6a92d2ee62da0297c62e4feea.nq.gz
    ├── 714fa8425dd635d88b2372f0a1ab46f177b16300.nq.gz
    ├── 71670dbd9e0856265fa9d846606e269158885cff.nq.gz
    ├── 71c4fa925e88e3177c4c9f38d63dac88bca225bc.nq.gz
    ├── 727c5f1a121ef67a78c4a6e1a650d4166159daf8.nq.gz
    ├── 7334b4f159178d9757ea1ef3f9ccbc56dd269eae.nq.gz
    ├── 752e68bfe28b539edff14c6d8b1056ce600f19dc.nq.gz
    ├── 75da06bae15f1c67c96e1e57e79f64a25424c7da.nq.gz
    ├── 7605e6a05044b09eba42ffb0dc95fab5eeb589e0.nq.gz
    ├── 763558a8a90a154c21ad09f297fb7846c69902ef.nq.gz
    ├── 769d8d3653a7b10c1bda86bbbc34e8a3bb84b6b3.nq.gz
    ├── 7a087d16bbe33544ce9daadab2675404cb2e3bc9.nq.gz
    ├── 7b857cc05248e1fa6a7b86c335bd3e2726a2e9c7.nq.gz
    ├── 7d5e6e4ee3d58b659022308f5e5840fba9d18787.nq.gz
    ├── 7ddf27a92c6305fbe151dbf9c6bdd07be66e5fef.nq.gz
    ├── 7ee325e477f4b863899dde155aca9b9730c8ad9a.nq.gz
    ├── 7ef14a7869a02ecf0b1ae98cda1cc8cf8be3046e.nq.gz
    ├── 7f1f9c7b6bad2dc76dc6940cf129a206cf272842.nq.gz
    ├── 7f50fe9e96d2edbd0e9ce10cafeac7ab5206f1b7.nq.gz
    ├── 7f53cb6d201d7bf003377da41f2b8e3866e5c54c.nq.gz
    ├── 811f00bdac276ab0a04e7bc0789a1d9d32f2c227.nq.gz
    ├── 8127535aba0ea90f118ffc973380fa8f04750526.nq.gz
    ├── 8128cdb2a33998e4123e0973f04969caaa6cceb4.nq.gz
    ├── 8145e32ab1f293c30f665b79e29357e02f86a51f.nq.gz
    ├── 81af3bb0284e54fea41cd8767bd859b59b064efc.nq.gz
    ├── 8214105e6a548f5711a5cd6405b1c74e17295163.nq.gz
    ├── 837de3f50250d998c2b8a329778850dc1ac0ec37.nq.gz
    ├── 845a88852289cf551a04a09bf9cf159f29f13f76.nq.gz
    ├── 850c6f83854709a8d4c736cb82dfb1f129934a18.nq.gz
    ├── 85670539acd592340fbe14b2dd3f2209ddb39550.nq.gz
    ├── 85bd2c009dd0905547d044240e57dfe8135cdcaf.nq.gz
    ├── 8673501f1f20500c191204bd1afaeb8879362d2e.nq.gz
    ├── 870d9c1f85c845d5c5d2b8c784505985e05a39ed.nq.gz
    ├── 87a510759383481e86f7004ea23400fbb4906d29.nq.gz
    ├── 8d653f7a5c36123b6bdceef79ce2bb0ca8491db5.nq.gz
    ├── 8e69ce36214c51b68240bc559864245fda8b8852.nq.gz
    ├── 9024bf658a9741dad627efbc45eb562a987eb045.nq.gz
    ├── 907bbc487b2ef4a4336eb8881118ad1f9db7ac9d.nq.gz
    ├── 925d621b942db74414c8deba5b56180d48b06c93.nq.gz
    ├── 936c0a8e123b06ac9de2b288da1bcbd336a225a0.nq.gz
    ├── 949274f0958053bed9c884832fc46188ffcd511e.nq.gz
    ├── 9518ada19cdec2cf3af5c740feaa3d8eac637f37.nq.gz
    ├── 95bd19216c0446359d54dbca66be068a59f36229.nq.gz
    ├── 97d2b38ff903e94e1cef76ae2176e7a21ebec6b4.nq.gz
    ├── 985c95c41c27bf131e05c18f282b5ef89b3fe61e.nq.gz
    ├── 9b09ba7d86bccab03a7df47f4853ef6be243e06c.nq.gz
    ├── 9c28c052465da8fc2cf25214cca4270eee5f7a97.nq.gz
    ├── 9ed040af0a49975e3b679f7a58b8e0b37c0740fa.nq.gz
    ├── 9ed75d9ba1d011a20879f6a5e9e4a0ff2cd10021.nq.gz
    ├── 9f1a5ffe5fdf8dca58ec56f069802038c36647ec.nq.gz
    ├── 9f5f8ad6505026ac447a0465f5218eb1b50a0ec6.nq.gz
    ├── 9fa2853d15b65b461a0733817b035c984527ee23.nq.gz
    ├── 9fa658697ba29d241abd534f818fdcc864d16a97.nq.gz
    ├── 9fd3fa49d6d05538f680358e67e87c9ed37ffd41.nq.gz
    ├── a26eeec49716cb089d62fb4dd840161c46d09c76.nq.gz
    ├── a2843f7f8dbbc180a340b95551a3a2ddbdd4297d.nq.gz
    ├── a2f75d061a14e33015ac506a0967696316b1a8f5.nq.gz
    ├── a46fdb977940faef4cdb429902d57755477a0fce.nq.gz
    ├── a6ceecf14031f409b9709a4ac13d8ce366f3df41.nq.gz
    ├── a9925c2edda4209001fe19afeeb1a8d87fdd1a7a.nq.gz
    ├── abe6333eef55172cfbc30856a8094fa901bfb668.nq.gz
    ├── ad5ec123ef66603628ae19e6a9971d8b969d2235.nq.gz
    ├── adde825aaa11819d3a971386c4cd9af4c26e8c6b.nq.gz
    ├── af77d24a84c2b7f3b5dc70a26bc668e6dc3f9ac0.nq.gz
    ├── b060a994f9c38c3bee97224a80a31d1a78a93b08.nq.gz
    ├── b240c787facae3d9a9aa55044d540268b7b252c0.nq.gz
    ├── b336d6236e2376d4ae2fb503dddc46c6eef87524.nq.gz
    ├── b49ea8dce109ae81b698ae931daa60f0f602c908.nq.gz
    ├── b4d33743299d8c9e128ab635f17d4ce75b551d2d.nq.gz
    ├── b57256376cd8ef15830e0374d6baf727bd2f39ed.nq.gz
    ├── b5780711141ec01206e8f04ca470befe249c54d8.nq.gz
    ├── b5860ea421205d8eae01e40291fc7c642e866e41.nq.gz
    ├── b58804ccc1e970cfec83f592a0895cf9675b5967.nq.gz
    ├── b5cfb58c8be5bf5923ac90420e685eead9af8fd0.nq.gz
    ├── b5f45bef27a579b21a33e5bbf11b9172cfad8bdf.nq.gz
    ├── b67c3e190492162d927e8f6fd7c16d8ea24f53de.nq.gz
    ├── b67f6e7ef57cabcc8d4ee4bf7e7acd1e9881efa2.nq.gz
    ├── b7b1b06d754ac9397d66de7ff94d4bafe5f578f4.nq.gz
    ├── b902fb72acad97336ab1be13d003a8f24bc28d05.nq.gz
    ├── ba9f5c48a30f780a86ed73e0fc5c358a084e796b.nq.gz
    ├── bad9a847ee3f82b588a342b17def9f0696655606.nq.gz
    ├── bccbb52cf5693fa2b44723097d6cadc884c00049.nq.gz
    ├── be56bcaa70d1200f46e474608acec3ca29483492.nq.gz
    ├── bf6e479eca6b221adbe6ea8315dc33ae5f19ebe4.nq.gz
    ├── bff09bed555d777fddc1a3daf3f2b1f626bf277b.nq.gz
    ├── c0d73faff665142cac6f1ebd99d6478b980286d7.nq.gz
    ├── c3168ad7862f1cd67eb555046c6f19e8b9bc969b.nq.gz
    └── c3657b2513da3a5be7fe155edc09f3f5cdc4c127.nq.gz

7 directories, 200 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[canonical/charm-relation-interfaces](https://github.com/canonical/charm-relation-interfaces)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
