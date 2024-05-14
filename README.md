# azure-login
Hyperskill GitHub Action | Azure Install and login

```yaml
- uses: hyperskill/azure-login@v3.0.0
  with:
    client_id: ${{ secrets.CLIENT_ID }}
    client_secret: ${{ secrets.CLIENT_SECRET }}
    subscription_id: ${{ secrets.SUBSCRIPTION_ID }}
    tenant_id: ${{ secrets.TENANT_ID }}
```
