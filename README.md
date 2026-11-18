# SAGE7 Artifactory

Signed, notarized downloads of SAGE7 AI apps. Binaries are attached to [Releases](https://github.com/sage7-ai/sage7-artifactory/releases), tagged `<product>-<version>-<build>`.

| Product | Platform | Latest download | Product page |
|---|---|---|---|
| [OnCue](oncue/) | macOS 14+ | [OnCue.zip](https://github.com/sage7-ai/sage7-artifactory/releases/download/oncue-latest/OnCue.zip) | [sage7.ai/products/oncue](https://sage7.ai/products/oncue) |

Every Mac build is signed with the Developer ID of **Sage7AI LLC (8AL763XQA7)** and notarized by Apple. Verify a download:

```sh
spctl -a -vv -t exec /Applications/OnCue.app
# accepted · source=Notarized Developer ID · origin=Developer ID Application: Sage7AI LLC (8AL763XQA7)
```

This repository holds release artifacts only, not source code. The apps are proprietary; © SAGE7 AI LLC. Support: support@sage7.ai
