# kubectl -n argocd get secrets argocd-initial-admin-secret -o json

# kubectl -n argocd get secrets argocd-initial-admin-secret -o json | jq .data.password -r

# kubectl -n argocd get secrets argocd-initial-admin-secret -o json | jq .data.password -r | base64 -d

