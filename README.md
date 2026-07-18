# NTK Mihon Extension Repository

Personal Mihon repository containing NTK v1.4.4.

Repository URL for Mihon:

```text
https://raw.githubusercontent.com/in71-king/NTK-Mihon-Extension/refs/heads/main/index.min.json
```

## Upload with GitHub Codespaces

Create a public GitHub repository named exactly `NTK-Mihon-Extension`, open a Codespace for it, upload `ntk-mihon-repository.zip`, then run:

```bash
unzip -o ntk-mihon-repository.zip
git add apk icon index.json index.min.json README.md
git commit -m "Publish NTK Mihon extension"
git push
```

The ZIP contains repository contents at its root, so do not place them inside an extra folder.

## Signing limitation

This APK is signed with the temporary Android debug certificate from the successful workflow run. The index matches that certificate. A future APK built in a different workflow run may use a different certificate and therefore may not update this installation. For reliable future updates, configure a persistent release signing key before publishing a later version.

이 프로젝트는 Tachimanga, Mihon, Tachiyomi 또는 대상 웹사이트와 제휴하지 않은 개인용 수정본입니다.
