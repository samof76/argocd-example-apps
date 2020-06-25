# [1.0.0-staging.2](https://github.com/samof76/argocd-example-apps/compare/v1.0.0-staging.1...v1.0.0-staging.2) (2020-06-25)

### Bug Fixes

- This will fix issues ([fe1935b](https://github.com/samof76/argocd-example-apps/commit/fe1935b6a2d8914c90b478eaa0e0363dc6e032f1))

### Other

- Fix port ([a44f5a1](https://github.com/samof76/argocd-example-apps/commit/a44f5a1b34703b396ea5e8fea07acb33bf17b35c))
- Just testing ([3d758b9](https://github.com/samof76/argocd-example-apps/commit/3d758b92b222cbb9c1be1e506ee73c81c9a81aae))

# 1.0.0-staging.1 (2020-06-25)

### Bug Fixes

- adding the semantic versioning ([4ff773d](https://github.com/samof76/argocd-example-apps/commit/4ff773d98e787d83932b41c25d2a26714cbb1dd9))

### Other

- Increase the replicas to five ([a3477ca](https://github.com/samof76/argocd-example-apps/commit/a3477ca906adabd0a1571ab985a85b0d597752a6))
- Reduce replicas to one ([b261c92](https://github.com/samof76/argocd-example-apps/commit/b261c92f3f52a60b369b9f349ea5d4f6ba892a03))
- Deploy to argocd-test namespace ([023b4d5](https://github.com/samof76/argocd-example-apps/commit/023b4d5f4eb3999236e33a42777cde6709b40b12))
- Replicas 3 ([7ea1fa6](https://github.com/samof76/argocd-example-apps/commit/7ea1fa64f8159866b1cdd42cac4a777af3c26517))
- Increase the replicas to 4 ([53947b5](https://github.com/samof76/argocd-example-apps/commit/53947b55c78e0a885639efbd2ead07609a26f92f))
- Add one more replica ([6d036f9](https://github.com/samof76/argocd-example-apps/commit/6d036f979ba347b64b15e39000f0bca32df7125c))
- Updates examples to better reflect hook usage today (#41) ([6bed858](https://github.com/samof76/argocd-example-apps/commit/6bed858de32a0e876ec49dad1a2e3c5840d3fb07)), closes [#41](https://github.com/samof76/argocd-example-apps/issues/41)
- Tidy up the examples repo + add a Helm hooks examples (#40) ([94ad32f](https://github.com/samof76/argocd-example-apps/commit/94ad32f4ea26798997774ffc3e20fbfa8e0d8c21)), closes [#40](https://github.com/samof76/argocd-example-apps/issues/40)
- Use apps/v1 API for Deployment resources (#38) ([5c2d89b](https://github.com/samof76/argocd-example-apps/commit/5c2d89b897c4df42e06f94622f857dc4d7adc8f8)), closes [#38](https://github.com/samof76/argocd-example-apps/issues/38)
- Fix broken pre-post-sync example (#37) ([b4ebe00](https://github.com/samof76/argocd-example-apps/commit/b4ebe0049d2ad363760cd2624df36c3b0acaab0e)), closes [#37](https://github.com/samof76/argocd-example-apps/issues/37)
- doc-fix: update kasane readme (#36) ([1ccdee0](https://github.com/samof76/argocd-example-apps/commit/1ccdee0a611224ccc6b9ff7919fe7002f905436e)), closes [#36](https://github.com/samof76/argocd-example-apps/issues/36)
- Clean-up (#35) ([6150e82](https://github.com/samof76/argocd-example-apps/commit/6150e82d927fd887f87b5d640514d0425e769027)), closes [#35](https://github.com/samof76/argocd-example-apps/issues/35)
- add application of applications example (#29) ([08836bd](https://github.com/samof76/argocd-example-apps/commit/08836bd970037ebcd14494831de4635bad961139)), closes [#29](https://github.com/samof76/argocd-example-apps/issues/29)
- Add example for jsonnet using functions with top level arguments (#30) ([454cc52](https://github.com/samof76/argocd-example-apps/commit/454cc5296246da3f1bd251555a2e96ee7969aa41)), closes [#30](https://github.com/samof76/argocd-example-apps/issues/30)
- Sync wave (#28) ([0ad95c5](https://github.com/samof76/argocd-example-apps/commit/0ad95c51bcefef6c1b42f7ebd64089e6ea13a8e7)), closes [#28](https://github.com/samof76/argocd-example-apps/issues/28)
- Update README.md (#26) ([35ca7c3](https://github.com/samof76/argocd-example-apps/commit/35ca7c333d593a6f56e3c9ec1a6facd19fd9f4a0)), closes [#26](https://github.com/samof76/argocd-example-apps/issues/26)
- Adds finalizers (#25) ([e8fe380](https://github.com/samof76/argocd-example-apps/commit/e8fe3804f856fb5f54084808dcf1fc8e8eeb4223)), closes [#25](https://github.com/samof76/argocd-example-apps/issues/25)
- fix (#23) ([c77a1b2](https://github.com/samof76/argocd-example-apps/commit/c77a1b2d151ff40637e2dd8ccc26f4234d605d91)), closes [#23](https://github.com/samof76/argocd-example-apps/issues/23)
- Adds app-of-apps (#22) ([3636323](https://github.com/samof76/argocd-example-apps/commit/36363233d00d67a7ab6b180053dc3322af9bc5c6)), closes [#22](https://github.com/samof76/argocd-example-apps/issues/22)
- Fix blue-gree example instructions (#21) ([90ff684](https://github.com/samof76/argocd-example-apps/commit/90ff6843e25cc17d03c73afefb91b826cd816653)), closes [#21](https://github.com/samof76/argocd-example-apps/issues/21)
- Add link to blue green sample app (#20) ([3f461c3](https://github.com/samof76/argocd-example-apps/commit/3f461c308f96bb219e5ffc0467acde4b6a812c13)), closes [#20](https://github.com/samof76/argocd-example-apps/issues/20)
- Add blue-green deployment example (#19) ([fd70f16](https://github.com/samof76/argocd-example-apps/commit/fd70f16a43d8f14626329a4f687bc8f8f689e9f6)), closes [#19](https://github.com/samof76/argocd-example-apps/issues/19)
- Fix init command in Helm + Kustomize example (#15) ([826b3fa](https://github.com/samof76/argocd-example-apps/commit/826b3fa710e76b20ea16ff55228ed84ac4d996c7)), closes [#15](https://github.com/samof76/argocd-example-apps/issues/15)
- Removes blue-green-deploy. Removes kustomize1. Moves kustomize2-guestbook to kustomize-guestbook (#12) ([3ef31ae](https://github.com/samof76/argocd-example-apps/commit/3ef31aef9ce5d9d64bdd3139878a7ebc45473cde)), closes [#12](https://github.com/samof76/argocd-example-apps/issues/12)
- Add config template plugin examples (#7) ([23eeb09](https://github.com/samof76/argocd-example-apps/commit/23eeb0925ba967b73182c65802f7e19a7f3a5696)), closes [#7](https://github.com/samof76/argocd-example-apps/issues/7)
- Adds example usage for Kustomize 2 (#6) ([179faab](https://github.com/samof76/argocd-example-apps/commit/179faabd63c682e0638fb14b2c69c4a9a47c31b3)), closes [#6](https://github.com/samof76/argocd-example-apps/issues/6)
- Update guestbook-ui-svc.yaml ([8a1cb4a](https://github.com/samof76/argocd-example-apps/commit/8a1cb4a02d3538e54907c827352f66f20c3d7b0d))
- adding instructions to helm-dependency example about subchart conditions (#5) ([1ff8a67](https://github.com/samof76/argocd-example-apps/commit/1ff8a67040f482a9186f8d1f5221b5e908b9c27c)), closes [#5](https://github.com/samof76/argocd-example-apps/issues/5)
- Add helm-dependency example demonstrating customization of OTS chart ([58594ac](https://github.com/samof76/argocd-example-apps/commit/58594acf362b1452349e2a15163d3357b9160663))
- Add back guestbook-ui-svc.yaml ([8c06d23](https://github.com/samof76/argocd-example-apps/commit/8c06d232686113445d1ab064789fa0843afcdf0c))
- Remove workflow example and limit revision history ([b0decab](https://github.com/samof76/argocd-example-apps/commit/b0decab622473b6526a7025b2b52e2a6301dd83a))
- Update examples for Argo CD v0.11 ([382b858](https://github.com/samof76/argocd-example-apps/commit/382b85852fa33f13d4987424853c5206b9231ff0))
- Fix annotation for pre-post sync example ([62c4539](https://github.com/samof76/argocd-example-apps/commit/62c453945b53e97e08f890dcd5aa382662e304c4))
- Add examples for a plain-YAML guestbook and kustomize guestbook ([d9c52b4](https://github.com/samof76/argocd-example-apps/commit/d9c52b4c89474bf6f7c33694b7650e54b60944b4))
- Add jsonnet example ([c86a7fb](https://github.com/samof76/argocd-example-apps/commit/c86a7fbb8e191c6e317526ac21db7a43f4c37688))
- Add jsonnet example ([9c549b1](https://github.com/samof76/argocd-example-apps/commit/9c549b198c6d3044197941014d170320efe3195a))
- Add a second values file in the helm-guestbook example ([a3ea618](https://github.com/samof76/argocd-example-apps/commit/a3ea618bb9d95efbaf901f4f491e26fd88e868c3))
- Add helm guestbook example ([9421276](https://github.com/samof76/argocd-example-apps/commit/9421276024ccb8b07f0c7f68607b2e77fe16c0fa))
- Tweak timings of the pre-post-sync example ([5eb3352](https://github.com/samof76/argocd-example-apps/commit/5eb3352b40ddc27e528eb7aa72542a0ff0d2e265))
- Add more environments to guestbook. Add README content ([e3a5ac2](https://github.com/samof76/argocd-example-apps/commit/e3a5ac20fc669aec1df512ce04e81c0a4789734b))
- Update pre-post-sync app to v0.2 ([e0c05b3](https://github.com/samof76/argocd-example-apps/commit/e0c05b3b149093b22d1541f5f3974d4c4ae31284))
- Add Pre/PostSync job example ([144fd97](https://github.com/samof76/argocd-example-apps/commit/144fd97a0c705db1cb33c72b56a04055e24fa4f7))
- Update bg-guestbook app to v0.2 ([96a019c](https://github.com/samof76/argocd-example-apps/commit/96a019c088db9e2eb7a5a05f5df08ee4e1c1c56a))
- Add blue green deployment example app ([b9eec94](https://github.com/samof76/argocd-example-apps/commit/b9eec94e6057656807153921f847bd32a15565ae))
- Update to newer sock shop manifests ([852d97d](https://github.com/samof76/argocd-example-apps/commit/852d97d96eb78962978ff1a3baf1b75b34ebf15b))
- Add sock shop app ([4972315](https://github.com/samof76/argocd-example-apps/commit/49723157a6cde9e03d01ebc8333f2ed6c94d474b))
- Update guestbook app to v0.2 ([a296624](https://github.com/samof76/argocd-example-apps/commit/a296624b793784519e0997ff54bb024c39aabe15))
- Add the guestbook example app (v0.1) ([67de934](https://github.com/samof76/argocd-example-apps/commit/67de934fd7f22062a4e2ac8b8d20cfc97f2b4e7f))
