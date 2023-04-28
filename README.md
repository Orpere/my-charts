# [my-charts](https://orpere.github.io/my-charts/)
helms charts


```bash
cd packages
helm package ../charts/chart

#Update index.yml searching all first level subfolders for possible packaged charts
cd ..
helm repo index . --url https://<github_username>.github.io/<repo_name>

```

