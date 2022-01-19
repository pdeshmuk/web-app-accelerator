# Accelerator Log

## Options
```json
{
  "branch" : "main",
  "description" : "new-tanzu-java-web-app-accelerator",
  "icon" : "https://raw.githubusercontent.com/simple-starters/icons/master/icon-tanzu-light.png",
  "name" : "my-new-accelerator",
  "projectName" : "new-tanzu-java-web-app-accelerator",
  "url" : "https://github.com/pdeshmuk/tanzu-java-web-app"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(YTT, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (YTT)
┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"artifactVersion":"0.0.1-beta","icon":"https://raw.githubusercontent.com/simple-starters/icons/master/icon-tanzu-light.png","name":"my-new-accelerator","description":"new-tanzu-java-web-app-accelerator","artifactId":"new-tanzu-java-web-app-accelerator","projectName":"new-tanzu-java-web-app-accelerator","branch":"main","url":"https://github.com/pdeshmuk/tanzu-java-web-app"}
┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input12168216803457400110, --data-values-file, /tmp/accelerator-options5150490441333642340.json, --output-files, /tmp/ytt-output13265101249351581201]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].include (Include)
┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┗ ┗ Debug new-accelerator.yaml didn't match [README.md] -> excluded
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
