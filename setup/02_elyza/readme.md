# vllm サーバのデプロイ

../../vllm/gpu/README.md 参照

REPO_TOP_DIR/vllm/gpu/gitops ディレクトリに移動

```
oc new-project elyza
kustomize build . | oc apply -f -
