# Accelerator Log

## Options
```json
{
  "branch" : "master",
  "description" : "",
  "icon" : "https://raw.githubusercontent.com/simple-starters/icons/master/icon-tanzu-light.png",
  "name" : "microsauer",
  "projectName" : "new-accelerator",
  "url" : "https://github.com/assafsauer/micro-spring/tree/master/02.restful-web-services"
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
┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"artifactVersion":"0.0.1-beta","icon":"https://raw.githubusercontent.com/simple-starters/icons/master/icon-tanzu-light.png","name":"microsauer","description":"","artifactId":"new-accelerator","projectName":"new-accelerator","branch":"master","url":"https://github.com/assafsauer/micro-spring/tree/master/02.restful-web-services"}
┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input10507273501789316297, --data-values-file, /tmp/accelerator-options15647238214583550552.json, --output-files, /tmp/ytt-output8763689404034735426]
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
