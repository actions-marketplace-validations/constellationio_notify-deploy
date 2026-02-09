# notify-deploy

# Usage in Github Actions Code:

- name: Notify Constellation of deployment
  uses: constellationio/notify-deploy@v1
  with:
    api-key: ${{ secrets.CONSTELLATION_API_KEY }}
    service: payments
    environment: production
