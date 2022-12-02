# python

<!---
Note: Do NOT edit directly, this file was generated using https://github.com/chainguard-images/readme-generator
-->

[![CI status](https://github.com/chainguard-images/python/actions/workflows/release.yaml/badge.svg)](https://github.com/chainguard-images/python/actions/workflows/release.yaml)

This is a minimal Python image based on Alpine, using Python apks available on the Alpine Community repositories (not built from source as of now).<br/><br/>While this image is being developed, we will stick to the latest stable Python version. Supported versions in the long term are TBD.

## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/python:latest
```

## Supported tags

| Tag | Digest | Arch |
| --- | ------ | ---- |
| `latest` | `sha256:eaf4dc66e9854060810fe198314701702d87800e3dd045cc85e0cc6275e56ed8`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:eaf4dc66e9854060810fe198314701702d87800e3dd045cc85e0cc6275e56ed8) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221122` | `sha256:2fb92368254ec422ead3d189999868e1c35daf729178681766c4e827dfd6fdf4`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:2fb92368254ec422ead3d189999868e1c35daf729178681766c4e827dfd6fdf4) | `amd64` |
| `migration-20221125` | `sha256:ca1dede10d2b15036ae0ea9f5459419df5a2de171068d1ec2230f8a03f9a8d41`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:ca1dede10d2b15036ae0ea9f5459419df5a2de171068d1ec2230f8a03f9a8d41) | `amd64` |
| `migration-20221127` | `sha256:52a85ac37e4776041bbfe67733cb6500c7efb6b3f95bdd8005fbd2c4aabdacf7`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:52a85ac37e4776041bbfe67733cb6500c7efb6b3f95bdd8005fbd2c4aabdacf7) | `amd64` |
| `migration-20221129` | `sha256:d753169370eee75c39b5b113cccd2171327a7d676fb503d6a01344c4a3cf1089`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d753169370eee75c39b5b113cccd2171327a7d676fb503d6a01344c4a3cf1089) | `amd64` |
| `migration` `migration-20221202` | `sha256:7eb68d14ee3b9635a7b4230fe8f76046ee960f318569e39fb4a729cfcfd5f83c`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7eb68d14ee3b9635a7b4230fe8f76046ee960f318569e39fb4a729cfcfd5f83c) | `amd64` |
| `migration-20221120` | `sha256:c43a298d7a5442d3a94b2c09a5eb1690e0bc0d82f7bc967409de0e42668541ef`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:c43a298d7a5442d3a94b2c09a5eb1690e0bc0d82f7bc967409de0e42668541ef) | `amd64` |
| `migration-20221124` | `sha256:335f4780b3e6b2137db65a0da5df15ab8491af3f2e05c7af00d6f4a212d402b7`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:335f4780b3e6b2137db65a0da5df15ab8491af3f2e05c7af00d6f4a212d402b7) | `amd64` |
| `migration-20221126` | `sha256:2267da75e3fe01d6f215fc51fcbf268c2105da1eb9739f83ef4dbc774bd51259`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:2267da75e3fe01d6f215fc51fcbf268c2105da1eb9739f83ef4dbc774bd51259) | `amd64` |
| `migration-20221201` | `sha256:95a8afdd4e367a0efa6468988e284b36eaf9e2ba42e8057d16cd78e4a3b31761`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:95a8afdd4e367a0efa6468988e284b36eaf9e2ba42e8057d16cd78e4a3b31761) | `amd64` |
| `migration-20221128` | `sha256:4f524714a33b738ab1e6ffdff812b9062388e358071967885f6373aec1b5ee23`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:4f524714a33b738ab1e6ffdff812b9062388e358071967885f6373aec1b5ee23) | `amd64` |
| `migration-20221130` | `sha256:f88529ca0198e6e4de02c5c08d1e04570dbce4918e563d8fb17c928e4269baf6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:f88529ca0198e6e4de02c5c08d1e04570dbce4918e563d8fb17c928e4269baf6) | `amd64` |
| `migration-20221118` | `sha256:0012ef5bfc2d6791c962b1cc99cc2c2934cf216ca5937c9eb2a80935c8ad898a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:0012ef5bfc2d6791c962b1cc99cc2c2934cf216ca5937c9eb2a80935c8ad898a) | `amd64` |
| `migration-20221119` | `sha256:bd5fb01c0e49167e21f2a4be26a1e58262b391813bed99bb7fd81a1ec2457974`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:bd5fb01c0e49167e21f2a4be26a1e58262b391813bed99bb7fd81a1ec2457974) | `amd64` |
| `migration-20221121` | `sha256:0ccde133cd574742173984fbdc4768d728bcd45d6f0685fc2b961b1647cc27c1`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:0ccde133cd574742173984fbdc4768d728bcd45d6f0685fc2b961b1647cc27c1) | `amd64` |
| `migration-20221123` | `sha256:320632b276a7e69039cd9f97bc7172c82a6e9228cf5bb84d5e718a14404f7613`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:320632b276a7e69039cd9f97bc7172c82a6e9228cf5bb84d5e718a14404f7613) | `amd64` |


