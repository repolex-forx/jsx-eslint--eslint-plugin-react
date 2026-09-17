# Repolex Knowledge Graph of jsx-eslint/eslint-plugin-react

RDF knowledge graph data for [jsx-eslint/eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download jsx-eslint/eslint-plugin-react
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2c98b83c451a4297edf1787d9a616e50687e27e8
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2c98b83c451a4297edf1787d9a616e50687e27e8.nq.gz
│   └── repolex
│       └── 2c98b83c451a4297edf1787d9a616e50687e27e8
│           └── chunk-001.nq.gz
└── blob
    ├── 00067c89d6e3968152233b5f630c952196d16143.nq.gz
    ├── 000d7eb4a996fb84daae09a97e4c4162e560682a.nq.gz
    ├── 002a1ed94258bae60c80594fd3419d8ba68756bf.nq.gz
    ├── 010d658041e2d089128dd7e316b44273a945f71a.nq.gz
    ├── 01dcb360ff75ea19aa9123e25a2c43ee8b82ba9e.nq.gz
    ├── 01f80be41a9b52e118fe611791003db8d3ed53d6.nq.gz
    ├── 031ad6ce5517b9eda9f167e860a48ff02a2bcd14.nq.gz
    ├── 0426f9f81a3ca307e2c46afa8d7907aa786e732e.nq.gz
    ├── 046ff795829e13400f72011cc751a5227d1757cf.nq.gz
    ├── 051cf436340ee38c78f58bcd4ad3c3b25a9463ff.nq.gz
    ├── 053bf08dab3857aa3a42a7b11f676ae6b68d2233.nq.gz
    ├── 0620c5068696296f16f147f3d55868843e94d165.nq.gz
    ├── 06807efcc6eb71d71c0f5a83bb98c93a91875013.nq.gz
    ├── 071ecd68ab0d19674845b1a7344ae504cdb317df.nq.gz
    ├── 078e30c5904f5ab5d4daae0ab75a016d732f6035.nq.gz
    ├── 0938613ca7581b3c5b970d9c9cfcd4936eb1f1f8.nq.gz
    ├── 097e6477649668abdae55075ba571288dde7e959.nq.gz
    ├── 09dcfb5b588fc13ceaa09dd72aa96d9b64bbca3d.nq.gz
    ├── 0aaca2cb00e436dd149f6d2f529789b4d6742b16.nq.gz
    ├── 0aaddfd290419c5a542286f62b752d67aaa362df.nq.gz
    ├── 0b6a323c4f481fad48b2e7b5fd0bda04c0fa1895.nq.gz
    ├── 0c5931345f87841e43f0d28bf6f11e67e4842cef.nq.gz
    ├── 0c9962a4de876af69a7a9d22686f88b9a7648da4.nq.gz
    ├── 0d6c9cdc066fd5be15a480e0e9106619e3120144.nq.gz
    ├── 0df43ac2d101ca087dd658691f91b0c9b9e99893.nq.gz
    ├── 0e2008478534a5c4fd547cc5a6784cf835d25adb.nq.gz
    ├── 0e73ab1a3f08f146ce5b5e5840ecc003a52d4571.nq.gz
    ├── 0f17143ffa0feff3a673d6e6fcbb47f3bfdecd5c.nq.gz
    ├── 0f8ed6ee4c0c720846aa53c950835ce10e04a658.nq.gz
    ├── 0fe74dab5e9cbc8d0dd7a8b26e4bfff5052271f4.nq.gz
    ├── 0ff292cadceeafb4e92e66a3ba0bb04b366106a1.nq.gz
    ├── 1090dff063c34cec4e91ced771759f02d747734c.nq.gz
    ├── 118f9dd81dd110f4d003c842e71e6c2fa9adcba3.nq.gz
    ├── 1192d4a3c62cd61060e7c28fba0f38d49d31bbaa.nq.gz
    ├── 11fffdad16dd13965d8c5309d0c06ca74ad89f51.nq.gz
    ├── 122fb545af479f2c62f10eb9277a3d6d776b8af2.nq.gz
    ├── 12625fa704626dacfc590b9ce51fc037d1798688.nq.gz
    ├── 13d0c10ac77e5c8fb51f4b83e0b40d3e83d3492e.nq.gz
    ├── 13ec64dd0eddeda00fdc5b538fa3f63aeb2fd69d.nq.gz
    ├── 145ad25780cf2ca507649de1779e2e6a3b617dab.nq.gz
    ├── 14fcf06a73ab040c8ea48f0496a7cd433b9faec3.nq.gz
    ├── 152d7d9c587856b6279c7915357900af3cc49041.nq.gz
    ├── 15d651db3a8cd181d4c5776d163027546d667941.nq.gz
    ├── 168620fa3d82e8e4746b1f1bd3d8b06ed54cd99d.nq.gz
    ├── 16b8aaae8f59afb1bb5255c3325ab1bb1de7e30f.nq.gz
    ├── 16ddd47f357215df2255deeab69769c3deee73fb.nq.gz
    ├── 16e6be43b9223b02789555641ef352a586d602bb.nq.gz
    ├── 181ed377b88fe3362e45d2d18943c4bee76f18bb.nq.gz
    ├── 1859f752317fd1b3fd1c6d7ee6ac35d739baa93e.nq.gz
    ├── 18811d37ad6b6e0b1de3100c5164e2914bea0c5b.nq.gz
    ├── 18fd1ca83c2d1e3bdd103f032c75d423d16c75b4.nq.gz
    ├── 1934e67b63151f7cad2b6e0da96b4ebd8976171b.nq.gz
    ├── 19af33125321849d25702827e718ead4924037d9.nq.gz
    ├── 19cbda4cf4f48324ad3fed5330c577239b0a48fd.nq.gz
    ├── 1a88c70b2f9c23e9737997c39b97300ec501ba30.nq.gz
    ├── 1aa8ab4ace578cf6eb7a075b134cda198ef044bd.nq.gz
    ├── 1b23dd88eee8d853ef171776e0c13e28d71e09a7.nq.gz
    ├── 1d7bdb38f6aa6e05016232b7275292c60718ff08.nq.gz
    ├── 1e271b2a686a6e74917980cdb5e6da8eb5070250.nq.gz
    ├── 1f8bb551dbbfe70e1b77ad2b15adecbc1d15c30c.nq.gz
    ├── 209b6abba73ad45e971418cc24e045c9058049d5.nq.gz
    ├── 20ca5d93241c1956cbbb079287ee64ae1aec2ed6.nq.gz
    ├── 20d191d26483c1a4a436474229a697645433cdb4.nq.gz
    ├── 21844eee2ef231937379304afef29ec9547782e6.nq.gz
    ├── 2269e208cad85228a3b99b8b7179ea7c4635a6d8.nq.gz
    ├── 23b71cdca59ff40308b90fcf96fba08180b636d4.nq.gz
    ├── 23e168605f366735ba51f04a2d2bc2e4debe7691.nq.gz
    ├── 24d9a37d02b00eee06fda59a79b58b6dda990d1f.nq.gz
    ├── 2683bfea4cba4c9cb4e286954d164731fc949127.nq.gz
    ├── 271300595d5455190a9d16e68c49f9ce14585e05.nq.gz
    ├── 2bc1437ff1d8ffd62632170376c4307d1d408ebe.nq.gz
    ├── 2becfef8a0dbb9d523197c85e7ff2e42dde2c02b.nq.gz
    ├── 2c503eda8fd3ce1804eaed1b40d46ea9a7e4521c.nq.gz
    ├── 2c5ba7a5c11310323968da329c13835ca4aa12f2.nq.gz
    ├── 2ce0bd816e3829a625f13dde7d72ec06471204bb.nq.gz
    ├── 2cef238841efc021bbb136d62b9d4fe29997a25e.nq.gz
    ├── 2d1cf681cdf881f38735b460a7b34f29c6b9b146.nq.gz
    ├── 2d423e8ad696918e84affa7d14d0ec07dbfb6253.nq.gz
    ├── 2dd4412b87e7d57d0d46415cd2816e73f6b34e7e.nq.gz
    ├── 2e4a618b81981bb063515119206b75ec834a7c75.nq.gz
    ├── 2e5df666687861ad5fc1a809e6cab83e19faaedf.nq.gz
    ├── 2e654951b6c48fcdd2350c6bf74e7e1adfd4041a.nq.gz
    ├── 2e8aa687dc1def4061e973ae751e2d6ec49d44ac.nq.gz
    ├── 3014d24f1ecca079995c3ef24482994efb798526.nq.gz
    ├── 3038951327eb86abfd7ba496d1cd466f4b74299e.nq.gz
    ├── 30a00364dbd46267834657431a0e6533efcab675.nq.gz
    ├── 30df9c02c1bad654f1867980ecc3fbbe73d7bbaf.nq.gz
    ├── 3103be86da1bf447c358b491c6bfe9c917561c5a.nq.gz
    ├── 3123c5bd5ddb97e74fea7d49fa8bed16980db176.nq.gz
    ├── 319299684ae7e2af0f9db645b0d39fc60f80d2c5.nq.gz
    ├── 3229d16bf48ebeb62b6dde1a93438ae4116b3971.nq.gz
    ├── 34e81a0047b059460b36c1204bc58f31ffdef4e9.nq.gz
    ├── 3539f481368d3bfc19bcfc753dee60fefef5ef17.nq.gz
    ├── 364a2e7c999c9a9c1f95ef819ed0b6074c79582f.nq.gz
    ├── 369b22ec5879a42a169f27f8aa023acd13e6d797.nq.gz
    ├── 381b44bc891d2d2d8e110533ce0e372f68cf91ce.nq.gz
    ├── 3878a29e0b31c2aa433bac0a672945b809b5da17.nq.gz
    ├── 3a0b7de4c951e7ea92a9de7bac924ba95d643342.nq.gz
    ├── 3ad3378abf43067a1ada2185e2e837cc25e0252f.nq.gz
    ├── 3ae61e3d9671ff6c0601cdee35a1f4754d69b5d2.nq.gz
    ├── 3b01998502e7a6d5b4697b563cb6be571551a15c.nq.gz
    ├── 3c3cd24e3ffd648dc949a08232a409ba6a08e11d.nq.gz
    ├── 3d6252168f25523dbf4867167cb9e9646bc2b12f.nq.gz
    ├── 3dc180be226c40364aeec4afbab2dec5d747ab4a.nq.gz
    ├── 3e626d61bbd2164a2df52b2a44d6fa803287de65.nq.gz
    ├── 3ec2cb23b6b2984ac9a236bd32db3e4b91eec6ec.nq.gz
    ├── 3f3c6ea9b3bae8786af8f347d3e2dff9b5fc1528.nq.gz
    ├── 3ff23e0230413db13d92f23ea5aade61b6483d29.nq.gz
    ├── 4099d0d81cb09715160ce001e726e4fdeb263114.nq.gz
    ├── 414f9a05bd9d515f411c5d6d4b5fd6067836505f.nq.gz
    ├── 41eb307d6bd5d7533b4d453f074ec63d9675cbb0.nq.gz
    ├── 42d19734c2ddacc9da06837f4611e619e01ef1b8.nq.gz
    ├── 4356cc2a5e5efa9a378a995affb77666f89d559e.nq.gz
    ├── 43605edffc061c3cff9321f20506aa1b53973509.nq.gz
    ├── 43c97e719a5a824700932f72e6e7e6748ce45d01.nq.gz
    ├── 43e3fa4711ba3cebe06809d87cf2529e63689299.nq.gz
    ├── 446fd9022af8c4a0ea38c0c57089d93b41411da9.nq.gz
    ├── 44967bf03cba12524a79e871f2256c3b94579f42.nq.gz
    ├── 44de1fa02336b3fc85becc77019db2f49a2c6e2f.nq.gz
    ├── 452b1a1ef2819fff07b9a99e449c856325219890.nq.gz
    ├── 4572e7ff8d688b930be33829dc53f5dcb98ed367.nq.gz
    ├── 45c9a54c48214c1fc25b0155b5215f3d611abe65.nq.gz
    ├── 45fa214ef4f17f8e98ce943ca8e487847bc17b7d.nq.gz
    ├── 4638a8700d0b6f9f3849f4427cd4af1aa9d9d386.nq.gz
    ├── 46847cb1950708b849a32d53152cddc85a585a2c.nq.gz
    ├── 475f97aaa6537ee12f88f1a8da643a3ad9d58946.nq.gz
    ├── 4788b7db4932a7a84de68e92856b6c2e1a42afc5.nq.gz
    ├── 4a2cfeede66b68255ca48bc38c0eb2f1537a785a.nq.gz
    ├── 4b42904c63ad1d7d854a76b20855c56244a860c4.nq.gz
    ├── 4cd3b1c5ad01c10e915b3177e1df04f3ae8b73ed.nq.gz
    ├── 4e184a7918891ad11edb288461f26b9c85abc01b.nq.gz
    ├── 4e62a82eb3cf0b3e0b31aca3d9e7dd57b2b33c18.nq.gz
    ├── 4fc4f928ad3336fe7d0ca31b723f3d695dd0d15f.nq.gz
    ├── 51830d448681acfd35316f72c5a17d56a0427e6b.nq.gz
    ├── 5227d9448b09822d1c10f06b7b9b420e20e32b4d.nq.gz
    ├── 53013f5a584d000c64fe3f6112634b5fc4572738.nq.gz
    ├── 549d7b4823e0c7404ec45ef98a5b22b755c96194.nq.gz
    ├── 54dbed49cffd1912e2f99a141ff37515b8f1f7c2.nq.gz
    ├── 54f478aa181720cb3b7de28a07feb0b7ad273c44.nq.gz
    ├── 55271e15f2966dd4a8c05a4349e6187a9c7f9053.nq.gz
    ├── 5587aa90f977a531b7751ab394e7e39b9d9b96a4.nq.gz
    ├── 560911342a8b232880b874eb54fc18866462525f.nq.gz
    ├── 566860d13909c4e7844e37a31d4dab5be6c2ed8f.nq.gz
    ├── 56a2abf018da0172a897ada6065308569c46d5b2.nq.gz
    ├── 591887e57e5a48b0fc956ff2ae6823e358190389.nq.gz
    ├── 59d756737b8ca3bdcdcfaf1ab4a0b18646cc673f.nq.gz
    ├── 5a48b15a8838872b3237e47327d14497f5102972.nq.gz
    ├── 5ca904e03d6b278ffdf02f7a24aee126fb80d85d.nq.gz
    ├── 5cbdc683c1b156c2f112394875498a2f09faeda3.nq.gz
    ├── 5ceee4ab22ce5071945fc0f88cd05fc4d17fca96.nq.gz
    ├── 5d64f76cd8e3e55964ab236fd1859a71b573dfee.nq.gz
    ├── 5f02cd3af8d79417d88e51d3325bb96195c79d25.nq.gz
    ├── 5f67e705c50d88e3b79a3982ff635d5f4640db7e.nq.gz
    ├── 5f6f6efe38df70c90529f2bf59cd171c34e484b3.nq.gz
    ├── 628eea3adfaad9fee1808a345bf9e21851097465.nq.gz
    ├── 62961cf958066aa2e4c5e25759f6dfa01629e01b.nq.gz
    ├── 64c4aadddbc91bfa259e5e25e3db3eef653e8bcd.nq.gz
    ├── 64ff5e4ce3ffe1ea3038a0281fcb88c3e898d1f2.nq.gz
    ├── 64ff9bbdc46ae8ce952969e9deafc11d8aeda46f.nq.gz
    ├── 65169f207508814ba28e6b90ad8ceddfa368b52a.nq.gz
    ├── 653d7a687ac44c89f472ddac23ce5400d677e662.nq.gz
    ├── 6594ac4768e6116403d79f726af6923123a8bf44.nq.gz
    ├── 66d23b8cdbf975d933be336e08dc27adac75ffa0.nq.gz
    ├── 66dac8803d1123db917fec53e5c86d4b34e8479e.nq.gz
    ├── 66e96ef9ed06b91f3f8196906a6595ad0fadecbd.nq.gz
    ├── 67ac1b47f6286c4a5a5d94b56826e78f0324cfb6.nq.gz
    ├── 6828f07ce50c5c974c1480e3f6d8e9a6f21eb5d3.nq.gz
    ├── 68891a091b5a284638b488b208b0d204425553f2.nq.gz
    ├── 6920fb24bf6aef9ff714ac5e0821053002a44061.nq.gz
    ├── 697c35cfa2f88dce089d9d16f7ee0f4b6c167e48.nq.gz
    ├── 69ed6abc695c01c0a3914bb780106d31a1c6150f.nq.gz
    ├── 6aaebea184cde95baafc85413fe3de5aeb0a2421.nq.gz
    ├── 6b5a43eae76c0696a07edd1bc748cbf11a525f6b.nq.gz
    ├── 6bebe31137850c1938338f029bc5bcca92051b55.nq.gz
    ├── 6cbf2b802f96871b0670236621ec37289df395c5.nq.gz
    ├── 6e254f772fddb2a23e6e9d5d52bdb53b2626480a.nq.gz
    ├── 6ed7302a47fa0100a422e03e908402fd9de2b1c8.nq.gz
    ├── 6f5ad50bbf5c162122a079fbd6f353ad58b776ae.nq.gz
    ├── 6f5f4f6cc042478b0de76635bda92ccafb97b8fb.nq.gz
    ├── 70143cc33d844920dde563b4130abdac7fe2c267.nq.gz
    ├── 70aa65a331fbe30a031a9bb871fd9c42b12ab8d4.nq.gz
    ├── 7146bc484ccca569b0736aadadb2cd431346b38c.nq.gz
    ├── 71e3e637178c7c5f5da85f591a1c66a45be3f160.nq.gz
    ├── 72615c2679fa21c512da28ef48c803646a91e818.nq.gz
    ├── 7364d71580dfce1141ab87c4346e0fe12bf312d1.nq.gz
    ├── 741df2610ed2f801b875305e767dc9bacdfc4572.nq.gz
    ├── 74e6119c0c42f8920021febcfbada7b98e3d5c0a.nq.gz
    ├── 761151fbb8743af15cf21f9d43be064488f4a12d.nq.gz
    ├── 767dcee36c525a4328b7941fd5ccf7b5f663053d.nq.gz
    ├── 77b1d8823ed0b355f09112a0900da4d00939f359.nq.gz
    ├── 77de5bde51f68fe953e50a1b9809f51e50bf4fa0.nq.gz
    ├── 77ffbab5a70cee066939fa59ced668822c2e3349.nq.gz
    ├── 797dc266504fc835635375b89384a496926ed6a0.nq.gz
    ├── 79a0537f3b4f52b04b29d46e89ce00f6da8fe579.nq.gz
    ├── 79e809657d251fed57b5a5b5d334a6e514065c71.nq.gz
    ├── 7a2f3b44c54ffb64128ffc7172b0034d955bcf79.nq.gz
    └── 7aafb1e589c4804f4dd755ffb3061f1635db0b71.nq.gz

8 directories, 200 files
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

## Source repository

[jsx-eslint/eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
