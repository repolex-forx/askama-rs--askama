# Repolex Knowledge Graph of askama-rs/askama

RDF knowledge graph data for [askama-rs/askama](https://github.com/askama-rs/askama), parsed by [repolex](https://repolex.ai).

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
rlex download askama-rs/askama
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9ae4d5bdf4352b35e34106e38944c90d7a7ede3e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 9ae4d5bdf4352b35e34106e38944c90d7a7ede3e.nq.gz
│   └── repolex
│       └── 9ae4d5bdf4352b35e34106e38944c90d7a7ede3e
│           └── chunk-001.nq.gz
└── blob
    ├── 005d6be204ec5c77d61cbd451855b2f451f03b14.nq.gz
    ├── 0089a99c7bcb5be4017fa71e244d80fbe67421ed.nq.gz
    ├── 019d574a9bc1ef4775addd3e04c1147935cfd97e.nq.gz
    ├── 01e207a79445c2ac6fd11cb72490aa4c9f8be98e.nq.gz
    ├── 027a565c07cdeb8ad42fa04191f77ed54040a0a0.nq.gz
    ├── 029f34fcb138d73abe88bc987173a044925a258f.nq.gz
    ├── 02dc30070cc2cd8e0960c4103cde8cbc2c7876e8.nq.gz
    ├── 03100422dae3913ead565a816870b5dbcea1cce7.nq.gz
    ├── 0328100d4dd9f17889fd76a8a36fd08ec3ced406.nq.gz
    ├── 04b624decc091940bd9deab8d17e0e8cfde1b4bc.nq.gz
    ├── 050aca072f01e80bf56fe1f860751f6ca1325c7d.nq.gz
    ├── 053191ccfcd044cb12ce978366e3837baf1c7532.nq.gz
    ├── 05d8325d34d6c2d2d9ad19cb54b6875bdef52470.nq.gz
    ├── 06477bfa534e4d3265e84a6411e193235ea0fb15.nq.gz
    ├── 07da572d51307f81d90d35d536daf01d74c20f3e.nq.gz
    ├── 0848dbf16f9bd53da3c5f6158fbbd2da950b7457.nq.gz
    ├── 08df1e511e0b8a825dcd784a5438b0c374ed229f.nq.gz
    ├── 08f7912dc3ad3d6c46455d2fc94b0cfd10c4c500.nq.gz
    ├── 093aef3a803c7eaf3c1d9ebfae1a878a114f9a53.nq.gz
    ├── 09720c0853a7a553dd2c17640d8b31347c194f6c.nq.gz
    ├── 09aeb2527b1654dc6dc53d8f4f7a2b4dafaebee0.nq.gz
    ├── 0a23e1c633d188746139a4e329640e96193af248.nq.gz
    ├── 0ca60674948063b78361e7d27484050bba7b32d1.nq.gz
    ├── 0dde9fee449b4d9f293a9e0e4b83fcb660ddd06d.nq.gz
    ├── 0e5caa3a69a050755ab2cef5de0a62fc4c1d1f9b.nq.gz
    ├── 0e927f6b39570cb754ec6a742ed7b6ebf89e86d0.nq.gz
    ├── 0ef11baf8cbc8bb98e00c6c43a85810c8afdb58c.nq.gz
    ├── 0f9be2348bac0495da49fb72b24eb384d66aa20f.nq.gz
    ├── 0fdde7adc5687de6b40ee218f127f1253ad55288.nq.gz
    ├── 102370468101047884ca859c22db37749cba7237.nq.gz
    ├── 1094814b27b87db7ba786e13a18aa651f589e8c9.nq.gz
    ├── 10a92dd18960ff555eea49a52e8295b0f02ce694.nq.gz
    ├── 10ea31f57c4eae856a56a3b55b5df39d3a898b7e.nq.gz
    ├── 1116676996a3cd7f70ec8e3dbb7e1c28e6fc410f.nq.gz
    ├── 1118bb1dc3d6bbe79197703f10f0e4175aaeffe9.nq.gz
    ├── 112b464815116d0bbd61049d24f7ef757cc3b370.nq.gz
    ├── 124cdf8f419baee4ef530f2ea9e2b3ad5c8c5885.nq.gz
    ├── 12a03691d37fc2587e737e6c86cdee63da1ba2bd.nq.gz
    ├── 12d7d456a320b11da95235c7064e806d89cc196a.nq.gz
    ├── 135a39a3c62aad4cc33a12b3bdebe059e1c352c5.nq.gz
    ├── 13d544407da760dac35b974938d6c384a0826921.nq.gz
    ├── 1416c1c3f1bc3edbe001a018d9baff43eb5bbfce.nq.gz
    ├── 142ac0dc733e733a1d4111869dac39b73557368e.nq.gz
    ├── 143670dea2fef68949d66d7d61e544becc9e9486.nq.gz
    ├── 1444b55bef71053ec8e045a9e2e2d1c74985270d.nq.gz
    ├── 14db9ca120974d5a017bb3a42e2ff8edc54e8757.nq.gz
    ├── 15e4306a8333ccbed3a60341e71417f4b7dc5bc5.nq.gz
    ├── 15f364076de84d7769dce67dcfeb84d7612f51f8.nq.gz
    ├── 15f68168aac990cc15b9e839bc31e59a798a59f9.nq.gz
    ├── 163b0571ee1d9b3b13bc35027128e81dce5527bd.nq.gz
    ├── 170e74bb715c894375d81945e8450ea31c825b11.nq.gz
    ├── 1793770f0c9e77c31f8f82affd590599d452f31a.nq.gz
    ├── 182ec2b6409626e2e3e2e3e419e2898cb6e5cb7c.nq.gz
    ├── 18373a7f63fb2f91731eb69ae73449a946286672.nq.gz
    ├── 199faf97ca578e65d29f75d0e1065928d5ea76c1.nq.gz
    ├── 1b312192b721001e0ad4567931e6f279e9fdcb52.nq.gz
    ├── 1be9c9200b489b42b726b7a21f292accb442dee2.nq.gz
    ├── 1c1c464af5693d3ee7e2d7c946dd417f31f992ca.nq.gz
    ├── 1c3687d6ab54710f4af516923f83ac9d652b1b8b.nq.gz
    ├── 1c41dcee324e44f9583b9650c778dd57ae7c4408.nq.gz
    ├── 1cd601d0a3affae83854be02a0afdec3b7a9ec4d.nq.gz
    ├── 1ddbd8255ff0252e40b76ec0a9941049e468a658.nq.gz
    ├── 1ec1e878ccbf9753d8244cb969536f32574a44e0.nq.gz
    ├── 1ede5296393aa466917e4f5a0d0b3aff601b4797.nq.gz
    ├── 1fa1f29aa6e194332cb4753a919833b2eb141a5f.nq.gz
    ├── 20d7d56f08a023a09540dea9ca69d4422f5bad46.nq.gz
    ├── 21405294137ca0462d801ecb764366a67331ad1a.nq.gz
    ├── 2159d50f9fbd25d1b08a1ae92ab02e2794d44205.nq.gz
    ├── 21763cc6c1e9c976382f06e88bb8d5d44d743382.nq.gz
    ├── 2264b5db8271b9eaf294839ba23bd77f56c46931.nq.gz
    ├── 2272d82d1d60a7b41b136b085f795862bcf3c4d8.nq.gz
    ├── 22d9b57effec56512c54a9d2c018591684b20c07.nq.gz
    ├── 23756ecc0b0e89d7c1ff02d5ae5d8c71117ad207.nq.gz
    ├── 2379a315e3c4a279e869877b5cdc340f1ca55909.nq.gz
    ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
    ├── 25c32f9f7c20c37cff91a046c2df8b91182db4a8.nq.gz
    ├── 25d83b56e0dc04ea0c1eed509d89584e1f92d591.nq.gz
    ├── 26ad488d27482961de56d25e8b2c58e99b854665.nq.gz
    ├── 26e5c9f2be071bb2425796d870a7791a34bdee53.nq.gz
    ├── 291c0eaf739b204ec297a068b52d326ad2d5439a.nq.gz
    ├── 29253153d4cb4c93edf82cbf041697ba1b3a05a9.nq.gz
    ├── 29675307ffbafb272b21757fe211c00c90ec3ce0.nq.gz
    ├── 2992f0c5a61bbb20a2b68578a85cb837555484c3.nq.gz
    ├── 29a47a2586d75ed70ae869c868b7bf38caf07161.nq.gz
    ├── 29d411791f19ec6d39ace768a043f15c4b669a26.nq.gz
    ├── 29ed0b8df5666eec3df87feb84b6958ca9b04856.nq.gz
    ├── 2a0bc6c629192561349a4f4d24648e827d395242.nq.gz
    ├── 2a4ea6e36a30d3c9d56878f21f00d90f3a75a6cb.nq.gz
    ├── 2a7ecf0d20990fe8b262a2ee8c39bdd972c48722.nq.gz
    ├── 2aade0e8077ba23ca7946b4242b6577ad24f3ab9.nq.gz
    ├── 2beb90dd6fe39649ab586fe4100c8ebc8e4b5af9.nq.gz
    ├── 2d6c6b2bd8fabf1b7ffad1fd072bd6953a1af654.nq.gz
    ├── 2d81bc43f4bcd148bca9d94dbe96f87dd903cd83.nq.gz
    ├── 2de69b95750bc51cb20f2aa4cc33111f98365a23.nq.gz
    ├── 2ea01cabba0f3c0a63cd972b56869e31a8620d47.nq.gz
    ├── 2fdf2f93d76c72554b7438ec8083b3926efccf9a.nq.gz
    ├── 30afe09b37a4b08c87b6b12396f8b12c5498d3a3.nq.gz
    ├── 311147ee26c4bcb03dc98529023e5c036f7ef0d8.nq.gz
    ├── 3148657f32992f805eea309545c3b99990e6e02c.nq.gz
    ├── 31fcb37234321a9573f6e423ac7de237ca407e29.nq.gz
    ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
    ├── 3327701d2e5efe89a3c93a7b7018f7a6425684e6.nq.gz
    ├── 335c7a62149b8552e0c16c7a24cf929eff438e2f.nq.gz
    ├── 335e328c714e46051719b2d87f938d223353cec2.nq.gz
    ├── 3388ef2853ca7a2c6ac7d3a1233e6dfb7b87ae0f.nq.gz
    ├── 33bb0c824f867d45634672b7b7588e481568496d.nq.gz
    ├── 348cb29121a21d54aa5be5edc292c283b5fd03f5.nq.gz
    ├── 3526774ba05e02a0a378e23f9258691b0d460b0d.nq.gz
    ├── 3555f1be37fc72ca1992e69bf369b832e3afd988.nq.gz
    ├── 369cbfd76249ae550d774569a9a673d03228c3c9.nq.gz
    ├── 3718d0afc2338bd3db2e7652a2edc5f0c9704549.nq.gz
    ├── 37b9294a95f7d04d9c9e42f2387af1903637efde.nq.gz
    ├── 38f65091146131beac0f7141774a39f68de0454e.nq.gz
    ├── 394aec41941b39563304c309fd09f199ef2e5e74.nq.gz
    ├── 39def8a457d39fddb62506e88561480fde35c78e.nq.gz
    ├── 3a0ad98458c8d38aaa0323a794e96edf354387b2.nq.gz
    ├── 3ae992aeeca5770563089109836eb01a42bfe875.nq.gz
    ├── 3b13904e90490ec46b5076992bae9fc7ec6e263c.nq.gz
    ├── 3b2ada5501f2b24f17b920f1a23347bac39721df.nq.gz
    ├── 3b40a4759b0fddbb59a98faa49313eeb44baa0a6.nq.gz
    ├── 3b4702055eb38687b9a2abaccfa3841a15107f19.nq.gz
    ├── 3b571591ba1c2f7cd2f188c9471efe8915fb8912.nq.gz
    ├── 3bdfdb0e9d88085e55e7b9f10e65ce3efb2c994c.nq.gz
    ├── 3bf825423c67d6ed5f930c213f7383cfde3239d1.nq.gz
    ├── 3c8b485041f22dc5d6dd5afa1ced603a0f82e635.nq.gz
    ├── 3d20ef30c7723088aafe5b2ae26e8230f60b86df.nq.gz
    ├── 3d3670959ac27b6c74c5944fa9ad6622195f2c29.nq.gz
    ├── 3d62d959ab2e6d87fc7c7f43a22e3b8f4ee98de1.nq.gz
    ├── 3e64ced573e9bd225d8d552a9477cefca140fe34.nq.gz
    ├── 3e776e5506fd6bd2f0688d523ec2c1994be94c57.nq.gz
    ├── 3eb061835e95a987bc83c565094a1be4d07730d3.nq.gz
    ├── 3ee375a8081264d3a4a0088385dcec246fac41d5.nq.gz
    ├── 3f444a6a9d7dd80a4b714c5016b63b8a45eae15b.nq.gz
    ├── 3f6174b01ac3a029b200f7a1bb3e4fe29034289d.nq.gz
    ├── 3f96be1225501919605a82620219656e443200ab.nq.gz
    ├── 41b13b3227c7a3858413ae283faea6148dbfc4f5.nq.gz
    ├── 42f43111ac88ddd1b0b819c19dc7d9ea29637d14.nq.gz
    ├── 42f559fbce5dc9fa11efad328dad5085141afc95.nq.gz
    ├── 434ca7ac169be9a5896bae11ae2e378b84fabacc.nq.gz
    ├── 43e3af66308226ac6a6526c418d9d3e09d6770d4.nq.gz
    ├── 4410a13f37fc0e4e5a657fd0c662b54174e376b0.nq.gz
    ├── 451b081039d54e055a5e1359a86838b6434f9a18.nq.gz
    ├── 4644cc9dc90a74039a4ae5bc61cd0805bf820ce1.nq.gz
    ├── 475cfeb75f084d7769a98d8fbc61768515c58986.nq.gz
    ├── 483958bde66d9936bd83aac5f9e92c72519d83e0.nq.gz
    ├── 49856c711c2083969e20cad75323d13f64ecb7c6.nq.gz
    ├── 4a41b1636c0df3bbb4616840f20d19d73db6a7ec.nq.gz
    ├── 4aaec07a0db3a8736ecdb918c1f48c8e40dd89ef.nq.gz
    ├── 4bafc1120b0340bbcef93b77b388f907ceb0f75e.nq.gz
    ├── 4bb9d6a08b404421632fa1d9951a6982530a6452.nq.gz
    ├── 4bea04c6b763ca7d811d04898b5601e87b1e8561.nq.gz
    ├── 4c3794e01f24677f2286f1ddfc078610e45456e3.nq.gz
    ├── 4c637b8f38c36d764aab6c6f6bc6346710d0ae85.nq.gz
    ├── 4cbb0257e989cdaed0df3f9542776119243a7527.nq.gz
    ├── 4d43188d30781c7919bfb3d96a0bceb055306e39.nq.gz
    ├── 4d52062091eec70e7217eb3cb24e6706984149dd.nq.gz
    ├── 4e0e8a7d654b23e194bda7d875db42bdcabde6ed.nq.gz
    ├── 4ed3bd89a321509ae5e4c49f77f9741176f840c7.nq.gz
    ├── 4f30e70345f5aa2529daf84954c5f239b87c7c23.nq.gz
    ├── 4f915a9ad2937a2cf6917879be44a547d8b277a3.nq.gz
    ├── 504ad47f4db365825c4c2677a32a34bdf36aea80.nq.gz
    ├── 5128bc0b3cd6190aa206e3e0c24ef17e685805db.nq.gz
    ├── 525e1a58f3c2c8b2a5f32f1bc4c0cc1601ec9aff.nq.gz
    ├── 528441e38bbcdab53c06d6a03b3d8370475822fa.nq.gz
    ├── 530b53f79a2021c8da446eef488104cfea076600.nq.gz
    ├── 53610ebf4ad9df845d0ffc603162afae6ac77a2c.nq.gz
    ├── 556edfd81a5c9744e67e37949585d379275bab9b.nq.gz
    ├── 5630c5bb167c3676fe44ba4c55c762b0ca12edbc.nq.gz
    ├── 5675bc89c78fe1d519496859218f98688aea903f.nq.gz
    ├── 577f95a35fe8b1297ae7d720bc5a04b9491ebca2.nq.gz
    ├── 5842a150e92cb533e2f8f8158e62d98fd690a351.nq.gz
    ├── 585682a6b793c13c841a2307a342046bc4e138cf.nq.gz
    ├── 59d7a07f3652c3f322594f7f5eeef6989599ddf5.nq.gz
    ├── 5a20066a04956231b43bbe1d4975a9d6a37ff745.nq.gz
    ├── 5c7134485059900c2020a98e67c41f4ac1c3b681.nq.gz
    ├── 5ca1956cfce7b813bdc9d38ba13c714e660a2443.nq.gz
    ├── 5cbfcad1baaaa641c8694d102cfec119c81419e8.nq.gz
    ├── 5d0967727a0fb3ba0bc0e6bb37ab8b0e97a1ade7.nq.gz
    ├── 5d27ec0827a1ed461bc77b95e1cad399f93482f9.nq.gz
    ├── 5d68d257d4149bdf68bd4d3b32649358a13bc4ff.nq.gz
    ├── 5d893c1fec3416e7b449139a4828b58f9ac46acf.nq.gz
    ├── 5d8a625fe48cfcc87fcc5628a2d39a951803819f.nq.gz
    ├── 5e13997624558cfe6911f8cb113440dc7edd7f63.nq.gz
    ├── 5fb8a05b06069c365766c1f602bb573e1b4a9f08.nq.gz
    ├── 6060d116aa755734c17205f52788cf3ea5eab15b.nq.gz
    ├── 60acb5355c2364d3ad24915acec3f1a4c8a481f3.nq.gz
    ├── 61a1fa4fa7373183121b5bef3ae4c5b0d9571302.nq.gz
    ├── 623e6bae0c06735f709ff6b9dedd9ee3c497d284.nq.gz
    ├── 650731aabfb6181d7dba0005c500ff3be50885ad.nq.gz
    ├── 6643270496ddfe8b13861c16c8b89223153f387b.nq.gz
    ├── 6646425cf41e1e737744e815bb2be3ec9221459d.nq.gz
    ├── 666c7a11ed8bcd42355b208f52961d678954ecac.nq.gz
    ├── 66ddadf30faad3105b85ebe8bd0ed6f00c895f7e.nq.gz
    ├── 67d210c98ec1dbe0126b68d3c7006fe1023c9aac.nq.gz
    ├── 6889a25583abba2639361e17798d07e5f993f497.nq.gz
    ├── 6a10323f3b3420042f446560fd7cdb3562b30c90.nq.gz
    └── 6a472be82f888d259061f4064fbd068f440c4c87.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[askama-rs/askama](https://github.com/askama-rs/askama)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