## Usage

To try out the image, run:

```shell
docker run --rm cgr.dev/chainguard/python python -VV
```

Python version installed 
```
Python 3.10.7 (main, Sep 11 2022, 22:42:41) [GCC 12.1.1 20220630]
```

Pip Version installed 

```shell 
docker run --rm cgr.dev/chainguard/python pip -V
```

```shell
pip 22.2.2 from /usr/lib/python3.10/site-packages/pip (python 3.10)
```


## Signing

All Chainguard Images are signed using [Sigstore](https://sigstore.dev)!

<details>
<br/>
To verify the image, download <a href="https://github.com/sigstore/cosign">cosign</a> and run:

```
COSIGN_EXPERIMENTAL=1 cosign verify cgr.dev/chainguard/python:latest | jq
```

Output:
```
Verification for cgr.dev/chainguard/python:latest --
The following checks were performed on each of these signatures:
  - The cosign claims were validated
  - Existence of the claims in the transparency log was verified offline
  - Any certificates were verified against the Fulcio roots.
[
  {
    "critical": {
      "identity": {
        "docker-reference": "ghcr.io/chainguard-images/python"
      },
      "image": {
        "docker-manifest-digest": "sha256:eaf4dc66e9854060810fe198314701702d87800e3dd045cc85e0cc6275e56ed8"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "b6b4b85d62ed8f5a6fa50b2dbe3d9bde098ee686",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/python",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIHrdyPy6CIkDbVCTo4xTRH2Wjdyh0IwUts9O7Sl3smhqAiBb1GNHE3Xz4PsSZ1jt16gfJKvJsVKWodyBknCjEL79Nw==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI4NDEyNDEzNjFjOTBlNTI1MGZmZGE2NWMyOGM1YjZmMDY1MmZiODJkZTFlMjZjNWNkYzRlMGFiYjUxMWNhMWIxIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FWUNJUUNIdVhhNGt6MWNJWkluakFQSjl6VVlnOEdUV0lEcUdLQS82VkZKSWRucDd3SWhBTEg1aXBnR3NGY0dHUDMraHlFUUFwMEluK0lHT2hOcG4yWVJGWlJKa0ZFSyIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnhha05EUVhwRFowRjNTVUpCWjBsVlJqTkhkMHRIY25WeWIwOTFia2xqT1VkdlMycFZPVTFNT1dGamQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFxUVhsTlJFRjVUVVJSZDFkb1kwNU5ha2w0VFdwQmVVMUVRWHBOUkZGM1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZwUzNnMlZHUlRhMUE0V0RWckt6SnRSMnRDVjNBME1VRkhiMVI0UzFGRVMyUXZlRWtLYUZJMFdVVmxkU3RNZG5rek4yVnpNblUxUWtGQlRYRnFVRmgyZURWMEsxaE9ha3BhVjNNM2FreG1lbWMxV2tKMmVVdFBRMEZyT0hkblowcE1UVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZwZW05V0NrSnVSRXN3UjFkSVNsQkJSR04wTHpGcmExUlBOVTVWZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGQldVUldVakJTUVZGSUwwSkdOSGRZU1ZwaFlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6UWpWa1IyaDJZbWs0ZFZveWJEQmhTRlpwVEROa2RtTnRkRzFpUnprelkzazVlVnBYZUd4WldFNXNURzVzYUdKWGVFRmpiVlp0Q21ONU9XOWFWMFpyWTNrNWRGbFhiSFZOUkd0SFEybHpSMEZSVVVKbk56aDNRVkZGUlVzeWFEQmtTRUo2VDJrNGRtUkhPWEphVnpSMVdWZE9NR0ZYT1hVS1kzazFibUZZVW05a1Ywb3hZekpXZVZreU9YVmtSMVoxWkVNMWFtSXlNSGRHWjFsTFMzZFpRa0pCUjBSMmVrRkNRV2RSU1dNeVRtOWFWMUl4WWtkVmR3cE9aMWxMUzNkWlFrSkJSMFIyZWtGQ1FYZFJiMWxxV21sT1IwazBUbGRSTWsxdFZtdFBSMWt4V1ZSYWJWbFVWWGRaYWtwcldXMVZlbHBFYkdsYVIxVjNDazlVYUd4YVZGazBUbXBCWTBKbmIzSkNaMFZGUVZsUEwwMUJSVVZDUVRWRVkyMVdhR1JIVldkVmJWWnpXbGRHZWxwVVFXMUNaMjl5UW1kRlJVRlpUeThLVFVGRlJrSkNhR3BoUjBad1ltMWtNVmxZU210TVYyeDBXVmRrYkdONU9YZGxXRkp2WWpJMGQwaFJXVXRMZDFsQ1FrRkhSSFo2UVVKQ1oxRlFZMjFXYlFwamVUbHZXbGRHYTJONU9YUlpWMngxVFVsSFNrSm5iM0pDWjBWRlFXUmFOVUZuVVVOQ1NITkZaVkZDTTBGSVZVRXpWREIzWVhOaVNFVlVTbXBIVWpSakNtMVhZek5CY1VwTFdISnFaVkJMTXk5b05IQjVaME00Y0Rkdk5FRkJRVWRGTUVSVWNpOTNRVUZDUVUxQlVtcENSVUZwUWxwek0xRm1WV3Q1YTBSNVVXSUtSblpSUkRaV2FVa3pObkJGYVRGS2JHRmhlREUyYkhkRU5FbFFlVEIzU1dkUVNIaGFZVzVWYVVodVlsRldWWFZzTnpaUlpIVTJaVWg2UjJod2JIWnhVd3BUUjJOT1pVTlVTWGg0VlhkRFoxbEpTMjlhU1hwcU1FVkJkMDFFWVVGQmQxcFJTWGRMUkhvME1UaFJOVWMwVjB4dVRURlRjWFJxTm1wWk56VnViRE5xQ21SbVR6bGpUV05uTjFjd1kyMUVjRUZMVDA5R01ETnZaamgxUkZsWFZuZFNObW95VmtGcVJVRnJOVzlxZVZkWVZVTklSV2xIVWxWVlNGUTVZVk52VXpJS1dVTk5OV2d2ZUZWdGVucFRNSHBYWTAxVVUxbFFZVUpMVVVOVlNuSjJaVWRaVmtGMVkwTlpNQW90TFMwdExVVk9SQ0JEUlZKVVNVWkpRMEZVUlMwdExTMHRDZz09In19fX0=",
          "integratedTime": 1669940466,
          "logIndex": 8258894,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/python/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/python",
      "githubWorkflowSha": "b6b4b85d62ed8f5a6fa50b2dbe3d9bde098ee686",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3597697038",
      "sha": "b6b4b85d62ed8f5a6fa50b2dbe3d9bde098ee686"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

