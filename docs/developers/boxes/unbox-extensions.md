
unbox-extensions
====================







## Dependencies
### Boxes
* [`seed-extensions`](seed-extensions.md)
* [`seed-models`](seed-models.md)
### npm packages
* [`unzip`](http://npmjs.com/package/unzip)


## Install
```bash
zeus unbox unbox-extensions
```
## Examples
### Unbox
```bash
zeus unbox helloworld
```

## Zeus Command Extensions
* ```zeus list-boxes  --help```
* ```zeus unbox  --help```
### Subcommands
* ```zeus deploy box --help```




### Model Instances
#### [repos/00-mapping.json](https://github.com/liquidapps-io/zeus-sdk/tree/master/boxes/groups/repos/unbox-extensions/models/boxmaps/00-mapping.json)
```json
{
  "contract-migrations-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/a84906bf331f4fc7585e1fde48f4bb6b880d4d28400d9e87ab87519bfd9ff438.zip",
  "core-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/7644e6e97e18c2612ca9634b538c6f4cd92ceb88727a6bd175f50cf74e5bb1e3.zip",
  "upgrade-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/73dc5c7cf9d185680ce6f6eba11cefb9f0489622896bb39218398ad7ead7027d.zip",
  "airdrop": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/2314542e81daaf4bb7e6fc1abf1f7cdf402c60373bf2f5dda84d75f5b2e51dc6.zip",
  "events": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/eb51460633179b1fab95757e63344fceab3587bad92fa4899f8c27034674d23d.zip",
  "seed-migrations": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/64093169484e440e91c53183c1dccbba84a074ee3fa318208b6e25b358454c01.zip",
  "frontend-transit": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/10df0b3bda80dc70248e1b29f79f2a97be07c80f93236b50feed2409c7499e37.zip",
  "seed-models": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/153a827af4b9e849df4c424793894817f274d6924e09970353b09d218ca6cad4.zip",
  "regression-tests": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/b401a60c9fc4a986098a6d2f2592cc45b088ea47ca9eec9c7c2ffd9c30dd612e.zip",
  "bancor-network": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/9874ff159fb7c4ec2c0726e40a3fdc6f1ed8518e0cfae1d4bd63105516a001fa.zip",
  "vaccounts-dapp-service": "ipfs://QmRD9b1QTwpPLNyW6G9sFw1R69YPbH19rg8XQShb6TH4qc",
  "airhodl": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/d77f3eaedc252a5194bca9a62068ce22cef86662b4d63000bbb6219b1448929a.zip",
  "update-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/f97c066965f6dd3becd64c8127b0396cdd62bd8b0c36de8d3023ca32e2db3e7e.zip",
  "eos-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/e4deda818d3184a62387568ed4b363b2b08a5b1e0e998a457d9fced256675529.zip",
  "framework-tests": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/4fc619afd93353007e1be064c1fcefe594d66bd19aed5fedcb1994efec90666f.zip",
  "seed": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/6b769409e2781e81286b0c88cb58079bce8e6cd2946a775b15184b60b75ec7c2.zip",
  "secure-accounts-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/7844b0d79779c11233b9ace5efc582583c7b8df3074c1b3a491a8c6e70efe98b.zip",
  "templates-emptycontract-eos-cpp": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/20477a936fbf8b0fd6e76c89f009109404434df1e053b2439314de8039a3cd00.zip",
  "ide": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/0c6fa309af78bc6877937dc86245b4b6b55769c5fd1a14cb2bc695836c2f6b5f.zip",
  "seed-microservices": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/126f068aef259348a67d22490861f39a1887cd46ea09bb1a43ea1386b4e73525.zip",
  "frontend-vue": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/f82057825526dfa189c52b698002c75c492a965bea3b695cb1a16236b845b7e3.zip",
  "sync-builtin-boxes-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/f504233edd3dab868a7e3f2cb478372d9de197be05c26f41caaf3a721d8e8d5f.zip",
  "dapp-cluster-k8s": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/db50ee4d893332237c8f835efb65517640d400a6e0707163c49245f2ada4825f.zip",
  "oracle-dapp-service": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/b169cd59c19dccb6401b2779e6aa71109f94089bf6fe80a0f5c9b675fc269696.zip",
  "eoscraft": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/a40dc8f9bcfe99b1d1fa08f35ee9ec6e2b83a64940fd118bd446c261952e2f6f.zip",
  "vgrab": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/29a528041114a88989e760262f13d419d1a19889c60c836c6f75a3fbd4ccd5b6.zip",
  "ipfs-dapp-service": "ipfs://QmagcTM59ixNtE1k56Siurw6QztvoK2etht2epkSfnhVax",
  "eos-detective-reports": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/c6d5f00f50bfc0828f1e6d29005a1d8c0cf7ee69d6d06b6d49f4b09ffd33dd93.zip",
  "frontend-phaser": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/410dbfff30f4a4707790d30c50997c0960e3aaaecfd64164da551cebb3541e24.zip",
  "dgoods": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/a324b90e4a0ace0958f7815b66a7fdb8e2e69c92b02bd4b64d451d9b95decbce.zip",
  "storage-dapp-service": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/ea495a08f8ec3b9d07417c87a8c3e8daf63ac2e90f2497955aa35f338c2b52e2.zip",
  "localenv-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/bfaccfa5004927e85057bb1c8276eeb0131279e9cc962e6eb71fd880d7f8893b.zip",
  "run-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/53895ed9329ed52db67ca76660fb315a5f84e3b7ce6485cb8bda0c43c4abf47a.zip",
  "ipfs-daemon": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/ca1ce6d0cd915ce957c4ff2a1d5aa565ab494855d9194046285e84d0baf6a6d6.zip",
  "bancor-formulas": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/773390a4a66d869b6aaf4dcc911eff9cc8aa845778206914bfe2ff8ad2264511.zip",
  "dapp-services": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/8cf8ace8a241b327af59f2c8a38762c83e37521995bc9dd91e6aa83f58bfd72d.zip",
  "dapp": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/7aa3ed3db3a047bcea0438be0232ed9e34684f6427ae5391288f442a9854416f.zip",
  "publish-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/3231ae0fd8947d9a9a4aad7106ca436b056be044ac54410f4b4e8371ce78bc19.zip",
  "test-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/5450db8266162bbc5114b06405e89f94f00c64ca84b795201bfe545af849affb.zip",
  "eos-common": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/77476139384979f282670898b196ebe772696e7922baaa53e5f75346c3c9894e.zip",
  "create-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/6e2eeb41a4fe1b8b76d783a756a360e5f43f586d9da3ccf15240bbd055625124.zip",
  "history-dapp-service": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/92d7518e384f6c947f3ae754201dce9684b7d7a10b693a63d754b6547d22acdc.zip",
  "seed-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/023464c4b77c34431b8856adeb09c4101f4bb7ab9ddcf462a5854b604910456f.zip",
  "helloworld": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/1c65dc8f18fcc37fc6f8f435698b9c0665c237fa9bbf2876c061c142fed178c2.zip",
  "build-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/7feab63442d175f37f229086fe97ecb80e25a107c2c6a8396dcf292cb664c65b.zip",
  "readfn-dapp-service": "ipfs://QmeRfRdAFJFj9iJrtSF1fXZPqKWjafJjSrrmRtL1JF6Zhd",
  "client-lib-base": "ipfs://QmWQtoEk2FfAv9mrzfQi53tT38FngKdVmRnpnXuNdQnKxB",
  "migrations-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/ca613156b465c529b6cf67c3b6270f7e16be2c93a51d028208243e78853a734d.zip",
  "sample-zeus-extension": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/a0a4e869568ae2a70f26109ec402ac813926b574a4fe32922a6569134134e6da.zip",
  "bancor-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/390883c11be49bbbd1f865d534d81323e5dec729c3b70865df48d44ae8bc544a.zip",
  "dns-dapp-service": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/e4f8f790eb21ef892c8316220c25d60cce0e11e041a5f56eda6416667bac069a.zip",
  "eos-client-js": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/e1cbbacdba2581798637fc80df112432f331c2bcdbdc0e553219d3632fe80909.zip",
  "unlock-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/0bbf39f9526767cf6d8715622afa447a74799adb7263bba9c40fa87ef1a08193.zip",
  "auth-dapp-service": "ipfs://QmWPqjsS4GhPKcm3TGMRKRnKVKuskgmPNR5zY1CfDn8NE4",
  "all-dapp-services": "ipfs://QmaKcCjPFmLayxe2Dn8v4DJhFzo4KZD34uwy5EPTykQGZW",
  "eoscraft-frontend": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/cde31de780c59c7a31d5dc6a3f8074822a1209156f79c40ca2776e118506cc04.zip",
  "seed-frontends": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/7987c6b83c5c57ae380a259632e74470e469e209917a63e23ec9568ea5bfc81f.zip",
  "cron-dapp-service": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/e87e0b08c1eafff05163cb4cc84b042b3ec648ade1b27f0fd30993a0795d15c5.zip",
  "sign-dapp-service": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/e59fcec3c3660c609e668d7f6c00c3b73c298fd570ff2ccfc31dbbbc6cd33d06.zip",
  "sample-eos-cpp": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/b4431723f8fc3f3faaaf367ae6a12ff37143edc010fb14c3927a54cd505ed05e.zip",
  "seed-eos": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/3b4f56fe7df88f7104e89b797b8d293f8d1837bdf84d3d429f07949ee9b4aa37.zip",
  "coldtoken": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/02db754c3820f22f0bebfe5a6597af85e6e756d643f83b3fff8a22cbcb1e114e.zip",
  "seed-utils": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/f9288933b909d9f5ba069979628c9edb0ef5c02b9ccb0327ce4deb05b401f8b8.zip",
  "eos-keystore": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/2684b0b08662f5bdb6fe3a7d1951852769d4584e759dc3b2f9d24722360f9ee4.zip",
  "bancor-relay": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/4b3aee162f0c7c32c806f60653021e155f31a3b26add995bb007accd493263c1.zip",
  "microauctions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/e28cdbf92b5d52347f7a71f6405a256d778ddcd6cbed7533b3eaa95f23aed6d0.zip",
  "log-dapp-service": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/fd4e0c3b5fb94b14ed7b12ab584ab304b3ff4690064b83f7621b0ae52180e708.zip",
  "log-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/2105d4268ccb16f22769e6fd219a3d4888a05519f1f9cdf593a4e59648f8bae7.zip",
  "hooks-npm": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/7bd925847ec7e1b5d3d2ddb05b11f53f41540d5ed953e7381bc0a48af622254d.zip",
  "token": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/de4b0180bb65a95db3497f52bf086c17c8e56ee1349d9cbbdabb652f67bd0ccf.zip",
  "eosio-system-contracts": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/66fe341943fd6469eab3e91cf6be19803ac02ec5763f52dcd00ab166638f8562.zip",
  "craft": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/9f71c205126481fa073a12ab434ce709072b3d27a662b7db4b94a9d9bb273252.zip",
  "deepfreeze": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/f789e9b3ef5be3425b31b1385a6ab24295f97f3e9bc63bfde5f077b68c89e428.zip",
  "zeus-eos": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/ef337e8cef9dfa15711a8fc200eb2b10d2b77bc83de3a467ed063a3db9650afa.zip",
  "dapp-services-deploy": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/b6310dec56fcf4090e57e00756db68911ee368c71b0369e0e002863e4875aac9.zip",
  "testbox": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/73d163e46a3397e51ab57a25747b7c18cce893383aa95e1592b21f89db42dfd6.zip",
  "demux": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/4008cf9422d259e7162bc1038759257e6c26780e1ae2532a5b5ceb8b5d05e3e7.zip",
  "seed-zeus-base": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/d6b7be1f9c1df2889fa4b09e365231a2a6f617b8dd0253f0f5e82112cffaa2a3.zip",
  "unbox-extensions": "ipfs://QmNNLjDZD9c2zhaAEUbjCiTJDcQeq2B83tVnajVWByoRMa",
  "templates-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/1beeb5e809adcf0da30cb638a762987e6dd125c1d9c4a46fbf16477093acf691.zip",
  "frontend-main": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/c3fc658d8284776d77560c135640d499e17dc97b04b78bf01972e7e949287519.zip",
  "registry": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/13cc3d0dbc08d037fa82a8fe04239a2a01cd3d0bec773624cbe5d1c9c6d00aba.zip",
  "hooks-extensions": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/c5443790ff79fce1cb3059bcb71cb57f33f0a1ce3e32514232cf6b616a090ba1.zip",
  "game": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/9c673ee0234ddd1ea1ac6d9a9c0deafe8a965cf16400de3cb28d0695ebdb1699.zip",
  "mocha": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/1583db87c398d6830d090fb7c3423fcc4aafbe3f8adde44dc935c85c62df3ab3.zip",
  "seed-empty": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/cdb826e41eb0cae06afb1866c05b7f729386d60e7d5b5647c1aaba851264fea8.zip",
  "hooks-cpp-contracts": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/2f3829c8ecad41cf3543b37421ffd9ac15824100c1cff4793a1a674f67ad0bdc.zip",
  "liquidapps-deployment": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/5aead624b4be448990dd8d66755548c6e6fbdaf136e72521623345eb779f6c34.zip",
  "seed-tests": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/1618d6170041177e02e2dc0dc57b56c7172e01138d3d03b788c96c31799aa41d.zip",
  "repo-zeusrepoeos": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/39498d573bb45eeff9d1ad370e1b1c0184b43fa92935574731b144cef2f04189.zip",
  "templates-dsp-service": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/632a89626ebe786e2716b323f87f6a97d587cd0558ff65227a13b0e371fea449.zip",
  "frontend-react": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/221047ae216a09687f4521840b5fd66a5d89853e0f6dbb00eec853f048d6987e.zip",
  "seed-zeus-support": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/c70622baafa3404b3d172e08200eaf6cd15ad0e55272e2c7d4f74f4a2d79b0fa.zip",
  "cardgame": "https://s3.us-east-2.amazonaws.com/liquidapps.artifacts/boxes/bbb4bcaf6486675cdfee1fb86be3dd1219bf597de397252803f4ad6e85ace6c7.zip"
}
```

## [Source](https://github.com/liquidapps-io/zeus-sdk/tree/master/boxes/groups/repos/unbox-extensions)