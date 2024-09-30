## [0.9.0](https://github.com/themoriarti/proxmox-csi-plugin/compare/v0.8.2...v0.9.0) (2024-09-30)


### ⚠ BREAKING CHANGES

* 

### refactor

* rename storageID to storage ([303f430](https://github.com/themoriarti/proxmox-csi-plugin/commit/303f43080c8fcf90194e087af7e1f44b33361d19))


### Features

* add unsafe env ([36fa532](https://github.com/themoriarti/proxmox-csi-plugin/commit/36fa5324074d6a695404c0c94fee65ff35c2d96e))
* **chart:** add allowedTopologies ([41cb02a](https://github.com/themoriarti/proxmox-csi-plugin/commit/41cb02a16dfa1b6abc2d2023d0d01f59a9501c8f))
* **chart:** add initContainers and hostAliases ([769c008](https://github.com/themoriarti/proxmox-csi-plugin/commit/769c008bb5cbd2a21303f12171d16df78000473e))
* **chart:** add support to mount a custom CA ([9b94627](https://github.com/themoriarti/proxmox-csi-plugin/commit/9b94627a9fb793b679b834efcf5ce84c36e2cd39))
* **chart:** add value to customize kubeletDir ([bbb627f](https://github.com/themoriarti/proxmox-csi-plugin/commit/bbb627f1a871f483f47888f2b158ad3370926dd0))
* **chart:** make StorageClass parameters/mountOptions configurable ([a78e338](https://github.com/themoriarti/proxmox-csi-plugin/commit/a78e338d3432d176ea543a3a455cfbcc7b1f5676))
* **chart:** support setting annotations and labels on storageClasses ([a5f5add](https://github.com/themoriarti/proxmox-csi-plugin/commit/a5f5adde7c3d533cae45660da312883b4ed1a24c))
* controller ([9f0f7a3](https://github.com/themoriarti/proxmox-csi-plugin/commit/9f0f7a325b1f06e611deca18808dcdcc4bf7e5ef))
* cosign images ([5e13f3f](https://github.com/themoriarti/proxmox-csi-plugin/commit/5e13f3f3874509484609350ecca3e9bd03ca4417))
* decrease node image ([93a04b6](https://github.com/themoriarti/proxmox-csi-plugin/commit/93a04b67ba8b11f7bf1a587a066552039b1d57d9))
* disk speed limit ([c464dab](https://github.com/themoriarti/proxmox-csi-plugin/commit/c464dabb186f1a451057d1ba7c736a919b607c59))
* drop node capabilities ([927f664](https://github.com/themoriarti/proxmox-csi-plugin/commit/927f6641a762bcf43556eaf0688fc684106002a5))
* expose metrics ([4bbe65d](https://github.com/themoriarti/proxmox-csi-plugin/commit/4bbe65dccc54192005d663fef86c2c40fd1c3b2c))
* helm oci release ([c438712](https://github.com/themoriarti/proxmox-csi-plugin/commit/c4387124372a08f2a31dd0934c9cf41b67f12eba))
* mkfs block/inode size options ([88f4ebc](https://github.com/themoriarti/proxmox-csi-plugin/commit/88f4ebcf33cef7409090383b68bbec6f8d52ffe5))
* noatime flag for ssd ([cd4f3f7](https://github.com/themoriarti/proxmox-csi-plugin/commit/cd4f3f77d38ef1e6b34c337c96b3b60fd2f04007))
* node daemon ([54dec7d](https://github.com/themoriarti/proxmox-csi-plugin/commit/54dec7dafe79f51c8d0a99a205ddc1fdd5bbab26))
* node daemonsets ([269c708](https://github.com/themoriarti/proxmox-csi-plugin/commit/269c7080fa302151ea281a74bb9b1757e3ec8d36))
* pin version ([e81d8e3](https://github.com/themoriarti/proxmox-csi-plugin/commit/e81d8e326cd48ebd2cc2578d88bccc93d5c421ab))
* prefer providerID ([7dcde72](https://github.com/themoriarti/proxmox-csi-plugin/commit/7dcde72bad2b036638cb3644a35deeb8c3ee3d47))
* pv/pvc cli helper ([d97bc32](https://github.com/themoriarti/proxmox-csi-plugin/commit/d97bc3245f2f370deb658ccf5e54fcdc38e5929d))
* raw block device ([1be660b](https://github.com/themoriarti/proxmox-csi-plugin/commit/1be660bf3014fa3e1d40251561a67b76d1e9cf98))
* regional block devices ([c7d1541](https://github.com/themoriarti/proxmox-csi-plugin/commit/c7d1541d4d8f0818b6af27e497746415c1448e03))
* remove udev dependency ([1810ec7](https://github.com/themoriarti/proxmox-csi-plugin/commit/1810ec71f56a03a462219a58f81c3d24e9fb1714))
* resize pvc ([bd2c653](https://github.com/themoriarti/proxmox-csi-plugin/commit/bd2c65362355d2cb3bc05a67ec29cf4e6cd6461c))
* storage encryption ([26c1928](https://github.com/themoriarti/proxmox-csi-plugin/commit/26c19288b80ed2847ab0df63e5480cf4f1f059e4))
* swap pv in already created pvc ([76c899e](https://github.com/themoriarti/proxmox-csi-plugin/commit/76c899e4e1c8f2287854a4e08fbbdd8a1c7360a9))
* switch to distroless ([ff1c9bf](https://github.com/themoriarti/proxmox-csi-plugin/commit/ff1c9bf44798c28b3888e6eab6eabcddc203a57a))
* trim filesystem ([dc7dbbd](https://github.com/themoriarti/proxmox-csi-plugin/commit/dc7dbbdb6e9deecab0abd439c77abffdd69f692a))
* use readonly root ([ca00846](https://github.com/themoriarti/proxmox-csi-plugin/commit/ca00846bb87c8f0e9a35c2ab7a6f2ceadb14bcf2))
* use release please tool ([39c4b22](https://github.com/themoriarti/proxmox-csi-plugin/commit/39c4b223f64351c2c2e8685d55091ffe7d58a7ce))
* volume capability ([1088dbb](https://github.com/themoriarti/proxmox-csi-plugin/commit/1088dbb8297802a52835bc4075b6553cb7e8a81a))
* wait volume to be detached ([3683d96](https://github.com/themoriarti/proxmox-csi-plugin/commit/3683d96136a52d06274788006e0c5c67d9818c93))


### Bug Fixes

* add delay before unattach device ([ff575d1](https://github.com/themoriarti/proxmox-csi-plugin/commit/ff575d17af06bbf629ab769e8e512872a3426e66))
* allow nfs shared storages ([04cfb97](https://github.com/themoriarti/proxmox-csi-plugin/commit/04cfb97993fb536994a8cf0da6542ea8f6fd696c))
* build release ([facdec5](https://github.com/themoriarti/proxmox-csi-plugin/commit/facdec5be4f0335eb489fc600a175e63584953ba))
* **chart:** detect safe mounted behavior ([5580695](https://github.com/themoriarti/proxmox-csi-plugin/commit/5580695bd9a3e55091a50a35c95cff9bd24bc390))
* check rbac permission ([57a6b0d](https://github.com/themoriarti/proxmox-csi-plugin/commit/57a6b0dbb7b60309f9185a475ac1e949878ff349))
* check volume existence ([aba0ca8](https://github.com/themoriarti/proxmox-csi-plugin/commit/aba0ca8fb4d96af8324de03856a55a8f130311e3))
* cli migration ([41b19bd](https://github.com/themoriarti/proxmox-csi-plugin/commit/41b19bdd40db9f84c0d65fe41983e2c2ee0b4977))
* cluster schema ([494a82b](https://github.com/themoriarti/proxmox-csi-plugin/commit/494a82b3dcfd8ea3cd0a952d766f27631b6e7d65))
* deps update ([657ad00](https://github.com/themoriarti/proxmox-csi-plugin/commit/657ad006c2e93f27ed08966c8e493cfb852a49ee))
* detach volume error ([dc128d1](https://github.com/themoriarti/proxmox-csi-plugin/commit/dc128d17ab1e298bff267d7b776e893ba7929d3e))
* find zone by region ([4eae22d](https://github.com/themoriarti/proxmox-csi-plugin/commit/4eae22d81c2ccd08a159f04412918deb09e19ab5))
* goreleaser ([4e0e87a](https://github.com/themoriarti/proxmox-csi-plugin/commit/4e0e87a34671681394b901f4956fae605dd892e3))
* goreleaser ([04a40f4](https://github.com/themoriarti/proxmox-csi-plugin/commit/04a40f40ebd6ef8904bdcc083ce028cf87544019))
* helm chart metrics option ([e5ef1b1](https://github.com/themoriarti/proxmox-csi-plugin/commit/e5ef1b132251e7bfb98234ee3ea935524db55d16))
* helm chart podAnnotation ([b935d88](https://github.com/themoriarti/proxmox-csi-plugin/commit/b935d88e14df3982ff59541ee0732e5b421a2088))
* helm create namespace ([364b8be](https://github.com/themoriarti/proxmox-csi-plugin/commit/364b8bee9342e8c6437078dfc0488784d8a41000))
* helm liveness context ([e1ed889](https://github.com/themoriarti/proxmox-csi-plugin/commit/e1ed889510ce2309f2f63243c95e50b03c50254e))
* implement structured logging ([cb5fb4e](https://github.com/themoriarti/proxmox-csi-plugin/commit/cb5fb4e0339fa714e13e421e557252ab348dbe25))
* kubectl apply in readme ([bc2f88b](https://github.com/themoriarti/proxmox-csi-plugin/commit/bc2f88bdd01c68be2be620af464461459279f642))
* log sanitizer ([474e734](https://github.com/themoriarti/proxmox-csi-plugin/commit/474e734e52b7725b62183911f7843e80b51594e1))
* publish shared volumes ([a681b2b](https://github.com/themoriarti/proxmox-csi-plugin/commit/a681b2b2b6431a23ef45e1705b0adb85dca34f5b))
* pv force migration ([8ecf990](https://github.com/themoriarti/proxmox-csi-plugin/commit/8ecf990a9b746358a505c25c0c728fd77d776b00))
* pvc migration ([ddfc362](https://github.com/themoriarti/proxmox-csi-plugin/commit/ddfc36229ccdf2fdc29e9fff9e59463f4b2da866))
* raise condition during volume attach ([3bf3ef5](https://github.com/themoriarti/proxmox-csi-plugin/commit/3bf3ef5c72c93a6a965e62a7cc5e38de1e0732a9))
* release check ([c3bd4e7](https://github.com/themoriarti/proxmox-csi-plugin/commit/c3bd4e72376ad622172423da3be4f089216265b5))
* release doc ([215c366](https://github.com/themoriarti/proxmox-csi-plugin/commit/215c366b5bb4bc86e7bee43fcf4a228193fcbbbe))
* release please ([593f605](https://github.com/themoriarti/proxmox-csi-plugin/commit/593f605fdb2b8f3fc6ece800bb44f4cfb93df882))
* release please ([ffad744](https://github.com/themoriarti/proxmox-csi-plugin/commit/ffad744ed54f59eb8cf610f84855845de4625886))
* remove nocloud label ([74e42b2](https://github.com/themoriarti/proxmox-csi-plugin/commit/74e42b2818d199fd4058f7dbd26eea1e4f70647a))
* skip lxc containers on resize process ([a24d24e](https://github.com/themoriarti/proxmox-csi-plugin/commit/a24d24e6ac81f76f06adc9d834beba769975d055))

## [v0.8.2](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.8.1...v0.8.2) (2024-09-28)

Welcome to the v0.8.2 release of Proxmox CSI Plugin!

### Bug Fixes

- log sanitizer (474e734)

### Miscellaneous

- release v0.8.2 (0274c03)


## [v0.8.1](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.8.0...v0.8.1) (2024-09-24)

Welcome to the v0.8.1 release of Proxmox CSI Plugin!

### Bug Fixes

- release please (593f605)
- goreleaser (4e0e87a)

### Miscellaneous

- release v0.8.1 (3f8bd85)


## [v0.8.0](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.7.0...v0.8.0) (2024-09-23)

Welcome to the v0.8.0 release of Proxmox CSI Plugin!

### Bug Fixes

- check rbac permission (57a6b0d)
- helm chart metrics option (e5ef1b1)
- allow nfs shared storages (04cfb97)
- helm chart podAnnotation (b935d88)

### Features

- expose metrics (4bbe65d)
- add unsafe env (36fa532)

### Miscellaneous

- release v0.8.0 (589de9c)
- bump deps (9a0161b)
- bump deps (3c3c122)
- bump deps (c5769c1)
- **chart:** update readme (c76555a)


## [v0.7.0](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.6.1...v0.7.0) (2024-06-14)

Welcome to the v0.7.0 release of Proxmox CSI Plugin!

### Bug Fixes

- implement structured logging (cb5fb4e)
- pv force migration (8ecf990)

### Features

- wait volume to be detached (3683d96)
- swap pv in already created pvc (76c899e)

### Miscellaneous

- release v0.7.0 (9424c06)
- release v0.7.0 (7362940)
- bump deps (5bf0677)
- bump deps (89adec9)
- release v0.6.1 (ac1ef92)


## [v0.6.1](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.6.0...v0.6.1) (2024-04-13)

Welcome to the v0.6.1 release of Proxmox CSI Plugin!

### Bug Fixes

- build release (facdec5)
- release doc (215c366)

### Miscellaneous

- release v0.6.1 (e7dfde2)


## [v0.6.0](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.5.0...v0.6.0) (2024-04-13)

Welcome to the v0.6.0 release of Proxmox CSI Plugin!

### Bug Fixes

- pvc migration (ddfc362)
- deps update (657ad00)
- cli migration (41b19bd)
- goreleaser (04a40f4)

### Features

- remove udev dependency (1810ec7)
- **chart:** support setting annotations and labels on storageClasses (a5f5add)
- **chart:** add initContainers and hostAliases (769c008)

### Miscellaneous

- release v0.6.0 (0b13bd0)
- bump deps (67dc34c)
- bump deps (2f9f17a)
- **chart:** update sidecar deps (5f16e6b)


## [v0.5.0](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.4.1...v0.5.0) (2024-02-20)

Welcome to the v0.5.0 release of Proxmox CSI Plugin!

### Bug Fixes

- add delay before unattach device (ff575d1)
- release please (ffad744)
- **chart:** detect safe mounted behavior (5580695)

### Features

- prefer providerID (7dcde72)
- pv/pvc cli helper (d97bc32)
- use release please tool (39c4b22)
- use readonly root (ca00846)
- raw block device (1be660b)
- **chart:** add support to mount a custom CA (9b94627)

### Miscellaneous

- release v0.5.0 (a361ce9)
- bump deps (ac4ddd0)


## [v0.4.1](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.4.0...v0.4.1) (2024-01-01)

Welcome to the v0.4.1 release of Proxmox CSI Plugin!

### Bug Fixes

- publish shared volumes (a681b2b)
- find zone by region (4eae22d)

### Features

- **chart:** add value to customize kubeletDir (bbb627f)
- **chart:** add allowedTopologies (41cb02a)

### Miscellaneous

- release v0.4.1 (fd8d14f)
- bump deps (2a86bd7)
- bump deps (d8c98ea)
- bump deps (9054282)


## [v0.4.0](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.3.0...v0.4.0) (2023-10-24)

Welcome to the v0.4.0 release of Proxmox CSI Plugin!

### Bug Fixes

- check volume existence (aba0ca8)
- helm create namespace (364b8be)
- remove nocloud label (74e42b2)

### Features

- mkfs block/inode size options (88f4ebc)
- disk speed limit (c464dab)
- **chart:** make StorageClass parameters/mountOptions configurable (a78e338)

### Miscellaneous

- release v0.4.0 (764b741)
- bump deps (9e5a139)
- bump deps (a243ffb)


## [v0.3.0](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.2.0...v0.3.0) (2023-09-19)

Welcome to the v0.3.0 release of Proxmox CSI Plugin!

### Features

- storage encryption (26c1928)
- volume capability (1088dbb)
- regional block devices (c7d1541)

### Miscellaneous

- release v0.3.0 (324ad91)
- bump deps (5f5d781)
- bump actions/checkout from 3 to 4 (f75bfff)
- bump sigstore/cosign-installer from 3.1.1 to 3.1.2 (51419d3)
- bump deps (ae63a06)
- bump deps (4ceef77)


## [v0.2.0](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.1.1...v0.2.0) (2023-08-07)

Welcome to the v0.2.0 release of Proxmox CSI Plugin!

### Bug Fixes

- skip lxc containers on resize process (a24d24e)
- helm liveness context (e1ed889)
- detach volume error (dc128d1)
- kubectl apply in readme (bc2f88b)

### Features

- noatime flag for ssd (cd4f3f7)
- cosign images (5e13f3f)
- pin version (e81d8e3)
- helm oci release (c438712)
- drop node capabilities (927f664)
- trim filesystem (dc7dbbd)

### Miscellaneous

- release v0.2.0 (6a2d98a)
- bump actions versions (b477132)
- bump deps (f6d726c)
- bump deps (ecea2ad)
- bump deps (28f0a72)
- bump deps (f00f057)


## [v0.1.1](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.1.0...v0.1.1) (2023-05-12)

Welcome to the v0.1.1 release of Proxmox CSI Plugin!

### Features

- switch to distroless (ff1c9bf)
- decrease node image (93a04b6)

### Miscellaneous

- release v0.1.1 (429a420)
- bump deps (4e80caf)
- bump deps (be954c9)


## [v0.1.0](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.0.2...v0.1.0) (2023-05-04)

Welcome to the v0.1.0 release of Proxmox CSI Plugin!

### Bug Fixes

- release check (c3bd4e7)

### Miscellaneous

- release v0.1.0 (449bddf)


## [v0.0.2](https://github.com/sergelogvinov/proxmox-csi-plugin/compare/v0.01...v0.0.2) (2023-04-29)

Welcome to the v0.0.2 release of Proxmox CSI Plugin!

### Miscellaneous

- release v0.0.2 (8390a9f)


## v0.01 (2023-04-29)

Welcome to the v0.01 release of Proxmox CSI Plugin!

### Bug Fixes

- raise condition during volume attach (3bf3ef5)
- cluster schema (494a82b)

### Features

- resize pvc (bd2c653)
- node daemon (54dec7d)
- node daemonsets (269c708)
- controller (9f0f7a3)

### Miscellaneous

- release v0.0.1 (56b4297)
