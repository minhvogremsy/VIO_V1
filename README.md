# VIO_V1
```
echo "ZIP_PASSWORD=<pass>" > .secrets
echo "GITHUB_TOKEN=<your_personal_access_token>" > .secrets
act -W .github/workflows/update_v1.yml --secret-file .secrets

```