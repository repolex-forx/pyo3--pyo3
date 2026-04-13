# Repolex Knowledge Graph of pyo3/pyo3

RDF knowledge graph data for [pyo3/pyo3](https://github.com/pyo3/pyo3), parsed by [repolex](https://repolex.ai).

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
lexq download pyo3/pyo3
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 743af645e7143be6abe2217aafaa0540cf532af4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 743af645e7143be6abe2217aafaa0540cf532af4.nq.gz
│   └── repolex
│       └── 743af645e7143be6abe2217aafaa0540cf532af4
│           └── chunk-001.nq.gz
└── blob
    ├── 00215e95b7daacf3e2ca0569b828877914168c0b.nq.gz
    ├── 011f5e776d67f9a159840c1f9b45d1abd3552a64.nq.gz
    ├── 017584b877dee3e3a248c65afc91a7cc1a4249f3.nq.gz
    ├── 01bd186b7e9a963a0c9f9a80c1a7df24ae845247.nq.gz
    ├── 01ceea3bdbeb6f1cb67478e95818e56a79dc631d.nq.gz
    ├── 01d3cf0e0d7a29544b8dc98a78e0de77e3bf33f6.nq.gz
    ├── 028827bc08bb24cf6bd4ea97b1698b16a241ed78.nq.gz
    ├── 02b399c3779ac6047e32a8a9281655d078fe840a.nq.gz
    ├── 02e8a6ab3cb545a6e477a3515a7423ca46c33f39.nq.gz
    ├── 0315c63e56ab15cb92a9ba5aa82689fcb0661932.nq.gz
    ├── 0368bb1f43231b9cdf21fc56a2d46824a854c5e8.nq.gz
    ├── 042e5e4b7d2c267cbd82e9662a84074835b71b77.nq.gz
    ├── 04435dcb64af42256b986aac6b014c3e058849e1.nq.gz
    ├── 0475124bb4eac91e3ef794026f17b86315e8671e.nq.gz
    ├── 04a28d4826fc646bc5dd49e0dea9842cd8965301.nq.gz
    ├── 04fa83b740d069922eb36f2eb854a1e7f9123a35.nq.gz
    ├── 0505c2f0ad096993b743980b3f86cdbb2caf9b6a.nq.gz
    ├── 052fd9fd481742107ed6eb49354814c855d3cb00.nq.gz
    ├── 05400557d5a12dfba54a382da50b1626405a1337.nq.gz
    ├── 064df213ba64eaacf58b6619850c380af0fdf018.nq.gz
    ├── 069b07a31302aad476a499e37d98e91414ecce57.nq.gz
    ├── 06cad61734ea5d0a16bad330d9ad689ab5b70c07.nq.gz
    ├── 06e1b1b94879abedaf4a073c84c6e033dd92a275.nq.gz
    ├── 073137e293fad9776b95b1fe24b17c183d0c5345.nq.gz
    ├── 07ca6c5e80ab3e33f8183ab80a7e11c723d482d6.nq.gz
    ├── 08346c848943703c7af5477c0ce76c3304a34e2e.nq.gz
    ├── 08351d18daa544d6e9152d12df467af265424066.nq.gz
    ├── 0847ba48a8e1fa7d453e477ead7560ba0d7c253c.nq.gz
    ├── 08bdf5cba18f3301cbd19a4ef888a5aca79b5668.nq.gz
    ├── 090c964d665cdb4b9cb32173c69f8180ece2d9f7.nq.gz
    ├── 0958555c20b3b048d6630ff7437075563fa425aa.nq.gz
    ├── 0967a89764950595ab563a18a0dea58cdf90e696.nq.gz
    ├── 096bb02ae132eee75055760e4d6549f0872272df.nq.gz
    ├── 0abe6e58987561f079e2e37f4b00a839c6bc2c2c.nq.gz
    ├── 0aedb6cbfcc337333961a5d2d86ea0f31c97511d.nq.gz
    ├── 0af721de55b39aaebd5461c0cd364ccfd7f4f505.nq.gz
    ├── 0bb2d341a17f3a35f74879ad04c97e29f3767c82.nq.gz
    ├── 0bf9f53f8c397f12e30bcd37e4212b246e721e9d.nq.gz
    ├── 0c15ce6ccd0d58b38c10ad3b9a19a00885550d2f.nq.gz
    ├── 0c9fedba687dd49d205e759772d98dacf6d93c2b.nq.gz
    ├── 0caaf2a37fffd07ed705a5a875d5a1581389748c.nq.gz
    ├── 0cb4039b18638753b7f8778f6caeb1368b7f2898.nq.gz
    ├── 0cd8815e11da950886080b0ee81df57fb4cd8eee.nq.gz
    ├── 0d2d77eb1516240061e2d11c20388ef95f24e78e.nq.gz
    ├── 0e289910987f4e39d1b532866239cf86a43810c3.nq.gz
    ├── 0e2f707cdd472f69559168f0744701470ef6cbb3.nq.gz
    ├── 0f091cabd3248a851efc11ca82e5cb4c181a6fe7.nq.gz
    ├── 0f6820f054ea82d93dc1d944f1e88a75d82a0c51.nq.gz
    ├── 0fefba0bd5c6fd4fcee82b51fddcd76012221905.nq.gz
    ├── 1016baa720905bd2f94f0588afeeb5b912911b3a.nq.gz
    ├── 1021bb35128aa35071246f15d298f7467eef30aa.nq.gz
    ├── 108f088ea18069428ccca5580e4f52f408fb67b6.nq.gz
    ├── 117af8bf41959654ad0e5306683eb4bf4d73d315.nq.gz
    ├── 11e64a628e730072614445a3d161527a0b09989e.nq.gz
    ├── 1200de3df484a71d9806561ec6ca98ff295397b7.nq.gz
    ├── 12ed90e5d1c7edff29182e2ae2df8e9d1b37e882.nq.gz
    ├── 1334bcabde4c1126780a052697ae326da2922c72.nq.gz
    ├── 1364185bcdd803d3df113ac94153ce27842a59bd.nq.gz
    ├── 156ecd309f6e1cbdd76fe2033f5bcbd738a0ebeb.nq.gz
    ├── 15e3d09d45508d3bad7a0130b9eedcabcd8837bc.nq.gz
    ├── 15ec8953bc63607baf88394201dcc498b3c2cc78.nq.gz
    ├── 16465f2cb5fe0972f68b6951d3028cc70d94e39f.nq.gz
    ├── 1648e067760e46782d3af19dc16f6d9ea1c00202.nq.gz
    ├── 167013f5c420990695a03dc94dfb5ab84bb9897b.nq.gz
    ├── 17242afca08cf45f88050858e704cb4f2be6d9cf.nq.gz
    ├── 1849d9a38feaae302784ca824feb1259e4e0759e.nq.gz
    ├── 18a764ab4eb69115a732b18497a7b863fe679464.nq.gz
    ├── 18bbc8bece06094f3128742858310ebc8f3bd944.nq.gz
    ├── 190ffe26c1299ba329018b03b93885a4646c0f0f.nq.gz
    ├── 19758ce39467680606167e06b26a962b4d2641db.nq.gz
    ├── 19dc0773a8035c9d8933d7cec822b80cb71ff9e4.nq.gz
    ├── 19f914069ca263bc8e8141dda8d6272045fe5f7b.nq.gz
    ├── 1a49eab164111fdd959ba59c139cf8ff4ffb7f20.nq.gz
    ├── 1a764f621f0361f647951362fef8c1c9b0fb864f.nq.gz
    ├── 1a7884251130a860bee60dec0a3776a64c0e7c94.nq.gz
    ├── 1b1e702944dc13fcfc4ad11ce359015160fec670.nq.gz
    ├── 1bd34081bce775ab669575355a66c5ab339cd5d4.nq.gz
    ├── 1c033083e0cb0e9da3de1f2d29698befe5ffcd54.nq.gz
    ├── 1c3c768e3427db024ae8ba5f6881de730da1242b.nq.gz
    ├── 1c50c7a759ff7f6ac16b60a75636ba6da8c8260a.nq.gz
    ├── 1c5edbafd31e14ae47b5052a4db7b048bb7cf9c3.nq.gz
    ├── 1cec27674479330e31eef2f5a937a06e100437e6.nq.gz
    ├── 1d5cca9a33d799a23e1975d880b6e20a0d9143fb.nq.gz
    ├── 1e763279d81238bd22fbb53073918b7098b5bd30.nq.gz
    ├── 1e7a6f4406575828d8d7a43fc22a08aa78aa55dd.nq.gz
    ├── 1ebe31b19e614536123c532bc17738cd5c1116db.nq.gz
    ├── 1ec88501bb2933ed5d3f4846450fc63967fd4b95.nq.gz
    ├── 1ee76c48114a1a435312568a67cbf903a191b1b4.nq.gz
    ├── 1f154c9ceb1045d7e61e3db08befb21986a307eb.nq.gz
    ├── 1f21fcd6718404ac6173b8fc431101ce4b3ffd54.nq.gz
    ├── 1f3e8d9f7f412f2c39ad97798cf3553aa5580e98.nq.gz
    ├── 20a5eca07bfa5bc83c6836a62d34feb2b3d6a345.nq.gz
    ├── 20d5a24387bc093ddbe65413bffb105a89ecf03f.nq.gz
    ├── 20f682fa04288e308b4be8aa18e62102c9a17ac3.nq.gz
    ├── 2156c1d7322cf1b66842b5051704d0d0a7e300bd.nq.gz
    ├── 215bc0640cd3b678ba6f0e6fd5c76fcb3f7df836.nq.gz
    ├── 2161c2f893500dd868157d7c9d1ddd3d67da369e.nq.gz
    ├── 21c667242de65447cfef99cf2af0dcdb8a54ca74.nq.gz
    ├── 22aac933e854f23dbc8456810d079a70d89474b4.nq.gz
    ├── 235831ac486acfb938562f90bafe6eb0b7559f68.nq.gz
    ├── 23d967cc6955dc7602e962f3f1a3dff4676d18c6.nq.gz
    ├── 245d58de593c73b793f9f95418c692ef26fd9d4a.nq.gz
    ├── 24604e87f25f315070230dace513be7ba2c74849.nq.gz
    ├── 25e3f54e331982d20938bf19bb8f1d33ed4429c2.nq.gz
    ├── 260916d2b195d09e70d4b9f434b7910001712bb3.nq.gz
    ├── 267751f4c480751368d80df6c06bcefb186a06e9.nq.gz
    ├── 276eaafc6007ee92a7f41a2d808cd7266978ec59.nq.gz
    ├── 278be0da12ab95954bae4019e5b954acd2ebab9e.nq.gz
    ├── 27c2fcdda502ff567e32507adfdab8fa37ce1e2b.nq.gz
    ├── 27d884adf2c6986449397984e990ce77570717b7.nq.gz
    ├── 28cef7975c9b0e00c8e581ce60bbc879e6790df1.nq.gz
    ├── 2a70079f82d20612a4791ca5bb98e8c138074b63.nq.gz
    ├── 2a7289205651c9733c53bc23639268826c24773a.nq.gz
    ├── 2b2acb9e0b6c9991ddd43a9a43ff70ad185d4ed6.nq.gz
    ├── 2b5554182f10c275cf2655cd61ea19a6a236c865.nq.gz
    ├── 2b9a7f784e0a668b00cf0cceb83a0be9be7c83cd.nq.gz
    ├── 2bc7dd5f0b004f961cc89e9601ec8e882a225c53.nq.gz
    ├── 2bc9c0366d19a0ea1153aa8e2648179d04c19bc0.nq.gz
    ├── 2c7375fd2f94c070d0846b13cefd7870d5f78b35.nq.gz
    ├── 2c889be418996530dc967d3bb3b13d4cb79084fd.nq.gz
    ├── 2ce6ff955a3239632be8e6bc68d315058c8d2af4.nq.gz
    ├── 2d3e39dadeae56543be5ef350a99f39b6c0ac3cf.nq.gz
    ├── 2d4daa194c65b7238a3c1ea6bce4ab96ae624200.nq.gz
    ├── 2d9dd5a4a1fe2526ba56c9d4d00ad37a06828644.nq.gz
    ├── 2dd052656393f550b49a8786dc88455320e37e25.nq.gz
    ├── 2e408eb7b34d1ca04647a8c6ddfa653ff296b92d.nq.gz
    ├── 2e4214288893e82e9e7cf862dd41d74b703cc1c2.nq.gz
    ├── 2e5f3fef5079672c77bf40c35e70eaf68613e2a9.nq.gz
    ├── 2e9d48bbc27558ec0dc94a799a4b3c687a7b6bf1.nq.gz
    ├── 2eeba6fa7b8024d766e666e4e7a31a8cc3161e91.nq.gz
    ├── 2f08ff421b958d6eae1f6a24cb0be7b0577ebadb.nq.gz
    ├── 2f0d17102c2219744ba7d85ac50114491a540633.nq.gz
    ├── 2f58ebf0755b635d98999fc2784795c451c85884.nq.gz
    ├── 2f638eda2e987470b39efa9d287a6fb72b3cc81e.nq.gz
    ├── 300efbe359bfe264b55c4dd51ca9197859088b6f.nq.gz
    ├── 3011e327914e2a12ee7ffc4f899d0203ad3b9f92.nq.gz
    ├── 309809ad9cb3406c491e567dff7b8d8f78023419.nq.gz
    ├── 309b67a633d95601d965bfed3903e1d8594bc40a.nq.gz
    ├── 31038b398320c4f4900d9bf2d3e0b78b6e2a533d.nq.gz
    ├── 31081e0185c813ea9e9dcfaa7a899bd1f3c21fb4.nq.gz
    ├── 321bb90a929c0cd17ba3efa6d466f2a2aa091ec2.nq.gz
    ├── 3235670811ccd9ef58196fb5d1758f04e5ce2559.nq.gz
    ├── 3283fc4e52f1f3632b60bb9183a3892a2bafa325.nq.gz
    ├── 32b74997bcb608d22bd87d3f9d775328678b6e94.nq.gz
    ├── 32ccec556040eea86b2f2544896d0425717b4842.nq.gz
    ├── 3313600ef4f93f96166894b52d33dcf975c8edd8.nq.gz
    ├── 343a67f5641bc4cee0da643bcee62ddb4cb0bd43.nq.gz
    ├── 356326e65d327177624b54f219b472cdb3a2e2c5.nq.gz
    ├── 35667fed8c23a596c4af7a5ba81649e2cbf41be3.nq.gz
    ├── 356facdc3ffe74ada64596406587629cc639b8fe.nq.gz
    ├── 358c88cf531cc976ea3f390107308d8380e1d1aa.nq.gz
    ├── 35fc784666b4c1c37084b4724fe387f70f971fa6.nq.gz
    ├── 364f43ca4f80f47106ad1efce0c6dc15851c73c5.nq.gz
    ├── 36de7bdee78f2a2e5a436488d0359e79cfc9b6ba.nq.gz
    ├── 36e45aadd2c2fabea0dc407c5fcdfb00ee72bfac.nq.gz
    ├── 3704a65b44715a2c666c56edd18c2545b92a65c5.nq.gz
    ├── 372490ca580d0ea74836d370cbe08c6e7b1e0563.nq.gz
    ├── 37991ee4ebe487defc42a59a96d6350afaddc5db.nq.gz
    ├── 38945cd869b9254d560fd6a668e90381b46f410b.nq.gz
    ├── 3921310cee8f3a14d45002370d6e62e908bbc841.nq.gz
    ├── 3a066353ca4ae04a0361708906912112b0a1591a.nq.gz
    ├── 3a2f693539537308f17f531e2776d1bff69c59e8.nq.gz
    ├── 3b525d399df0f174f4b10b5939878d35b5c803b1.nq.gz
    ├── 3b72764301cde148224e30b376e17490a35f2228.nq.gz
    ├── 3b874e51bca6cf2f902b725db1951f273e1fbc61.nq.gz
    ├── 3be303fb38a6ca750181c88dbd472faa21ad734c.nq.gz
    ├── 3c574320cb5c02b125b0516566075321fb9fd3f5.nq.gz
    ├── 3c5ac47fb84d2d2dbb9c0561df3361608218e603.nq.gz
    ├── 3c7cc30139918225b57bf890c69174f76a05d4f6.nq.gz
    ├── 3cd4410f6e9e235cf96d9b7ace70d11160945b8d.nq.gz
    ├── 3d76b5ebc11fc469879f6c09b50a9bc82efadd13.nq.gz
    ├── 3d980368fc01c942cb667773c24878489047d4cb.nq.gz
    ├── 3e887475d21a9aba1781409bb589594b773f8ccc.nq.gz
    ├── 3e9e4544467e299e9896add78b8e99119994ecab.nq.gz
    ├── 3efc9615c1e3a6a688c70c0690cdd39bb0768934.nq.gz
    ├── 3f0a5053c17a498cc9d6057eeb987f0b10e257c0.nq.gz
    ├── 3f0d23fa97caeec4930b7f176d0ea85815372f72.nq.gz
    ├── 40b848cf7e0c48ece705a8e3a415b4c74dc9e56b.nq.gz
    ├── 40f1e1cc01da952a93bb9a24ebea525b5a1b8586.nq.gz
    ├── 414f96a829009d636c301489b78822a259df5220.nq.gz
    ├── 423f0dd5cea7bb28e8c7144b56e3f3889025b3d7.nq.gz
    ├── 42d8934641c5d58a0608d05ef55d8b3d6cf9d177.nq.gz
    ├── 42ec20f52f0c9596a537d644784d795c8eaec0ca.nq.gz
    ├── 443266611a0634083364a01428572b79dd071db5.nq.gz
    ├── 4433178e3becf6c28a0d60317286f14bd478f7d0.nq.gz
    ├── 4464e1addc9912f60aab2e565615add118322d52.nq.gz
    ├── 44ae47bdc306ba57226d1c787985add5fb497d0d.nq.gz
    ├── 44cfd089fabcd57ef58f68e4d79361c022a61783.nq.gz
    ├── 45696c747a137fb0cc8a8d15fee48312af03aff8.nq.gz
    ├── 46d2dbeedef2231a2038e7ec0d83b1d85e3df7ed.nq.gz
    ├── 477424206c9f046af45d2dca6466f853756034c7.nq.gz
    ├── 477ea99f61833abec67380425e764747cfbd0733.nq.gz
    ├── 47e86d914c5262b1a0aee8d45239fe75a9511c81.nq.gz
    ├── 4843c67fd9c69b97c942d72dab7e271c76f271a5.nq.gz
    ├── 484c4ce44f4f7a841204aa12eff5bfbb101f8306.nq.gz
    ├── 486694bc51dd5b848ce9edf9cea9e405d7ca0aa5.nq.gz
    └── 487173f9afb63794b073a3fab71fa6ae9c335f92.nq.gz

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

[pyo3/pyo3](https://github.com/pyo3/pyo3)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
