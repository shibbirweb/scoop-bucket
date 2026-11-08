# SendMock Scoop bucket

Scoop manifests for [SendMock](https://github.com/shibbirweb/sendmock), the local email, SMS, push, payment and webhook catcher for development and CI.

## Install

Add the bucket:

```powershell
scoop bucket add shibbirweb https://github.com/shibbirweb/scoop-bucket
```

Stable:

```powershell
scoop install shibbirweb/sendmock
```

Beta:

```powershell
scoop install shibbirweb/sendmock-beta
```

The manifests in `bucket/` are written by SendMock's release workflow for every release; do not edit them by hand. Report problems in the [SendMock repository](https://github.com/shibbirweb/sendmock/issues).
